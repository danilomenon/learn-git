
# Basic Git Commands for Beginners

This document presents the most commonly used Git commands in daily version control tasks for beginners.

---

## Initialization and Configuration

### Initialize a Git repository
```bash
git init
```
Initializes a new Git repository in the current directory.

### Clone an existing repository
```bash
git clone <repository-url>
```
Copies a remote repository to your local machine.

---

## Version Control

### Check the status of the repository
```bash
git status
```
Shows the current status of the repository, including modified, untracked files, and those ready for commit.

### Add files to the index (staging area)
```bash
git add <file-name>
```
Adds files to the index to prepare them for commit. Use `.` to add all files.

### Commit changes
```bash
git commit -m "Commit message"
```
Records the changes added to the index with a descriptive message.

---

## Working with Branches

### Create a new branch
```bash
git branch <branch-name>
```
Creates a new branch with the specified name.

### Switch to an existing branch
```bash
git checkout <branch-name>
```
Switches to a specific branch.

### Create and switch to a branch simultaneously
```bash
git checkout -b <branch-name>
```
Creates and switches to the new branch at the same time.

---

## Remote Repositories

### Add a remote repository
```bash
git remote add origin <repository-url>
```
Links the local repository to a remote one (for example, on GitHub).

### Push commits to the remote repository
```bash
git push origin <branch-name>
```
Sends changes from the current branch to the remote repository.

### Update the local repository
```bash
git pull origin <branch-name>
```
Fetches the latest changes from the remote repository.

---

These commands are ideal for getting started with Git. As you gain more experience, you can explore more advanced commands to optimize your workflow!
