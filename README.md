 Assignment Q#1
 ==============

 # Git & GitHub Assignment

## Commands Used

### 1. Initialize Git Repository
```bash
git init

Creates a new local Git repository in the current folder.

2. Check Repository Status
git status

Shows the current status of files, branches, and changes.

3. Add Files to Staging Area
git add .

Adds all files and changes to the staging area for commit.

4. Commit Changes
git commit -m "First Github Assignment"

Saves the staged changes with a commit message.

5. Add Remote Repository
git remote add origin https://github.com/goudsanjeev794/Git_GitHub_SanjeevAssignment.git

Connects the local repository to the GitHub remote repository.

6. Push Code to Master Branch (Successful)
git push origin master

Successfully pushed the local master branch to GitHub.

<img width="1044" height="519" alt="image" src="https://github.com/user-attachments/assets/4a714a58-a3db-4fb8-bc9b-f825077bd6c6" />

<img width="683" height="220" alt="image" src="https://github.com/user-attachments/assets/95ab0dae-fb8f-4e3e-8769-2ce66d8be1e7" />

Assignment Q#2
================
# Additional Git Commands Used

## 1. Add Changes to Staging Area
```bash
git add .

Adds all modified and new files to the staging area.

2. Commit Changes
git commit -m "Second Github Assignment"

Creates a new commit with the message "Second Github Assignment".

3. Add More Changes to Staging Area
git add .

Stages the latest file changes again.

4. Commit New Changes
git commit -m "Second Github Assignment- new addition"

Creates another commit with updated changes.

5. View Detailed Commit History
git log

Displays complete commit history including:

Commit ID
Author
Date
Commit message
6. View Short Commit History
git log --oneline

Displays a simplified one-line version of the commit history.

Example Output:

f0f0001 Second Github Assignment- new addition
5ecaaec Second Github Assignment
36f245c First Github Assignment

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/1d221014-e8cb-4131-b872-e861c3fab0bc" />


Assignment Q#3
================

## Git Branching Commands Used

### 1. Check existing branches
```bash
git branch

Displays all local branches in the repository.
The * symbol shows the currently active branch.

2. Create and switch to a new branch
git checkout -b feature-update

Creates a new branch named feature-update and switches to it immediately.

3. Stage all changes
git add .

Adds all modified and new files to the staging area.

4. Commit changes
git commit -m "Third Github Assignment - branching"

Saves the staged changes with a commit message.

5. Switch back to master branch
git checkout master

Moves from the current branch to the master branch.

6. Merge feature branch into master
git merge feature-update

Merges changes from the feature-update branch into the master branch.

7. Delete merged branch
git branch -d feature-update

Deletes the branch safely after it has been merged.

8. Create another branch
git checkout -b dummy-branch

Creates and switches to a new branch named dummy-branch.

9. Force delete branch
git branch -D dummy-branch

Force deletes the branch even if it has not been merged.

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/dcdc0405-5044-4ab6-806c-2d265b734538" />
<img width="940" height="200" alt="image" src="https://github.com/user-attachments/assets/1688766a-5d47-4fe8-97e9-24992832958d" />





