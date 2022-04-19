---
layout: post
title: "Spring Blog 9 - GitHub Branches"
date: 2022-04-18 23:31:17 -700
categories: jekyll update
---

## **GitHub Branches**

Branches allows one to work on new features, fix bugs, or test new ideas in a secure portion of the repository. Git branches are similarly like a pointer to a snapshot of your changes. You create a new branch to capture your changes when you wish to add a new feature or solve a bug, no matter how big or small. 

A branch signifies a distinctive line of development. Branches are like an abstraction for the edit/stage/commit process. A branch is always created from an existing branch. You might create a new branch from the repository’s default branch. 

The main branch is where all changes get merged back into, and it is the official functioning version of the project. You do not make changes to the main branch while other group members are working on it. The changes to the main branch influences everyone’s progress and will result in merge conflicts. The main branch is deployable, and it is the product code. 

Here's an example of a Git Branch:

![Git branch](/assets/images/git-branch.png)

### Git branch commands
The git branch lets you create, list, and delete branches. Here are some of the common options of the git branch: 
- `git branch` - lists all of the branches in the repository.
  - `git branch –list` is another way to list all the branches.
- `git branch <branch>` - creates a new branch. This doesn’t check out the new branch. 
- `git branch -d <branch>` - deletes a branch. If there are unmerged changes, Git does not allow you to delete  
  - `git branch -D <branch>` - this command force the deletion of the branch.
- `git branch -a` - lists all remote branches. 

### Git checkout commands

The git checkout commands allow you to navigate between the branches created by the git branch. Checking out a branch modifies the files in the working directory to match the branch’s version. It also notifies Git to keep track of any new commits to that branch. 
- `git checkout -b <branch>` - creates a new branch and then checked out
- `git checkout <branch>` - switch to a branch in local repository 


**Other Git commands**
- `git log` - to show all commits in the current branch's history
- `git merge <branch>` - to merge the specified branch's history into the current one 
