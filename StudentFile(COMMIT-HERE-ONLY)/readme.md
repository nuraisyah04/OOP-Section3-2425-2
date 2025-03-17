
# 📝 Instructions for Students - Folder Setup & Lab Submissions

## 📂 Step 1: Create Your Own Folder

1. **Navigate to the `StudentFile/` directory** in your project's root.
2. **Create a new folder** named with your **full name** or **student ID**.

   **Example:**
   ```
   StudentFile/JohnDoe/
   ```
   or
   ```
   StudentFile/A22CS1234/
   ```

   *Visual Example:*

   ![Folder Structure Example](https://via.placeholder.com/600x300?text=Folder+Structure+Example)

3. This will serve as your personal workspace for the entire semester.

---

## 📄 Step 2: Set Up Your Profile in `README.md`

1. Inside your personal folder (e.g., `StudentFile/JohnDoe/`), **create a file** named `README.md`.
2. In the `README.md` file, include the following profile details:

   ```markdown
   # Student Profile

   - **Full Name:** John Doe
   - **Student ID:** A22CS1234
   - **Course:** Object-Oriented Programming (SECJ2154)
   - **Email:** johndoe@example.com
   - **GitHub Username:** johndoe123

   ## About Me
   > Write a short introduction about yourself and your learning goals.
   ```

   *Visual Example:*

   ![README.md Example](https://via.placeholder.com/600x300?text=README.md+Example)

---

## 💻 Step 3: Lab Exercises Submission

1. For each lab exercise, **create a new subfolder** inside your personal folder.

   **Example for Lab 1:**
   ```
   StudentFile/JohnDoe/Lab1/
   ```

2. **Save all related files** (code, reports, etc.) inside the appropriate lab folder.

   *Visual Example:*

   ![Lab Folder Structure Example](https://via.placeholder.com/600x300?text=Lab+Folder+Structure+Example)

3. Maintain this structure for each subsequent lab:
   ```
   StudentFile/JohnDoe/Lab2/
   StudentFile/JohnDoe/Lab3/
   ...
   ```

---

## 🔄 Step 4: Push Your Work to GitHub

After completing a lab, **push your work** to GitHub within your personal folder.

### Workflow:

```bash
# Stage your changes
git add StudentFile/YourFolderName/

# Commit your changes
git commit -m "Add Lab X files"

# Push your changes
git push origin main
```

*Replace `YourFolderName` with your actual folder name.*

*Visual Example of Git Workflow:*

![Git Workflow Example](https://via.placeholder.com/600x300?text=Git+Workflow+Example)

---

## 🚦 Important Notes:

- **Do NOT modify** or submit work in another student's folder.
- Ensure your folder and file names are **clear** and **organized**.
- All lab submissions must reside **within your personal folder**.
- Keep your `README.md` **updated** if there are any profile changes.

---

✅ **Good Practice:** Commit and push your work after every lab to avoid missing submissions.

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

*Visual Example:*

![Final Structure Example](https://via.placeholder.com/600x300?text=Final+Structure+Example)

---

## 💡 Tip:

Use **meaningful commit messages** such as `"Completed Lab 3 with all required files"`.
