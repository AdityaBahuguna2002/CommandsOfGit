# Git Commands Guide

This guide quickly references commonly used Git commands for configuring, managing, and working with your Git repository.

## Configuration

Set your name and email for Git commits:

```bash
git config --global user.name "your name"
git config --global user.email "youremail@gmail.com"
```

## Working with Remote Repositories

Show the remote repositories associated with your project:

```bash
git remote -v
```

## Tracking Changes

View the changes that have occurred in your files:

```bash
git status
```

## Staging and Committing Changes

Add all files to the staging area:

```bash
git add .
```

Add a specific file to the staging area:

```bash
git add <file_name_type_here>
```

Commit your changes from the staging area to the repository:

```bash
git commit -m "type your message here"
```

View the commit history:

```bash
git log
```

## Branching

Create a new branch:

```bash
git branch branch-name
```

Switch between branches:

```bash
git checkout branch-name
```

Create a branch and switch to it simultaneously:

```bash
git checkout -b branch-name
```

## Merging Branches

Switch to the branch you want to merge into (e.g., `main`):

```bash
git checkout main
```

Merge another branch into it:

```bash
git merge branch-name
```

## Pushing and Pulling Changes

Push local commits to the remote repository:

```bash
git push origin branch-name
```

Pull the latest changes from the remote repository:

```bash
git pull
```

## Deleting Branches

Delete a local branch:

```bash
git branch -d branch-name
```

Delete a remote branch:

```bash
git push origin --delete branch-name
```