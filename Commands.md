# Git Commands Guide

# 1. Basic Setup

**Initialize Git Repository**

'git init'

Initializes a new Git repository in the current directory.

**Set Username and Email**

'git config --global user.name "Your Name"'

'git config --global user.email "your.email@example.com"'

Sets global Git configuration for your username and email.

**Check Configuration**

'git config --list'

Lists all Git configuration settings for the user.

# 2. Working with Files

**Add a New File**

'echo "File content" > filename.txt'

Creates a new file and adds text content to it.

**Edit a File Using vim**

'vim filename.txt'

Opens the filename.txt file in vim editor for editing.

**List Files**

'ls'

Lists all files in the current directory.

**Remove a File**

'rm filename.txt'

Deletes filename.txt from the working directory.

# 3. Staging and Committing

**Stage a File**

'git add filename.txt'

Stages filename.txt for the next commit.

**Unstage a File**

'git rm --cached filename.txt'

Removes the file from the staging area without deleting it.

**Commit Changes**

'git commit -m "Commit message"'

Commits the staged changes with a descriptive message.

**View Git Status**

'git status'

Shows the status of changes in the working directory and staging area.

# 4. Branching and Switching Branches

**Create a Branch**

'git branch branch-name'

Creates a new branch called branch-name.

**View All Branches**

'git branch -a'

Lists all branches in the repository, including remote-tracking branches.

**Switch to a Branch**

'git checkout branch-name'

Switches to branch-name.

**Rename Branch**

'git branch -m old-branch-name new-branch-name'

Renames the branch from old-branch-name to new-branch-name.

# 5. Working with Remote Repositories

**Add Remote Repository**

'git remote add origin https://github.com/username/repo.git'

Adds a remote repository with the alias origin.

**Change Remote URL**

'git remote set-url origin git@github.com:username/repo.git'

Sets the URL for the remote repository to use SSH instead of HTTPS.

**View Remote URL**

'git remote -v'

Displays the remote repository URL(s) associated with the current repo.

**Fetch Changes from Remote**

'git fetch origin'

Fetches changes from the remote repository without merging.
