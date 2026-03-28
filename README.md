# repo3

A collection of small projects including a Voter ID card generator (HTML/JS), sample C programs, and a Python GUI project.

## Projects

- **voterid.html** – Browser-based Voter ID card generator form
- **filename.c** – Simple "Hello, World!" C program
- **Kabutar/1.c** – Basic C program
- **Python-GUI-Project/** – Python GUI starter files

## Getting Started

### Clone the repository

```bash
git clone https://github.com/245123748025-code/repo3.git
cd repo3
```

### Push to GitHub (fixing "Repository not found")

A common cause of the `fatal: repository '...' not found` error is an incorrect remote URL. To fix it:

1. **Check your current remote URL:**

   ```bash
   git remote -v
   ```

2. **Set the correct remote URL** (replace with your actual repository URL):

   ```bash
   git remote set-url origin https://github.com/<your-username>/<your-repo>.git
   ```

   For this repository:

   ```bash
   git remote set-url origin https://github.com/245123748025-code/repo3.git
   ```

3. **Push your changes:**

   ```bash
   git push -u origin master
   ```

### Starting fresh with a new repository

If you are setting up a new repository:

```bash
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin master
```

> **Note:** Make sure the repository already exists on GitHub before pushing. Create it at https://github.com/new first.
