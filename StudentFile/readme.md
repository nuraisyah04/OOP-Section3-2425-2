
# 📝 Instructions for Students - Folder Setup & Lab Submissions

## 📂 Step 1: Create Your Own Folder

1. Inside the provided **`StudentFile/`** directory, create a folder with your **full name** or **student ID**.
   
   **Example:**
   ```
   StudentFile/JohnDoe/
   ```
   or
   ```
   StudentFile/A22CS1234/
   ```

2. This will be your personal workspace for the entire semester.

---

## 📄 Step 2: Setup Your Profile in `README.md`

1. Inside your personal folder (e.g., `StudentFile/JohnDoe/`), create a file named `README.md`.

2. In the `README.md` file, include the following profile details:

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

1. For every lab exercise, **create a new subfolder** inside your personal folder.

   **Example for Lab 1:**
   ```
   StudentFile/JohnDoe/Lab1/
   ```

2. Save your lab codes, reports, and any related files inside the correct lab folder.

3. Continue this structure for each lab:
   ```
   StudentFile/JohnDoe/Lab2/
   StudentFile/JohnDoe/Lab3/
   ...
   ```

---

## 🔄 Step 4: Push Your Work to GitHub

Each time you complete a lab, you must push your work to GitHub inside your **own folder**.

### Workflow:
```bash
# Stage your changes
git add StudentFile/YourFolderName/

# Commit your changes
git commit -m "Add Lab X files"

# Push your changes
git push origin main
```

_Replace **YourFolderName** with your actual folder name._

---

## 🚦 Important Notes:
- Do **NOT** modify or submit work in another student's folder.
- Ensure your folder and file names are **clear** and **organized**.
- All lab submissions must be inside your personal folder only.
- Keep your `README.md` updated if there are any profile changes.

---

✅ **Good practice:** Commit and push your work after every lab to avoid missing submissions.

---

## 🎯 Final Deliverable Structure Example:

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

## 🖼 Example Screenshot (recommended)

You can include a screenshot like this in your `README.md` or submission report:

![example structure](https://via.placeholder.com/600x300?text=Example+Folder+Structure)

---

## 💡 Tip:
Use meaningful commit messages such as `"Completed Lab 3 with all required files"`.

