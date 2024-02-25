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

- Configure git with your name and email. This is done by running the following command in the terminal.

```bash
git config --global user.name "Your Name"
git config --global user.email "Your Email"
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

- To create a branch and merge at the same time you can do this as a shortcut in terminal.

```bash
git switch -c <branch-name>
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

## Git rebase

- Definition: Rebase is the process of moving or combining a sequence of commits to a new base commit.

- Rebase a branch onto the current branch. This is done by running the following command in the terminal.

```bash
git rebase <branch-name>
```

- Continue a rebase after resolving conflicts. This is done by running the following command in the terminal.

```bash
git rebase --continue
```

- Abort a rebase. This is done by running the following command in the terminal.

```bash
git rebase --abort
```

## Git stash

- Definition: Stashing is the process of temporarily storing changes

- Stash changes. This is done by running the following command in the terminal.

```bash
git stash
```

- Show the list of stashes. This is done by running the following command in the terminal.

```bash
git stash list
```

- Apply a stash. This is done by running the following command in the terminal.

```bash
git stash apply
```

- Delete a stash. This is done by running the following command in the terminal.

```bash
git stash drop
```

- Delete all stashes. This is done by running the following command in the terminal.

```bash
git stash clear
```

## Git remote

- Definition: A remote is a common repository that all team members use to exchange their changes.

- Clone a repository. This is done by running the following command in the terminal.

```bash
git clone <repository-url>
```

- Add a remote repository. This is done by running the following command in the terminal.

```bash
git remote add <remote-name> <repository-url>
```

- Adding fine-grained permissions to a remote repository. This is done by running the following command in the terminal.

```bash
git remote set-url <remote-name> <https://<token>@github.com/username/repo_name>
```

- Show the list of remote repositories. This is done by running the following command in the terminal.

```bash
git remote -v
```

- Pull changes from a remote repository. This is done by running the following command in the terminal.

```bash
git pull <remote-name> <branch-name>
```

- Push changes to a remote repository. This is done by running the following command in the terminal.

```bash
git push <remote-name> <branch-name>
```

- Remove a remote repository. This is done by running the following command in the terminal.

```bash
git remote remove <remote-name>
```

## Git tags

- Definition: A tag is a reference to a specific commit.

- Create a tag. This is done by running the following command in the terminal.

```bash
git tag <tag-name>
```

- Show the list of tags. This is done by running the following command in the terminal.

```bash
git tag
```

- Delete a tag. This is done by running the following command in the terminal.

```bash
git tag -d <tag-name>
```

- Push a tag to a remote repository. This is done by running the following command in the terminal.

```bash
git push <remote-name> <tag-name>
```

- Delete a tag from a remote repository. This is done by running the following command in the terminal.

```bash
git push <remote-name> --delete <tag-name>
```

## Learning References

- [Git Documentation](https://git-scm.com/doc)
- [Learn Git Branching](https://learngitbranching.js.org/)

## Github profile generator

- [Github Profile Generator](https://profilinator.rishav.dev/)
