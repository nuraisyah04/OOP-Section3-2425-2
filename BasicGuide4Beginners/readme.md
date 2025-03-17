
# 🚀 GitHub Basic Operations Guide (For First-Time Users)

## 📌 Introduction

This guide will walk you through the essential steps to start using GitHub after registration, including setting up Git locally and performing basic operations.

---

## 🛠 Step 1: Install Git on Your Computer

### For Windows:
1. Go to [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Download and run the installer.
3. Follow the default installation settings.

### For macOS:
```bash
brew install git
```

### For Linux:
```bash
sudo apt-get install git
```

---

## 🛠 Step 2: Configure Git (First-Time Setup)

Open **Terminal** or **Command Prompt** and run the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

Verify the configuration:

```bash
git config --list
```

---

## 🛠 Step 3: Create a New Repository on GitHub

1. Login to [GitHub](https://github.com)
2. Click the **"+"** icon at the top-right corner and select **"New repository"**.
3. Fill out:
   - **Repository name** (e.g., `my-first-repo`)
   - Optional: **Description**
   - **Public** or **Private**
   - ✅ (optional) **Initialize this repository with a README**
4. Click **Create repository**.

---

## 🛠 Step 4: Clone the Repository to Your Local Machine

1. In your GitHub repo page, click the **Code** button and copy the URL (HTTPS or SSH).
2. In your terminal:

```bash
git clone https://github.com/your-username/my-first-repo.git
```

3. Navigate into the project folder:

```bash
cd my-first-repo
```

---

## 🛠 Step 5: Add or Create Files Locally

Create a simple file inside your project folder:

```bash
echo "# My First GitHub Project" > README.md
```

Or create/edit files using any text editor (e.g., VS Code, Notepad++).

---

## 🛠 Step 6: Stage and Commit Changes

### Stage all new or changed files:

```bash
git add .
```

### Commit the changes with a message:

```bash
git commit -m "Initial commit"
```

---

## 🛠 Step 7: Push Changes to GitHub

Push your changes to the **main** branch:

```bash
git push origin main
```

_For older repositories, you may need to push to `master`:_

```bash
git push origin master
```

---

## 🛠 Step 8: Check Your Repository on GitHub

1. Go to your repository page on [GitHub](https://github.com).
2. Refresh the page to see your committed files and commit history.

---

## 🛠 Step 9: Basic Workflow for Future Changes

For all future updates, repeat these steps:
1. Make changes to your files.
2. Stage the changes:
   ```bash
   git add .
   ```
3. Commit the changes:
   ```bash
   git commit -m "your commit message"
   ```
4. Push to GitHub:
   ```bash
   git push origin main
   ```

---

## 🛠 Step 10: Pull Latest Changes (Collaboration)

If you are working with a team, always pull the latest changes before making new commits:

```bash
git pull origin main
```

---

## 🛠 Optional: Create and Use Branches

### Create a new branch:

```bash
git checkout -b feature-branch
```

### Switch to an existing branch:

```bash
git checkout main
```

### Push the new branch to GitHub:

```bash
git push origin feature-branch
```

---

## 🛠 Optional: Open a Pull Request (PR)

1. On GitHub, switch to your new branch.
2. Click **"Compare & pull request"**.
3. Add a title and description.
4. Click **"Create pull request"**.
5. After review, click **"Merge pull request"** to merge it into **main**.

---

## ✅ You're Done! 🎉

You now know how to:
- Set up Git and GitHub
- Clone repositories
- Stage, commit, and push changes
- Work with branches and pull requests

---

## 🔄 Quick Commands Summary

```bash
git clone <repo-url>
git add .
git commit -m "your message"
git push origin <branch-name>
git pull origin <branch-name>
git checkout -b <new-branch>
```

---

## 📚 Helpful Resources

- [GitHub Docs](https://docs.github.com/en)
- [Git Cheat Sheet PDF](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub Learning Lab](https://lab.github.com/)

---

**Tip:** For GUI users, you can also install [GitHub Desktop](https://desktop.github.com/) to manage your repositories visually.

