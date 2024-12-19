# Git Commands Guide

A comprehensive list of commonly used Git commands for managing repositories effectively.

## Table of Contents

1. [Initializing and Cloning Repositories](#initializing-and-cloning-repositories)
2. [Working Directory and Staging Area](#working-directory-and-staging-area)
3. [Committing Changes](#committing-changes)
4. [Branch Management](#branch-management)
5. [Remote Repositories](#remote-repositories)
6. [Stashing Changes](#stashing-changes)
7. [Reverting and Resetting](#reverting-and-resetting)
8. [Configuration](#configuration)
9. [Pulling and Fetching](#pulling-and-fetching)
10. [Miscellaneous](#miscellaneous)

---

### Initializing and Cloning Repositories

- **`git init`** - Initialize a Git repository.
- **`git clone <repository>`** - Clone an existing repository.

### Working Directory and Staging Area

- **`git status`** - Check the status of the working directory and staging area.
- **`git add <filename>`** - Add the file to the staging area.
- **`git add .`** - Add all files in the working directory to the staging area.

### Committing Changes

- **`git commit -m "message"`** - Commit and save the staged changes with a message.
- **`git commit --amend`** - Rewrite the commit history.

### Branch Management

- **`git branch`** - Show all branches.
- **`git branch <name>`** - Create a new branch.
- **`git diff <branch1> <branch2>`** - Show differences between two branches.
- **`git branch -d <branch name>`** - Delete a branch.
- **`git branch -D <branch name>`** - Forcefully delete a branch.
- **`git merge <branch>`** - Merge a branch into the current one.
- **`git rebase <branch>`** - Rebase a branch to include changes from another branch.

### Remote Repositories

- **`git remote add origin <repo url>`** - Link the local repository to a remote repository.
- **`git push origin <branch name>`** - Push committed changes to the remote repository.
- **`git remote`** - List all remote repositories associated with the current repository.
- **`git remote -v`** - Display the names and URLs of the remote repositories.
- **`git remote remove <name>`** - Remove a remote repository.
- **`git remote rename <old name> <new name>`** - Rename a remote repository.

### Stashing Changes

- **`git stash`** - Stash staged files without committing.
- **`git stash -u`** - Stash working directory files without committing.
- **`git stash pop`** - Retrieve stashed changes.

### Reverting and Resetting

- **`git revert <commit id>`** - Revert to a previous commit.
- **`git reset <file>`** - Unstage a file while retaining changes in the working directory.
- **`git reset --mixed`** - Discard changes in the local repository and staging area.
- **`git reset --soft`** - Discard changes only in the local repository.
- **`git reset --hard`** - Discard changes in the working directory, staging area, and local repository.
- **`git rm <filename>`** - Remove a file from the staging area and working directory.
- **`git rm --cached <filename>`** - Remove a file from the staging area.
- **`git restore --staged <filename>`** - Remove a file from the staging area.

### Configuration

- **`git config --global user.name "Your Name"`** - Set a global username.
- **`git config --global user.email "your-email@example.com"`** - Set a global email address.

### Pulling and Fetching

- **`git pull`** - Retrieve changes from a remote repository.
- **`git fetch`** - Download changes from a remote repository without modifying the working directory.

### Miscellaneous

- **`git log`** - Show commit history.
- **`git log --oneline`** - Show commit history in a single line.
- **`git branch -r`** - List remote branches.
- **`git branch -a`** - List all branches, both local and remote.
- **`git cherrypick <commit id>`** - Apply a commit from one branch to another.
