# git-github-commands

This repository is a summary of Git and GitHub commands I practiced while learning version control.

Git is used to track changes locally on my computer. GitHub is used to store repositories online and push code to a remote location.

---

## git setup commands

| command              | what it does                              |
| -------------------- | ----------------------------------------- |
| `git init`           | Starts Git tracking in the current folder |
| `git status`         | Shows the current state of the project    |
| `git branch`         | Shows the branches in the repository      |
| `git branch -M main` | Renames the current branch to `main`      |

---

## staging and committing commands

| command                          | what it does                        |
| -------------------------------- | ----------------------------------- |
| `git add .`                      | Stages all changed files            |
| `git add file-name`              | Stages one specific file            |
| `git commit -m "commit message"` | Saves staged changes with a message |

---

## github remote commands

| command                                | what it does                                          |
| -------------------------------------- | ----------------------------------------------------- |
| `git remote add origin repository-url` | Connects a local project to a GitHub repository       |
| `git remote -v`                        | Shows the connected GitHub remote                     |
| `git push -u origin main`              | Pushes the `main` branch to GitHub for the first time |
| `git push`                             | Pushes new commits to GitHub                          |
| `git pull`                             | Pulls the newest changes from GitHub                  |

---

## clone command

| command                    | what it does                                 |
| -------------------------- | -------------------------------------------- |
| `git clone repository-url` | Copies a GitHub repository onto the computer |

---

## branch commands

| command                                      | what it does                                    |
| -------------------------------------------- | ----------------------------------------------- |
| `git checkout -b branch-name`                | Creates a new branch and switches to it         |
| `git checkout branch-name`                   | Switches to an existing branch                  |
| `git push --set-upstream origin branch-name` | Pushes a new branch to GitHub                   |
| `git branch -d branch-name`                  | Deletes a local branch after it has been merged |
| `git branch -D branch-name`                  | Force deletes a local branch                    |

---

## practice commands

```bash
git init
git status
git branch
git branch -M main
git add .
git add file-name
git commit -m "commit message"
git remote add origin repository-url
git remote -v
git push -u origin main
git push
git pull
git clone repository-url
git checkout -b branch-name
git checkout branch-name
git push --set-upstream origin branch-name
git branch -d branch-name
git branch -D branch-name
```

---

## common git workflow

```bash
git status
git add .
git commit -m "Describe the change"
git push
```

---

## new project workflow

```bash
mkdir my-project
cd my-project
git init
touch README.md
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main
```

---

## pull request branch workflow

```bash
git checkout -b update-readme
git add .
git commit -m "Update README"
git push --set-upstream origin update-readme
```

---

## what I practiced

* Starting a Git repository
* Checking the status of a project
* Staging files
* Committing changes
* Connecting a project to GitHub
* Pushing code to GitHub
* Pulling updates from GitHub
* Cloning repositories
* Creating and switching branches
* Deleting local branches
* Understanding the difference between Git and GitHub
