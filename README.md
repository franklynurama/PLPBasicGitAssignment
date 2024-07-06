
This is my first repository

# PLPBasicGitAssignment

## Repository Setup and Initialization

### Task 1: GitHub Repository Creation

1. **Log in to GitHub**:
   - Log in to your GitHub account.

2. **Create New Repository**:
   - Create a new repository named `PLPBasicGitAssignment`.
   - Initialize it with a README file.

### Task 2: Local Setup

1. **Create Local Folder**:
   - Create a new folder on your local machine named `PLPBasicGitAssignment`.
   - Open a terminal or command prompt and navigate to the created folder.

   ```bash
   mkdir PLPBasicGitAssignment
   cd PLPBasicGitAssignment

2. **Initialize Git Repository**:
   - Initialize a new Git repository in your local folder 

     ```bash
     git init

3. **Connect to GitHub Repository**:
   - Link your local repository to the GitHub repository.

    ```bash
     git remote add origin https://github.com/<your-username>/PLPBasicGitAssignment.git

### Task 3: Making Changes

1. **Create a File**:
   - Inside your local folder, create a new text file named `hello.txt`.
   - Add a simple text message ("Hello, Git!") to the file.

2. **Stage the Change**:
   - sStage the `hello.txt` file.

     ```bash
     git add hello.txt

3. **Commit the Changes**:
   - Commit the staged changes with a message.

    ```bash
     git commit -m "Add hello.txt with a greeting"

### Task 4: Pushing to GitHub

1. **Push to GitHub**:
   - Push the committed changes to the GitHub repository.

    ```bash
     git push -u origin main
   
### Task 5: Verify on GitHub

1. **Verify on GitHub**:
   - Visit your GitHub repository in a web browser.
   - Confirm that the `hello.txt` file and the commit message are visible.
