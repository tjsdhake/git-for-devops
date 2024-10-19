### 1. Initialize Git Repository
```bash
git init
Initializes a new Git repository in the current directory.

2. Add Text to a File
bash
Copy code
echo "Hi Bro How are you" >> gitfile.txt
Adds the text "Hi Bro How are you" to the file gitfile.txt.

3. List Files in Directory
bash
Copy code
ls -l
Lists files in the current directory with detailed information.

4. View File Contents
bash
Copy code
cat gitfile.txt
Displays the contents of the gitfile.txt file.

5. Show Hidden Files
bash
Copy code
ls -a
Lists all files, including hidden files, in the current directory.

6. Check Git Status
bash
Copy code
git status
Displays the status of the working directory and staging area.

7. Clear Terminal
bash
Copy code
clear
Clears the terminal screen.

8. Add File to Staging Area
bash
Copy code
git add nibbi.txt
Adds nibbi.txt to the staging area.

9. Create New File
bash
Copy code
touch nibba.txt
Creates a new, empty file called nibba.txt.

10. Remove File from Staging Area (Cached)
bash
Copy code
git rm --cached nibba.txt
Removes nibba.txt from the staging area without deleting the file.

11. Commit Changes with a Message
bash
Copy code
git commit -m "latest version"
Commits the changes in the staging area with the message "latest version".

12. Navigate to Parent Directory
bash
Copy code
cd ..
Changes directory to the parent directory.

13. Create New Directory and Enter It
bash
Copy code
mkdir git-test
cd git-test/
Creates a new directory called git-test and navigates into it.

14. Initialize Git in a New Directory
bash
Copy code
git init
Initializes a new Git repository in the git-test directory.

15. Add Specific File to Staging Area
bash
Copy code
git add test1.txt
Adds test1.txt to the staging area.

16. Commit Changes in the New Directory
bash
Copy code
git commit -m "new version or updated"
Commits the changes in the staging area with the message "new version or updated".

17. Delete a File
bash
Copy code
rm test1.txt
Removes the file test1.txt from the directory.

18. Restore a Deleted File
bash
Copy code
git restore test1.txt
Restores the deleted test1.txt from the last commit.

19. Display Commit History
bash
Copy code
git log
Displays the commit history of the repository.

20. Add All Files to Staging Area
bash
Copy code
git add ./
Adds all changes (including new, modified, or deleted files) in the current directory to the staging area.

21. Show Branch Information
bash
Copy code
git branch
Lists all branches in the repository.

22. Create and Switch to a New Branch
bash
Copy code
git branch dev
git checkout dev
Creates a new branch named dev and switches to it.

23. Commit with Specific Message to File
bash
Copy code
git commit -m "updatedd" devfile.txt
Commits devfile.txt with the message "updatedd".

24. Switch to Master Branch
bash
Copy code
git checkout master
Switches from the current branch to the master branch.

25. View Commit History in One Line
bash
Copy code
git log --oneline
Displays the commit history in a condensed one-line format.

26. Remove Numbered History Listing
bash
Copy code
history
Shows the list of recently executed commands.

bash
Copy code
history -c
