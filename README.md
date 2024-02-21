# Introduction

## What is Git?

Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.

## What is Github?

Github is a cloud-based hosting service that lets you manage Git repositories. It provides a web-based graphical interface for software development and project management.

## Why use Git?

- Manage versions
- Track historical changes
- Create backups
- Allow reversal changes
- Allow collaboration

## Difference between Git and Github

Git is a version control system that lets you manage and keep track of your source code history. Github is a cloud-based hosting service that lets you manage Git repositories.

## Installing Git

For windows, you can download the installer from the following link: [Git](https://git-scm.com/download/win)

For Ubuntu users, you can use the following command to install Git.

```bash
sudo apt-get install git
```

## Git basics

- Initiate git in a folder to allow version control. This is done by running the following command in the terminal.

```bash
git init
```

- Showing the status of the repository. This is done by running the following command in the terminal.

```bash
git status
```

- Add files to the staging area. This is done by running the following command in the terminal.

```bash
git add <file>
```

- Commit changes to the repository. This is done by running the following command in the terminal.

```bash
git commit -m "commit message"
```

- Show the history of the repository. This is done by running the following command in the terminal.

```bash
git log
```

## Git branches

- Definition: A branch represents an independent line of development. It allows you to work on different parts of the project simultaneously.

- Create a new branch. This is done by running the following command in the terminal.

```bash
git branch <branch-name>
```

- Switch to a branch. This is done by running the following command in the terminal.

```bash
git checkout <branch-name>
```

- Rename a branch. This is done by running the following command in the terminal.

```bash
git branch -m <new-branch-name>
```

- Delete a branch. This is done by running the following command in the terminal.

```bash
git branch -d <branch-name>
```

- Reverse changes in a branch. This is done by running the following command in the terminal.

```bash
git revert <commit-id>
```

- Revert changes using HEAD. This is done by running the following command in the terminal.

```bash
git reset HEAD~<number-of-commits>
```

- Revert changes while keeping the changes in the working directory. This is done by running the following command in the terminal.

```bash
git reset --soft HEAD~<number-of-commits>
```

- Revert changes while deleting the changes in the working directory. This is done by running the following command in the terminal.

```bash
git reset --hard HEAD~<number-of-commits>
```

- Retrieve changes from a branch. This is done by running the following command in the terminal.

```bash
git reflog
git checkout -b <branch-name> <commit-id>
```

## Git merge

- Definition: Merging is the process of combining two or more branches into a single branch.

- Merge a branch into the current branch. This is done by running the following command in the terminal. (Fast forward merge)

```bash
git merge <branch-name>
```

- Abort a merge. This is done by running the following command in the terminal.

```bash
git merge --abort
```

-6 What is a commit?

-7 What is a pull request?
