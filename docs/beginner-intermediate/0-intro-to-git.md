## Git

>   In this module, we will learn a little bit about version control system (VCS) - Git, the problem its solved and the necessary things to aid our learning and usage. We will talk about how to set it up on a local machine be it MacOS, Linux or Windows.

###   What is Git? 

>   It is a free and open source softwares that helps developers tracks and manages changes in a particular files and purposely to manage collaborative development especially during **software development**.

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. - [Git Website](https://git-scm.com/)

![Branch Tree](./vscode-pack/branch.png)

### What is version control system

>   This is also called source control system (SCS). It is a system that is responsible for managing and tracking changes in computer programs, files and documents.

### Git Installation 🌄

-   Step 1: Download git that is compatible with your operating system from the [Git Website](https://git-scm.com/)

-   Step 2: Follow the installation prompts to complete the installation

-   Step 3: Configure your machine
-   
    -   To configure username  
    ```bash
        git config --global user.username <your-github-username>
    ```
    -   To configure full name
    ```bash
        git config --global user.name <your-github-name>
    ```
    -   To configure email
    ```bash
        git config --global user.email <your-github-email>
    ```
> Pro tips: Why ``--global``? For writing options: write to global ~/.gitconfig file rather than the repository .git/config, write to

-   Step 4: By now, your machine will be up and running to communicate with Git and GitHub.


[Next Module >>](1-basic-linux-commands.md)
