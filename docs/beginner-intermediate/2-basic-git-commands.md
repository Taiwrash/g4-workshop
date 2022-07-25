## Basic Git Commands

>   In this module, we will learn about most used Git commands to get us basic knowledge to make our first contribution to source code.

### The Commands

1.  ```git help``` 
    This command list every possible commands that can be done along with different options that are availabe on Git.
    ```bash
        git help
    ```

2.  ```git help tutorial```
    This command opens a documentations about git commands and in-depth explanations of how they all work together.
    ```bash
        git help tutorial
    ```

3.  ```git help <command>```
    This command opens documentation for the single command passed in to it as an arguments.
    ```bash
        git help init
    ```

4.  ```git init```
    This command creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files
    ```bash
        git init
    ```

>   Pro tips: Ensure you are in the right directory/folder of your project before running this command.

5.  ```git status```
    This display the working tree status. It gives information about the changes and the state of the trackers.
    ```bash
        git status
    ```

6.  ```git add```
    This command adds file contents to the index(staging). This is the temporary addition of the contents into the staging environment.This command updates the index using the current content found in the working tree, to prepare the content staged for the next commit.
    a. Add everything in the directory
    ```bash
        git add .
    ```

    b. Add a single or multiple individual files
    ```bash
        git add file1 file2
    ```

    c.  To add all 
    ```bash
        git add -A
    ```

7.  ```git commit```
     This record changes permanently to the repository.
     ```bash
        git commit -m <message>
    ```
    























[<< Previous Module](/beginner-intermediate/1-intro-to-git.md)<========================================================>[Next Module >>](/beginner-intermediate/3-git-in-vscode.md)