# Command History

## Project Setup

1. **Create a new directory for the project:**
    ```bash
    mkdir git-for-devops-new
    ```

2. **Navigate to the newly created directory:**
    ```bash
    cd git-for-devops-new/
    ```

3. **List contents to confirm creation:**
    ```bash
    ls
    ls -l
    pwd
    ```

## File Operations

4. **Create a text file with a message:**
    ```bash
    echo -e "Hi Bro how are you" > gitMasterfile.txt
    ls
    ```

5. **Create a second file:**
    ```bash
    touch gitmasterfile2
    ls
    ```

6. **Edit the content of the file (using Vim):**
    ```bash
    vim gitMasterfile.txt
    ```

7. **Delete and restore the file:**
    ```bash
    rm gitMasterfile.txt
    git restore gitMasterfile.txt
    cat gitMasterfile.txt
    ls
    ```

## Git Initialization

8. **Initialize Git repository:**
    ```bash
    git init
    ls -a
    ```

9. **Check the status of the repository:**
    ```bash
    git status
    ```

## Git Operations

10. **Stage the file for commit:**
    ```bash
    git add gitMasterfile.txt
    git status
    ```

11. **Commit the file with a message:**
    ```bash
    git commit -m "file updated" gitMasterfile.txt
    ```

12. **Check branches and logs:**
    ```bash
    git branch
    git log
    ```

13. **Switch between branches:**
    ```bash
    git checkout master
    git checkout dev
    ```

14. **Create and commit changes in the dev branch:**
    ```bash
    touch devfile.txt
    git add devfile.txt
    git commit -m "dev file updated" ./
    ```

15. **Check logs with different formats:**
    ```bash
    git log --oneline
    git log --twoline
    ```

## Cleanup

16. **Clear the terminal to improve readability:**
    ```bash
    clear
    ```

## Miscellaneous

17. **Navigate to different directories:**
    ```bash
    cd ..
    cd git-for-devops-new/
    ```
