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

4.  ```git-config``` 
    This is to get and set repository or global options
    ```bash
        git config
    ```
>   Quick notice: This requires the options like (--local, --global)

5.  ```git init```
    This command creates an empty Git repository - basically a .git directory with subdirectories for objects, refs/heads, refs/tags, and template files
    ```bash
        git init
    ```

>   Quick notice: Ensure you are in the right directory/folder of your project before running this command.

6.  ```git status```
    This display the working tree status. It gives information about the changes and the state of the trackers.
    ```bash
        git status
    ```

7.  ```git add```
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

8.  ```git commit```
     This record changes permanently to the repository.
     ```bash
        git commit -m <message>
    ```

9.  ```git log```
    This is show commit logs. List commits that are reachable by following the parent links from the given commit(s), but exclude commits that are reachable from the one(s) given with a ^ in front of them. The output is given in reverse chronological order by default.
    ```bash
        git log
    ```

10.  ```git push```
    This is to  update remote refs along with associated objects. It is updates remote refs using local refs, while sending objects necessary to complete the given refs.
    ```bash
        git push
    ```

11. ```git remote```
    This manage set of tracked repositories. Manage the set of repositories ("remotes") whose branches you track. With no arguments, shows a list of existing remotes. Several subcommands are available to perform operations on the remotes.
    ```bash
        git remote
    ```
    
> Important Options: |-
    ``git remote add`` [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=(fetch|push)] <name> <url> |-
    ``git remote rename`` <old> <new> |-
    ``git remote remove`` <name>

12. ```git  clone```
    This clones a repository into a newly created directory, creates remote-tracking branches for each branch in the cloned repository (visible using git branch --remotes), and creates and checks out an initial branch that is forked from the cloned repository’s currently active branch.
    ```bash
        git clone
    ```

13. ```git branch```
    This is to list, create, or delete branches

    ```bash
        git branch
    ```

14. ```git checkout```
    This is to switch branches or restore working tree files
    ```bash
        git checkout
    ```
> Pro tips: the branch as option

15. ```git merge```
    This is used to  join two or more development histories/branches together. Incorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch. This command is used by git pull to incorporate changes from another repository and can be used by hand to merge changes from one branch into another.
    ```bash
        git merge
    ```

> Pro tips: ```.gitignore``` is a file that contain what is mearnt to not be tracking by git


### Exercise

-   Move into the University folder created in previous module
-   Initialize a git a repository
-   Open <about-my-school.txt> file and added 5 things about your school and save
-   Add the  file to index
-   Make a final commit

[<< Previous Module](/beginner-intermediate/1-intro-to-git.md)<========================================================>[Next Module >>](/beginner-intermediate/3-git-in-vscode.md)