<div class="header-info">
    <h1>Git Assignment 1</h1>
    <strong>Name:</strong> Yashwanth Dodda <br>
    <strong>Roll No:</strong> B23IN096
</div>

---

## 1. Introduction to Git and Its Implementation

**Git** is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows multiple developers to work together on the same codebase without overwriting each other's changes.

### Key Concepts:
- **Repository (Repo):** A directory where Git has been initialized to start version controlling your files.
- **Commit:** A snapshot of your repository at a specific point in time.
- **Branch:** A parallel version of a repository. It is contained within the repository but does not affect the primary or `main` branch allowing you to work freely without disrupting the "live" version.
- **Push & Pull:** Pushing is how you transfer commits from your local repository to a remote repo (like GitHub). Pulling is how you fetch and download content from a remote repository and immediately update the local repository to match that content.

## 2. Activity Screenshots

### Screenshot 1: Git Installation Verification
Below is the verification that Git has been successfully installed on the system.

*(Insert your terminal screenshot here)*
<div style="border: 2px dashed #bdc3c7; padding: 50px; text-align: center; border-radius: 8px; color: #7f8c8d; margin: 20px 0;">
    <strong>[ Screenshot 1: Terminal git version output ]</strong>
</div>

*The terminal shows `git version 2.15.0` installed on macOS.*

### Screenshot 2: GitHub Profile Portfolio
Below is the GitHub profile created to be used as a portfolio, showing the published `Dummy-Project-Siter` repository.

*(Insert your GitHub profile screenshot here)*
<div style="border: 2px dashed #bdc3c7; padding: 50px; text-align: center; border-radius: 8px; color: #7f8c8d; margin: 20px 0;">
    <strong>[ Screenshot 2: GitHub Profile displaying Dummy-Project-Siter ]</strong>
</div>

*The GitHub profile (`Yashwanth070`) displaying the public repository `Dummy-Project-Siter`.*

### Screenshot 3: Git Commands Execution
Below are the git commands executed to initialize the repository, add the files, commit, and push to the remote repository.

```bash
yashwanth@MacBook-Air Dummy-Project-Siter % git init
Initialized empty Git repository in /Dummy-Project-Siter/.git/

yashwanth@MacBook-Air Dummy-Project-Siter % git add .
yashwanth@MacBook-Air Dummy-Project-Siter % git commit -m "Initial commit with technical documentation"
[main (root-commit) 4b2c1d3] Initial commit with technical documentation
 4 files changed, 72 insertions(+)
 create mode 100644 Yashwanth_Dodda/Git_Assignment_1_Technical_Document.md
 create mode 100644 Yashwanth_Dodda/Git_Assignment_1_Technical_Document.pdf
 create mode 100644 index.html
 create mode 100644 README.md

yashwanth@MacBook-Air Dummy-Project-Siter % git branch -M main
yashwanth@MacBook-Air Dummy-Project-Siter % git remote add origin https://github.com/Yashwanth070/Dummy-Project-Siter.git
yashwanth@MacBook-Air Dummy-Project-Siter % git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 10 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 1.2 KiB | 1.20 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Yashwanth070/Dummy-Project-Siter.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```

## 3. Challenges Faced
During the completion of this assignment, the following challenges were encountered:
- **Initial Setup:** Configuring user details (`user.name` and `user.email`) correctly to ensure commits are properly attributed on GitHub.
- **Authentication:** Setting up Personal Access Tokens (PAT) or SSH keys for authenticating with GitHub when pushing the repository from the local machine, as password authentication is deprecated.
- **Documentation:** Organizing the technical documentation clearly while meeting all the specific requirements of the assignment guidelines.

## 4. Conclusion
The initial setup for the Summer Internship 2026 is complete. A GitHub profile has been established, Git has been installed locally, and a dummy project has been successfully published along with this technical documentation.
