## Git

>   In this module, we will explore the fundamentals of Version Control Systems (VCS), with a focus on Git. We’ll dive into the problems Git solves and the essential concepts to help you effectively learn and use it. Additionally, we will guide you through setting up Git on various operating systems, including macOS, Linux, and Windows, ensuring you’re ready to start managing your projects with ease.

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
