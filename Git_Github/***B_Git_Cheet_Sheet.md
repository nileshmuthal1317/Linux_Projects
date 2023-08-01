Sure! Here's the Git and GitHub cheat sheet formatted in Markdown:

# Git Cheat Sheet

1. **Setting Up Git:**
   ```
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   ```

2. **Creating Repositories:**
   ```sh
   git init                      # Initialize a new Git repository locally
   git clone <repository URL>    # Clone an existing repository from a remote URL
   ```

3. **Basic Workflow:**
   ```sh
   git status                    # Check the status of your working directory
   git add <file>                # Stage changes for the next commit
   git commit -m "Your message"  # Commit staged changes with a descriptive message
   git pull                      # Fetch and merge changes from the remote repository
   git push                      # Push your local commits to the remote repository
   ```

4. **Branching and Merging:**
   ```sh
   git branch                    # List all branches, with * next to the current branch
   git branch <branchname>       # Create a new branch
   git checkout <branchname>     # Switch to a different branch
   git merge <branchname>        # Merge the specified branch into the current branch
   ```

5. **Updating and Undoing:**
   ```sh
   git pull                      # Fetch and merge changes from the remote repository
   git fetch                     # Fetch changes without merging
   git reset --hard HEAD         # Discard all local changes and revert to the last commit
   git revert <commit-hash>      # Create a new commit that undoes the changes of a specific commit
   ```

6. **Viewing History and Diffs:**
   ```sh
   git log                       # Show commit history
   git log --oneline             # Show commit history in one-line format
   git diff                      # Show changes between working directory and staging area
   git diff --cached             # Show changes between staging area and last commit
   git show <commit-hash>        # Show details of a specific commit
   ```

# GitHub Cheat Sheet

1. **Working with Remote Repositories:**
   ```sh
   git remote -v                 # List all remote repositories and their URLs
   git remote add origin <URL>   # Add a remote repository named 'origin'
   git push -u origin <branch>   # Push the branch to the 'origin' remote repository
   git pull origin <branch>      # Pull changes from the 'origin' remote repository
   ```

2. **Forking and Pull Requests:**
   - Fork a repository: Click the 'Fork' button on GitHub.
   - Clone your fork: `git clone <fork-url>`
   - Create a new branch for your feature: `git checkout -b feature-branch`
   - Make changes, commit, and push to your fork.
   - Create a pull request from your fork's branch on GitHub.

3. **Managing Issues:**
   - Create an issue: Go to the repository > Issues > New Issue.
   - Referencing issues: Use keywords like "Fixes #issue_number" in your commit messages.

4. **Collaborating with Others:**
   - Add collaborators: Go to the repository > Settings > Manage access.
   - Review pull requests: Go to the repository > Pull requests > Review changes.

5. **Using Git Ignore:**
   - Create a `.gitignore` file in the root directory to exclude certain files from version control.

6. **GitHub Pages:**
   - Host a static website from a repository by enabling GitHub Pages in the repository settings.

Remember, this is just a brief overview. Git and GitHub are powerful tools, and there's much more to learn. It's always a good idea to refer to the official documentation for more detailed information. Happy coding!
```

You can copy and paste this Markdown code into a Markdown file (e.g., `git_github_cheatsheet.md`) and then commit and push it to your GitHub repository. It will be displayed nicely as documentation on GitHub.
