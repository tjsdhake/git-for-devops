Step 1: Initialize a Git Repository
bash
Copy code
git init
This command initializes a new Git repository in your current directory. After running this, Git starts tracking changes in your project.
Step 2: Create a File and Add Content
bash
Copy code
echo "Hi Bro How are you" >> gitfile.txt
This command creates (or appends) the text “Hi Bro How are you” to a file called gitfile.txt.
bash
Copy code
ls -l
cat gitfile.txt
Use ls -l to list the files and cat to display the contents of gitfile.txt.
Step 3: Check the Status of Your Repository
bash
Copy code
git status
This command shows the current status of your working directory and staging area, indicating which files are tracked, untracked, or modified.
Step 4: Stage Changes for Commit
bash
Copy code
git add nibbi.txt
This command stages the file nibbi.txt for commit, meaning Git will include it in the next snapshot (commit).
Step 5: Create New Files
bash
Copy code
touch nibbi.txt nibba.txt
The touch command creates empty files named nibbi.txt and nibba.txt.
Step 6: Add and Remove Files from the Staging Area
bash
Copy code
git add nibba.txt
git rm --cached nibba.txt
git add stages the file, and git rm --cached removes it from the staging area without deleting the file itself from your working directory.
Step 7: Commit Changes
bash
Copy code
git commit -m "latest version"
This creates a snapshot of the staged changes, with the commit message "latest version". Commits in Git represent the project at a certain state.
Step 8: Create a New Directory
bash
Copy code
mkdir git-test
cd git-test
This creates a new directory called git-test and moves into it.
Step 9: Initialize a New Git Repository
bash
Copy code
git init
You initialize another Git repository in this new directory.
Step 10: Create and Track New Files
bash
Copy code
touch test1.txt test2.txt
git add test1.txt
The touch command creates test1.txt and test2.txt, and git add stages test1.txt for tracking.
Step 11: Commit Changes
bash
Copy code
git commit -m "new version or updated"
Commits the staged changes with the message "new version or updated".
Step 12: Modify, Remove, and Restore Files
bash
Copy code
rm test1.txt
git restore test1.txt
Removes test1.txt from the working directory and then restores it using git restore.
Step 13: Add All Changes to Staging
bash
Copy code
git add ./
This command stages all changes (new, modified, or deleted files) in the current directory for commit.
Step 14: Commit All Staged Changes
bash
Copy code
git commit -m "updated"
This commits all the changes with the message "updated".
Step 15: Create and Switch Between Branches
bash
Copy code
git branch dev
git checkout dev
git branch dev creates a new branch called dev, and git checkout dev switches to that branch.
Step 16: Add New Changes in the dev Branch
bash
Copy code
echo "hi bro" >> devfile.txt
git add devfile.txt
git commit -m "updatedd"
Appends text to devfile.txt, stages the file, and commits it with the message "updatedd".
Step 17: Switch Back to the master Branch
bash
Copy code
git checkout master
This switches you back to the master branch.
Step 18: View the Commit History
bash
Copy code
git log
This command shows the full commit history for the repository.
bash
Copy code
git log --oneline
This displays a more concise, one-line-per-commit view of the log.
Step 19: View the Branches
bash
Copy code
git branch
Shows a list of branches in your repository and indicates which one you’re currently on.
General Workflow Summary:
Initialize a Repository: git init to create a Git repository.
Track Files: Create or modify files and use git add <filename> to stage them.
Check Status: Use git status to see what’s staged, modified, or untracked.
Commit Changes: git commit -m "message" to create a snapshot.
Branching: Use git branch <branch-name> to create a branch and git checkout <branch-name> to switch between them.
History: View commit history with git log.
Restore Files: Use git restore <file> to recover deleted or modified files.
