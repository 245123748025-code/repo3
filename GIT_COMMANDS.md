# 10 Essential Git Commands to Get Started from Scratch

A quick reference guide for the most important Git commands every developer should know.

---

## 1. `git init`
**Initialize a new Git repository**

Creates a new `.git` folder in your current directory, turning it into a Git repository.

```bash
git init
```

---

## 2. `git clone`
**Copy an existing repository**

Downloads a remote repository to your local machine.

```bash
git clone https://github.com/user/repository.git
```

---

## 3. `git status`
**Check the state of your working directory**

Shows which files are staged, unstaged, or untracked.

```bash
git status
```

---

## 4. `git add`
**Stage changes for the next commit**

Adds a specific file or all changed files to the staging area.

```bash
# Stage a single file
git add filename.txt

# Stage all changed files
git add .
```

---

## 5. `git commit`
**Save staged changes to the repository history**

Creates a snapshot of your staged changes with a descriptive message.

```bash
git commit -m "Your commit message here"
```

---

## 6. `git push`
**Upload local commits to a remote repository**

Sends your committed changes to a remote branch (e.g., on GitHub).

```bash
git push origin main
```

---

## 7. `git pull`
**Download and integrate remote changes**

Fetches the latest changes from the remote and merges them into your current branch.

```bash
git pull origin main
```

---

## 8. `git branch`
**Manage branches**

Lists all branches, creates a new branch, or deletes one.

```bash
# List all branches
git branch

# Create a new branch
git branch feature-login

# Delete a branch
git branch -d feature-login
```

---

## 9. `git checkout`
**Switch branches or restore files**

Switches to a different branch or creates and switches to a new one.

```bash
# Switch to an existing branch
git checkout main

# Create and switch to a new branch
git checkout -b feature-signup
```

---

## 10. `git log`
**View commit history**

Displays a list of past commits with their messages, authors, and timestamps.

```bash
# Full log
git log

# Compact one-line log
git log --oneline
```

---

## Quick Workflow Example

```bash
# 1. Initialize a new project
git init my-project
cd my-project

# 2. Create a file and track it
echo "Hello, Git!" > hello.txt
git add hello.txt

# 3. Save your first commit
git commit -m "Initial commit"

# 4. Connect to a remote repository
git remote add origin https://github.com/user/my-project.git

# 5. Push to GitHub
git push -u origin main
```
