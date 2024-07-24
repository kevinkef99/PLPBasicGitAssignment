# PLPBasicGitAssignment
Basic Git and GitHub workflow assignment.

This repository is created as part of the Basic Git and GitHub Workflow assignment. Below are the steps and commands used to set up and manage this repository.
Objective

To familiarize with the basic workflow of creating a GitHub repository, connecting it to a local folder, making commits, and pushing changes.
Steps Followed
1. Repository Setup on GitHub

    Log in to GitHub:
        Access your GitHub account at GitHub.

    Create a New Repository:
        Click on the + icon in the top right corner and select New repository.
        Enter PLPBasicGitAssignment as the repository name.
        Add a description: "Basic Git and GitHub workflow assignment" (optional).
        Check Add a README file to initialize the repository.
        Click Create repository.

2. Local Setup

    Create a Local Folder:
        Create a folder named PLPBasicGitAssignment on your local machine.

    Open Terminal/Command Prompt:
        Navigate to the folder using the terminal or command prompt:

        bash

    cd path/to/PLPBasicGitAssignment

Initialize a Git Repository Locally:

    Run the following command to initialize a new Git repository:

    bash

    git init

Connect Local Repository to GitHub:

    Add the GitHub repository as a remote origin:

    bash

        git remote add origin https://github.com/yourusername/PLPBasicGitAssignment.git

        Replace https://github.com/yourusername/PLPBasicGitAssignment.git with your repository's URL.

3. Making Changes

    Create a File:
        Inside the local folder, create a file named hello.txt.
        Add the following text to the file:

    Hello, Git!

    Save and close the file.

Stage the Changes:

    Add hello.txt to the staging area:

    bash

    git add hello.txt

Commit the Changes:

    Commit the changes with a message:

    bash

        git commit -m "Add hello.txt with a greeting"

4. Pushing to GitHub

    Push the Changes:
        Push the committed changes to the GitHub repository:

        bash

        git push -u origin main

        If your branch is named master, replace main with master.

5. Verification

    Verify on GitHub:
        Go to your GitHub repository page.
        Check that hello.txt is visible and that the commit message "Add hello.txt with a greeting" appears in the commit history.

Additional Information

    Documentation: The README file in this repository documents the steps taken during the assignment.
    Troubleshooting: For any issues, refer to the GitHub Documentation or seek assistance from peers or the instructor.

License

This repository is for educational purposes only.

Feel free to adjust the content according to your needs or any specific requirements from your instructor. Once you have this information ready, save it in a README.md file in your local repository, and push it to GitHub:

bash

git add README.md
git commit -m "Add README with documentation of Git and GitHub workflow"
git push -u origin main

This will ensure that your README file is up-to-date and provides a clear record of your work.
