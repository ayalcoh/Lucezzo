# GitHub Guide for Team Collaboration

## Why Use GitHub?
GitHub is a powerful platform for managing code, tracking changes, and collaborating on software development. Here’s why it’s beneficial for our team:

- **Version Control:** Keeps track of all changes made to the code, allowing us to revert to previous versions if needed.
- **Collaboration:** Multiple developers can work on the same project without conflicts.
- **Code Reviews:** Improves code quality by allowing teammates to review each other’s work.
- **Issue Tracking:** Helps us keep track of bugs, tasks, and feature requests.
- **Backup & Security:** Ensures our code is safely stored and accessible from anywhere.

## Setting Up GitHub

### Step 1: Create a GitHub Account
1. Visit [GitHub](https://github.com/).
2. Click on **Sign up** and follow the instructions.
3. Choose a username, enter an email, and set a password.
4. Verify your email and log in.

### Step 2: Install Git
Git is the version control system that powers GitHub. Install it by following these steps:
1. Download Git from [Git Downloads](https://git-scm.com/downloads).
2. Run the installer and follow the default setup.
3. Verify the installation by running:
   ```sh
   git --version
   ```
   in the command line.

### Step 3: Configure Git
Run the following commands to set up your Git identity:
```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## Joining the Repository
1. I will invite you to the GitHub repository.
2. Accept the invitation via email or in your GitHub dashboard.
3. Clone the repository to your local machine using:
   ```sh
   git clone https://github.com/your-repo-name.git
   ```
4. Navigate into the project folder:
   ```sh
   cd your-repo-name
   ```

## Basic Git Commands
- **Check repository status:**
  ```sh
  git status
  ```
- **Pull the latest changes:**
  ```sh
  git pull origin main
  ```
- **Create a new branch:**
  ```sh
  git checkout -b feature-branch-name
  ```
- **Add changes to commit:**
  ```sh
  git add .
  ```
- **Commit your changes:**
  ```sh
  git commit -m "Your commit message"
  ```
- **Push changes to GitHub:**
  ```sh
  git push origin feature-branch-name
  ```
- **Create a Pull Request (PR):**
  - Go to the repository on GitHub.
  - Click **Pull Requests** → **New Pull Request**.
  - Select your branch and compare it with the `main` branch.
  - Click **Create Pull Request** and add a description.
  - Wait for review before merging.

## Best Practices
- Always **pull the latest changes** before starting new work.
- Work in **separate branches** for different features or fixes.
- Write **clear commit messages** describing your changes.
- Use **Pull Requests** to merge code only after a review.
- Communicate with the team in GitHub issues or discussions.

## Troubleshooting
- If you face access issues, ensure you’ve accepted the repository invitation.
- If there’s a merge conflict, resolve it locally before pushing changes.
- Use `git help` or visit the [GitHub Docs](https://docs.github.com/) for more guidance.

By following this guide, we can collaborate effectively and maintain a well-organized codebase. Welcome to GitHub, and happy coding!

