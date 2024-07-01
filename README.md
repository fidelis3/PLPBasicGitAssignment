# PLPBasicGitAssignment
## Introduction
This repository is a basic introduction to the Git and GitHub workflow. It covers the steps for creating a GitHub repository, setting up a local repository, making changes, committing those changes, and pushing them to GitHub.

## Task Overview

### Task 1: Repository Setup
1. **GitHub Repository Creation:**
   - Log in to your GitHub account.
   - Create a new repository named "PLPBasicGitAssignment".
   - Initialize it with a README file.

### Task 2: Local Setup
2. **Local Folder Setup:**
   - Create a new folder on your local machine named "PLPBasicGitAssignment".
   - Open a terminal or command prompt and navigate to the created folder.

3. **Git Initialization:**
   - Initialize a new Git repository in your local folder using the command:
     ```bash
     git init
     ```

4. **Connecting to GitHub:**
   - Link your local repository to the GitHub repository using the command:
     ```bash
     git remote add origin <repository-url>
     ```
     Replace `<repository-url>` with the actual URL of your GitHub repository.

### Task 3: Making Changes
5. **Create a File:**
   - Inside your local folder, create a new text file named `hello.txt`.
   - Add a simple text message, for example, "Hello, Git!".

6. **Committing Changes:**
   - Stage the changes using the command:
     ```bash
     git add hello.txt
     ```
   - Commit the changes using the command:
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

### Task 4: Pushing to GitHub
7. **Pushing to GitHub:**
   - Push the committed changes to your GitHub repository using the command:
     ```bash
     git push -u origin main
     ```

### Task 5: Verification
8. **Verify on GitHub:**
   - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

