# Repository Overview

This repository is designed as a template for managing version control tasks efficiently.
It includes instructions for setting up a repository, creating feature branches, and merging changes. 
This readme was created using ChatGPT.

---
CHANGES FOR PRACTICAL IN BRANCH "featureBranch3" IN "ReadMe.md"
---
CHANGES FOR PRACTICAL IN BRANCH "featureBranch2" IN "ReadMe.md"
---
CHANGES MADE TO "ReadMe.md" FOR PRACTICAL IN BRANCH "master".
ADDITIONAL CHANGES MADE TO "ReadMe.md" FOR PRACTICAL IN BRANCH "master".
---
CHANGES MADE FOR PRACTICAL IN "featureBranch1".
ADDITIONAL CHANGES MADE FOR PRACTICAL IN "featureBranch1".
---

## Tasks

### 1. Initialise the Repository
- Use `git init` to initialise the repository.
- Create a `.gitignore` file to exclude unnecessary files and directories.
- Stage and commit the initial changes using `git add` and `git commit`.

### 2. Update the `README.md` File
- Modify the `README.md` file to include relevant information about the project.
- Add a brief description, project purpose, and tasks.
- Stage and commit the updated `README.md` file.

### 3. Create `featureBranch1`
- Use `git branch featureBranch1` to create a new branch.
- Switch to the new branch using `git checkout featureBranch1` or `git switch featureBranch1`.
- Make the necessary updates or changes on this branch.
- Stage, commit, and push the changes.

### 4. Create `featureBranch2`
- Use `git branch featureBranch2` to create another branch.
- Switch to the branch using `git checkout featureBranch2` or `git switch featureBranch2`.
- Make changes specific to this feature.
- Stage, commit, and push the updates.

### 5. Merge Changes
- Switch back to the `main` branch using `git checkout main` or `git switch main`.
- Merge `featureBranch1` into `main` using `git merge featureBranch1`.
- Resolve any merge conflicts if necessary.
- Repeat the process to merge `featureBranch2` into `main`.
- Push the merged changes to the remote repository.

---

## Additional Notes
- Always pull the latest changes from the remote repository before starting a new task: `git pull origin main`.
- Use descriptive commit messages to document the changes.
- Regularly push your changes to avoid conflicts.

### Example Commands
```
# Initialise Repository
git init

# Create and Switch to Feature Branch
git branch featureBranch1
git switch featureBranch1

# Merge Feature Branch
git switch main
git merge featureBranch1

# Push Changes
git push origin main
```

By following these steps, you can manage your repository efficiently and maintain a clean version control history.
