## Basic Linux Commands

>   In this module, we will learn about seven (7) Linux commands to fast track Git learning curve. This is not compulsory but recommended mostly for Windows or other platforms users.

### What is Linux?

>   Linux (/ˈliːnʊks/ (listen) LEE-nuuks or /ˈlɪnʊks/ LIN-uuks)[11] is a family of open-source Unix-like operating systems based on the Linux kernel,[12] an operating system kernel first released on September 17, 1991, by Linus Torvalds. - [Wikipedia](https://en.wikipedia.org/wiki/Linux)

### Why Learning Linux?

>   Simple answer is, because of **Git Bash**. 

This is a tool is basically setup to perform all git actions. It is command line intermediate with little touch and integrations that empowers it to perform tasks beyond ordinary cmd prompts. It is popularly called **Bourne Again Shell (BASH)** which has Linux like attributes and accept most of the Linux commands.

### Linux Terminologies
-   Command
>   Commands are set of instructions that will pass into our computer to instruct and control it on what to do

-   Options
>   Linux command options are used to control the output of a Linux command. Some commands over 30 options. Options are always preceed with a dash (-) and are sometimes called **flags**

### Commands

In the field of **Human Computer Interactions**, there are different kinds of ways at which users interacts with machines especially computers for example form-fill-type, command line interface, graphical user interfaces and many others. The Linux BASH is mainly a command line interfaces family.

This implies,
>   We put commands into a prompt to carry out any tasks.

Below are some of the comamnds that are acceptable and used to carry out certain tasks in Linux.

1.  ```cd``` commands (change directory)
    -   To navigate through the Linux files and directories
    -   Some of the options allowed with cd commands ```~, .., -```

2.  ```mkdir``` commands (make directory)
    -   Use mkdir command to make a new directory — if you type mkdir Music it will create a directory called Music.

3.  ```touch``` commands (touch)
    -   The touch command allows you to create a blank new file through the Linux command line

4.  ```ls``` commands (list)
    -   The ls command is used to view the contents of a directory
    -   Some of the options allowed with ls commands ```-l, -al, -A, -R```

5.  ```cat``` commands (concatenate)
    -   Reads data or contents from file and gives their content as output. It helps us to create, view, concatenate files

6.  ```echo``` commands
    -   Used to display and write line of text/string that are passed as options

7.  ```diff``` commands (difference)
    -   Short for difference, the diff command compares the contents of two files line by line.

### Practice

1.  Let's move from one folder/directory to another

    a. Go to home directory  
    ```bash
        cd 
    ```

    b. Go to home directory
    ```bash
        cd ~
    ```
    c. Go to upper level of the current directory/folder
    ```bash
        cd ..
    ```

    d.  Go to a particular folder
    ```bash
        cd <folder-name>
    ```

2.  Let's create folders/directories
    a.  create a folder named <your-name-firstname>
    ```bash
        mkdir rasheed
    ```

    b. create a folder named <your-university-name>
    ```bash
        mkdir summit-university
    ```

3.  Let's see the content of a folder
    a. list folder contents
    ```bash
        ls
    ```

    b. list contents including hidden files
    ```bash
        ls -a
    ```

    c. list contents including file permissions
    ```bash
        ls -l
    ```

    d. list contents with permissions including hidden files
    ```bash
        ls -al
    ```

4.  Let's move into a folder named <your-firstname>
    ```bash
        cd rasheed
    ```
5. Let's create a file.
    a. create a file with a name <bio>
    ```bash
        touch bio.txt
    ```

6.  Writing to the empty file created
    a. Write **Congratulations <your-firstname>, you are almost done with this module !**
    ```bash
        echo "Congratulations Rasheed, you are almost done with this module !" > bio.txt
    ```

7. Reading the file
    ```bash
        cat bio.txt
    ```

### Exercises / TODOs

1.  Navigate to <your-university> folder created before
2.  Create a file with name <about-my-school.txt>
3.  Write a string of text about your institutions
4.  Outputs what you just written

>   Pro tips: If you get back what you wrote in step 3, congratulations you've completed the task but if no.Try again! 

[<< Previous Module](/beginner-intermediate/0-intro-to-git.md)<============================>[Next Module >>](/beginner-intermediate/2-basic-git-commands.md)

