# Git Workflow and History Management

## Overview

This repository demonstrates basic Git workflow operations and history management. The purpose of this assignment is to practice working with commits, rewriting history, recovering lost work, and organizing a repository using Git.

---

## Tasks Completed

### 1. Initialize Repository

A new Git repository was initialized and a file `project.txt` was created and committed.

### 2. Create Messy Commits

Several commits with unclear messages were intentionally created to simulate a messy commit history.
messy commits:
* add
* stuff
* update
* another update
* final

### 3. Clean Up Commit History

Using **interactive rebase**, the messy commits were rewritten and squashed into meaningful commits with clear messages.
command used:
git rebase -i HEAD~4

### 4. Simulate a Lost Commit

A commit was intentionally removed to simulate a mistake in the repository history.

### 5. Recover Lost Commit

The lost commit was recovered using:
git reflog

### 6. Create a Branch from Recovered Commit

A new branch was created from the recovered commit to continue development without losing work.
command used:
git checkout -b recovered-branch 238a6ed

### 7. Create a Custom Git Alias

A custom alias was added to make it easier to visualize the repository history.

alias used:
git graph = git log --oneline --graph --decorate --all

A screenshot is in the folder alias.png


### 8. Tag a Release

The cleaned repository was tagged as version:

v1.0

### 9. Push to GitHub

The repository was pushed to GitHub.

---

## Commands Practiced

* git init
* git add
* git commit
* git rebase -i
* git reflog
* git branch
* git checkout
* git tag
* git push

