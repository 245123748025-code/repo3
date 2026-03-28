# My Project

A collection of student projects including a Voter ID form (HTML/CSS/JS), C programs, and a Python GUI project.

## Projects

1. **voterid** – Voter ID registration form built with HTML, CSS, and JavaScript.
2. **filename.c** – A simple "Hello, World!" program in C.
3. **Kabutar/1.c** – A basic C program that prints a greeting.
4. **Python-GUI-Project** – Starter files for a Python GUI project.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/user/my-project.git
cd my-project
```

### Git Setup – Fix "src refspec main does not match any"

If you see this error when pushing:

```
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/user/my-project.git'
```

It means your local branch is not named `main`. Fix it with one of these options:

**Option 1 – Rename your current branch to `main`:**

```bash
git branch -M main
git push -u origin main
```

**Option 2 – Set `main` as the default branch for all new repositories:**

```bash
git config --global init.defaultBranch main
```

Then for a new project:

```bash
git init
git add .
git commit -m "Initial commit"
git push -u origin main
```
