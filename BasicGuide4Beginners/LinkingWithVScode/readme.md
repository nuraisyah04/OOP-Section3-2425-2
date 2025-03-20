
# 📝 Instructions for Students - Folder Setup, GitHub + VS Code, and Lab Submissions

## 🛠 Step 0: Linking GitHub with Visual Studio Code (VS Code)

### 🔗 Step 0.1: Install VS Code

1. Download and install Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/).
2. Launch VS Code after installation.

### 🔗 Step 0.2: Install Git in VS Code

Make sure Git is installed on your system and detected by VS Code:
```bash
git --version
```

### 🔗 Step 0.3: Install GitHub Extension in VS Code

1. Open VS Code.
2. Click the **Extensions** icon on the sidebar (or press `Ctrl+Shift+X`).
3. Search for **"GitHub Pull Requests and Issues"**.
4. Click **Install**.

### 🔗 Step 0.4: Sign in to GitHub from VS Code

1. Click on the **Accounts icon** (bottom left corner of VS Code).
2. Choose **"Sign in to GitHub"**.
3. Complete the sign-in process via your browser.

### 🔗 Step 0.5: Clone a GitHub Repository in VS Code

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac).
2. Type **"Git: Clone"** and select it.
3. Paste your GitHub repository URL.
4. Choose a folder location on your computer.
5. Click **"Open"** when prompted.

### 🔗 Step 0.6: Git Commands in VS Code

- **Stage**: Go to **Source Control** panel and click **"+"** next to the file.
- **Commit**: Write a commit message and click **✔ Commit**.
- **Push**: Click **..." More Actions"** and select **Push**.
- **Pull**: Click **..." More Actions"** and select **Pull**.

---

## 📂 Step 1: Create Your Own Folder

1. Inside the **`StudentFile/`** directory, create a folder with your **full name** or **student ID**.
   
   **Example:**
   ```
   StudentFile/JohnDoe/
   ```
   or
   ```
   StudentFile/A22CS1234/
   ```

---

## 📄 Step 2: Setup Your Profile in `README.md`

1. Inside your folder, create a file named `README.md`.

```markdown
# Student Profile

- **Full Name:** John Doe
- **Student ID:** A22CS1234
- **Course:** Object Oriented Programming (SECJ2154)
- **Email:** johndoe@example.com
- **GitHub Username:** johndoe123

## About Me
> Write a short introduction about yourself and your learning goals.
```

---

## 💻 Step 3: Lab Exercises Submission

1. Create a new subfolder for each lab inside your personal folder.

   **Example:**
   ```
   StudentFile/JohnDoe/Lab1/
   ```

2. Continue for each lab:
   ```
   StudentFile/JohnDoe/Lab2/
   StudentFile/JohnDoe/Lab3/
   ...
   ```

---

## 🔄 Step 4: Push Your Work to GitHub

```bash
git add StudentFile/YourFolderName/
git commit -m "Add Lab X files"
git push origin main
```

---

## 🎯 Final Folder Structure Example:

```
StudentFile/
└── JohnDoe/
    ├── README.md
    ├── Lab1/
    │   ├── lab1_code.java
    │   └── lab1_report.pdf
    ├── Lab2/
    │   ├── lab2_code.java
    │   └── lab2_report.pdf
    └── Lab3/
        └── ...
```

---

## ✅ Tips:
- Keep commit messages clear (e.g., `"Completed Lab 3 with all required files"`).
- Do **NOT** modify other students' folders.
