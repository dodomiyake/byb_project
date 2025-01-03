# Part 2 - Practical Task 1: Repository Setup and Git Basics

This README provides a step-by-step guide for Part 2: Practical Task 1. Follow these instructions to create and manage a GitHub repository, write a simple program, and perform essential Git operations.

---

## Steps to Complete the Task

### 1. Log in to GitHub
- Use the GitHub account you created.


---

### 2. Create a New Repository
1. On GitHub, click the **New** button.
2. Name the repository `byb_project`.
3. Set the repository visibility to **Public**.

---

### 3. Set Up a Local Repository
1. Create an empty folder named `byb_project` on your local machine.
2. Open a terminal or command prompt and navigate to the folder:
   ```bash
   cd path/to/byb_project
3. Initialize a Git repository:
   ```bash
   git init

---

### 4. Create a "Hello World" Program
1. Inside the byb_project folder, create a file named:
   ```bash
   touch helloWorld.js
2. Write the following code in the file created:
   ```bash
   console.log("Hello, World!")

---

### 5. Check and Stage Your File
1. Verify the file is untracked:
   ```bash
   git status
- The file should appear as untracked.
  
2. Stage the file for commit:
   ```bash
   git add helloWorld.js
3. Commit the file
   ```bash
   git commit -m "Added Hello World program"

---

### 6. Modify and Track Changes
1. Update the file to print:
   ```bash
   console.log("Git is Awesome!");
2. Verify the file is modified but unstaged:
   ```bash
   git status
3. Stage the updated file:
   ```bash
   git add helloWorld.js
4. Commit the changes:
   ```bash
   git commit -m "Modified the message printed"

---

### 7. Push to GitHub
1. Add the remote repository:
   ```bash
   git remote add origin https://github.com/YourUsername/byb_project.git
2. Push the repository:
   ```bash
   git push -u origin master

---

### 8. Share and Submit the Repository
1. Copy the public URL of the repository.
2. Add the URL to your Google Answers document under the section for Part 2: Practical Task 1.


