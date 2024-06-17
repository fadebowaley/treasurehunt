# GitHub Beginner Exercises for Treasure Hunt

## Introduction

Welcome to the GitHub Treasure Hunt exercise! You will be working in teams to complete a series of tasks using GitHub. Each team will submit their exercise on a separate branch. The teams are:

- Team Alpha
- Team Beta
- Team Charlie
- Team Delta

Each team should create a branch named after their team (e.g., `team-alpha`, `team-beta`, etc.) and submit their changes on that branch.

## Project 1: Initializing a Repository for a Treasure Hunt

### Scenario:
You have discovered a mysterious old map that leads to hidden treasures. To keep your findings organized and share them with your fellow adventurers, you need to create a GitHub repository.

### Challenge:
1. Clone the treasure hunt repository.
2. Create a README file with a brief description of the treasure hunt.
3. Commit the README file.
4. Push the changes to GitHub on your team's branch.

### Hint:
```
1. Clone the repository:
   ```bash
   git clone https://github.com/fadebowaley/treasurehunt.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd treasurehunt
   ```
3. Create a branch named after your team (replace `<team-name>` with your team's name, e.g., `team-alpha`):
   ```bash
   git checkout -b <team-name>
   ```
4. Create a README file:
   ```bash
   echo "# Treasure Hunt" > README.md
   ```
5. Add the README file to staging:
   ```bash
   git add README.md
   ```
6. Commit the file:
   ```bash
   git commit -m "Initial commit with README"
   ```
7. Push the changes to GitHub on your team's branch:
   ```bash
   git push origin <team-name>
   ```
```

## Project 2: Collaborating on a Secret Code

### Scenario:
You and your friends have discovered ancient runes and need to decode them together. To do this efficiently, you must collaborate on GitHub.

### Challenge:
1. Fork the treasure hunt repository.
2. Create a new branch for your contributions.
3. Make changes to the decoding guide.
4. Commit your changes.
5. Push the branch to GitHub.
6. Create a pull request for review.

### Hint:
```
1. Fork the repository by clicking on the "Fork" button on GitHub.
2. Clone the forked repository (replace `<your-username>` with your GitHub username):
   ```bash
   git clone https://github.com/<your-username>/treasurehunt.git
   ```
3. Navigate to the repository directory:
   ```bash
   cd treasurehunt
   ```
4. Create a new branch:
   ```bash
   git checkout -b decode-runes
   ```
5. Make changes to the guide (edit files as needed).
6. Stage the changes:
   ```bash
   git add <modified-files>
   ```
7. Commit the changes:
   ```bash
   git commit -m "Added decoding methods for new runes"
   ```
8. Push the branch to GitHub:
   ```bash
   git push origin decode-runes
   ```
9. Create a pull request:
   - Go to your forked repository on GitHub.
   - Click on "Pull Requests" and then "New Pull Request".
   - Select your branch and create the pull request.
```

## Project 3: Tracking Changes in Ancient Manuscripts

### Scenario:
While researching, you and your team have found several versions of an ancient manuscript. You need to track changes and maintain a history of all versions.

### Challenge:
1. Add multiple versions of the manuscript to the repository.
2. Commit each version with a relevant message.
3. View the history of changes.

### Hint:
```
1. Add the first version:
   ```bash
   echo "Ancient Manuscript - Version 1" > manuscript.txt
   git add manuscript.txt
   git commit -m "Added version 1 of the manuscript"
   ```
2. Add the second version:
   ```bash
   echo "Ancient Manuscript - Version 2" > manuscript.txt
   git add manuscript.txt
   git commit -m "Updated to version 2 of the manuscript"
   ```
3. Add the third version:
   ```bash
   echo "Ancient Manuscript - Version 3" > manuscript.txt
   git add manuscript.txt
   git commit -m "Updated to version 3 of the manuscript"
   ```
4. View the commit history:
   ```bash
   git log
   ```
```

## Project 4: Resolving Conflicts in Expedition Notes

### Scenario:
You and a fellow explorer have made different updates to the same expedition notes. Now, you need to merge these updates and resolve any conflicts.

### Challenge:
1. Fetch the latest changes from the remote repository.
2. Merge the updates into your local branch.
3. Resolve any conflicts that arise.
4. Commit the resolved changes.
5. Push the final version to GitHub on your team's branch.

### Hint:
```
1. Fetch the latest changes:
   ```bash
   git fetch
   ```
2. Merge the updates (assuming you are merging `main` branch):
   ```bash
   git merge origin/main
   ```
3. Resolve conflicts:
   - Open the conflicted files in your text editor.
   - Look for conflict markers (<<<<<<<, =======, >>>>>>>) and resolve them.
   - Save the files after resolving conflicts.
4. Stage the resolved files:
   ```bash
   git add <resolved-files>
   ```
5. Commit the resolved changes:
   ```bash
   git commit -m "Resolved merge conflicts in expedition notes"
   ```
6. Push the final version to GitHub on your team's branch:
   ```bash
   git push origin <team-name>
   ```
```

## Project 5: Reverting Changes in Artifact Documentation

### Scenario:
You have documented a newly found artifact, but some details were incorrect. You need to revert to a previous version of the documentation.

### Challenge:
1. Identify the commit with the correct documentation.
2. Revert to that commit.
3. Push the changes to GitHub on your team's branch.

### Hint:
```
1. View the commit history to find the correct commit:
   ```bash
   git log
   ```
2. Revert to the specific commit (replace `<commit-hash>` with the actual commit hash):
   ```bash
   git revert <commit-hash>
   ```
3. Push the changes to GitHub on your team's branch:
   ```bash
   git push origin <team-name>
   ```
```

---

These exercises will provide you with practical experience using GitHub and help you develop a solid understanding of fundamental GitHub commands and workflows.
