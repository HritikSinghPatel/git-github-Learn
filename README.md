# Learn Git & GitHub 

## Overview


This Git project provides hands-on experience in using Git and GitHub for effective project management. The primary objectives include initializing a Git repository, linking it to GitHub, committing and pushing changes, creating and managing branches, intentionally generating a merge conflict, resolving the conflict, and documenting the project using a comprehensive README file.


## 1. Repository Initialization and Push

### Install Git and Set Up GitHub Account

- Install Git: [Download Git](https://git-scm.com/downloads)
- Create a GitHub account: [GitHub Sign Up](https://github.com/join)

### Initialize Git Repository

Navigate to your project directory in the terminal and run.
Initialize Git Repository:

Navigate to your project directory in the terminal.



Commit and Push:

Add your changes: git add .
Commit changes: git commit -m "Initial commit"
Push to GitHub: git push -u origin main (assuming your branch is named "main").
Step 1:
Initialize Git Repository 
    
    git init

Step 2:
Create a New GitHub Repository:

Go to GitHub.

Click on the "+" in the top right corner and select "New repository."

Follow the instructions to create a new repository.
Link GitHub Repository to Local Repository:

step 3: Copy the repository URL from GitHub.
In your terminal, run

    git remote add origin https://github.com/HritikSinghPatel/git-github-Learn.git

Step 3: Create README File
Create a file named README.md in your project directory:

    touch README.md
This command creates an empty README file.

Step 3: Check Git Status
Check the status of your Git repository to see the untracked files:


    git status
The output will show that README.md is an untracked file.

Step 4: Commit Changes
Stage and commit the changes:

    git add .
    git commit -m "Initial commit with README.md"
These commands stage all changes and commit them with a message indicating the initial commit.

2. Resolve Author Identity Issue
Step 1: Set Your Git Identity
If you encounter the "Author identity unknown" issue, set your Git identity using the following commands:

    git config --global user.email "hritikpatel125@gmail.com"
    git config --global user.name "Hritik Patel"
These commands set your global Git identity. If you prefer to set the identity only for this repository, omit the --global flag.

Step 2: Commit Again
After setting your identity, commit your changes again:

    git commit -m "Added README.md file"
Now, your commits will include the correct author information.

Step 3: View Git Log
Check the Git log to verify your commits:

    git log
This command displays a log of your commits, confirming that the "Author identity unknown" issue has been resolved.
