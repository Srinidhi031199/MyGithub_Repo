# 🚀 Git & GitHub Basics – Complete Command Guide

This repository contains all essential **Git** and **GitHub** commands required for beginners to work with version control efficiently.

---

# 📌 1️⃣ Git Installation

### 🔹 Check Git Version

```bash
git --version
```

### 🔹 Configure Git (First Time Setup)

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### 🔹 Verify Configuration

```bash
git config --list
```

---

# 📌 2️⃣ Initialize Repository

### 🔹 Initialize a New Git Repository

```bash
git init
```

### 🔹 Clone an Existing Repository

```bash
git clone <repository-url>
```

Example:

```bash
git clone https://github.com/username/repository-name.git
```

---

# 📌 3️⃣ Basic Workflow Commands

### 🔹 Check Status

```bash
git status
```

### 🔹 Add Files to Staging Area

```bash
git add filename
```

Add all files:

```bash
git add .
```

### 🔹 Commit Changes

```bash
git commit -m "Your commit message"
```

---

# 📌 4️⃣ Branching Commands

### 🔹 View Branches

```bash
git branch
```

### 🔹 Create New Branch

```bash
git branch branch-name
```

### 🔹 Switch Branch

```bash
git checkout branch-name
```

OR (recommended)

```bash
git switch branch-name
```

### 🔹 Create & Switch Branch

```bash
git checkout -b branch-name
```

---

# 📌 5️⃣ Remote Repository Commands

### 🔹 Add Remote Repository

```bash
git remote add origin <repository-url>
```

### 🔹 View Remote

```bash
git remote -v
```

### 🔹 Push Code to GitHub

```bash
git push -u origin branch-name
```

Example:

```bash
git push -u origin main
```

### 🔹 Pull Latest Changes

```bash
git pull origin branch-name
```

### 🔹 Fetch Changes

```bash
git fetch
```

---

# 📌 6️⃣ Undo Commands

### 🔹 Undo Last Commit (Keep Changes)

```bash
git reset --soft HEAD~1
```

### 🔹 Undo Last Commit (Remove Changes)

```bash
git reset --hard HEAD~1
```

### 🔹 Unstage File

```bash
git restore --staged filename
```

---

# 📌 7️⃣ Log & History

### 🔹 View Commit History

```bash
git log
```

Compact View:

```bash
git log --oneline
```

Graph View:

```bash
git log --oneline --graph --all
```

---

# 📌 8️⃣ Stashing

### 🔹 Save Changes Temporarily

```bash
git stash
```

### 🔹 View Stash List

```bash
git stash list
```

### 🔹 Apply Stash

```bash
git stash apply
```

### 🔹 Drop Stash

```bash
git stash drop
```

---

# 📌 9️⃣ Merge & Rebase

### 🔹 Merge Branch

```bash
git merge branch-name
```

### 🔹 Rebase

```bash
git rebase branch-name
```

---

# 📌 🔐 GitHub Authentication (Important)

GitHub no longer supports password authentication.

### Use Personal Access Token (PAT)

1. Go to GitHub → Settings → Developer Settings → Personal Access Token
2. Generate token
3. Use token instead of password when pushing

OR Use SSH:

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
```

Add SSH key to GitHub account.

---

# 📌 1️⃣0️⃣ Remove Remote Repository

```bash
git remote remove origin
```

---

# 📌 Common Errors & Fixes

### ❌ Authentication Failed

✔ Use Personal Access Token instead of password.

### ❌ Repository Not Found

✔ Check repository URL
✔ Ensure repo exists
✔ Check access permissions

---

# 🎯 Basic Git Workflow Summary

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

---

# 📚 Best Practices

* Write meaningful commit messages
* Pull before pushing
* Use branches for new features
* Never commit sensitive data
* Keep `.gitignore` updated

---

# 👩‍💻 Happy Coding!

If you’re learning Git & GitHub, practice these commands regularly to build strong version control skills.

---

