# Git & GitHub Commands

This repository contains Git and GitHub commands I practiced while learning setup, remotes, staging, commits, branches, and cloning.

## Git Setup

| Command              | What It Does                              |
| -------------------- | ----------------------------------------- |
| `git init`           | Initializes a Git repository              |
| `git status`         | Shows the current state of the project    |
| `git branch`         | Shows the branches in the repository      |
| `git branch -M main` | Renames the current branch to `main`      |

---

## GitHub Remote Process

| Command                                | What It Does                                          |
| -------------------------------------- | ----------------------------------------------------- |
| `git remote add origin repository-url` | Connects a local project to a GitHub repository       |
| `git remote -v`                        | Shows the connected GitHub remote                     |
| `git push -u origin main`              | Pushes the `main` branch to GitHub for the first time |
| `git push`                             | Pushes new commits to GitHub                          |
| `git pull`                             | Pulls the newest changes from GitHub                  |

---

## Staging & Committing

| Command                          | What It Does                        |
| -------------------------------- | ----------------------------------- |
| `git add .`                      | Stages all changed files            |
| `git add file-name`              | Stages one specific file            |
| `git commit -m "commit message"` | Saves staged changes with a message |

---

## Branching

| Command                                      | What It Does                                    |
| -------------------------------------------- | ----------------------------------------------- |
| `git checkout -b branch-name`                | Creates a new branch and switches to it         |
| `git checkout branch-name`                   | Switches to an existing branch                  |
| `git push --set-upstream origin branch-name` | Pushes a new branch to GitHub                   |
| `git branch -d branch-name`                  | Deletes a local branch after it has been merged |
| `git branch -D branch-name`                  | Force deletes a local branch                    |

---

## Cloning

| Command                    | What It Does                                 |
| -------------------------- | -------------------------------------------- |
| `git clone repository-url` | Copies a GitHub repository onto the computer |
