# Getting started

## Installing Git

### Linux Installation

- You can install Git on Linux Ubuntu and Debian by running:

    ```bash
    sudo apt install git
    ```
***This for Ubuntu and Debian distribution and will not work for other distribution.***

- After installation, verify Git by running:

    ```bash
    git --version
    ```

### macOS installation

- You can install Git on macOS by running:

    ```bash
    brew install git
    ```

- After installation, verify Git by running:

    ```bash
    git --version
    ```

## Basic Configuration

### 1. Configure Username and Email

- Set your Git username and email using the following commands:

    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

### 2. Configure Default Branch

- By default, Git uses the term "master" for the main branch. However, there's a move towards more inclusive language, and some repositories may use "main" instead. You can configure Git to use "main" as the default branch globally with:

    ```bash
    git config --global init.defaultBranch main
    ```

- This ensures that every time you initialize a new repository, it will default to creating a "main" branch instead of "master."

## Repository

A repository, often abbreviated as `repo` is a project's folder that contains all the files and the entire history of changes made to those files.
### Initializing a Git Repository

- To initialize a directory, run:

    ```bash
    git init
    ```

- To link your local repo to remote repo, use `git remote add` command.
- Using `git push` to upload local changes to a remote repository.
- Using `git pull` to fetch changes from a remote repository.
- This will create a `.git` subdirectory in the project directory that stores all the version control information.
- You can also clone a remote repo repo with `git clone command`. e.g, 

    ```bash
    git clone linkToTheRepo
    ```

- If you have some files or directories that you don't want to track their changes, you can `.gitignore` file and put their name inside the file.
- Use `git add` to stage changes for commit.
- A commit is a set of changes made in a repo. To commit changes, use `git commit` command.

### Branches

- Branches are divergent lines of development within a repo.
- The default branch of a repo is the `main` branch.
- Branches allow you to separate your work from the main branch.
- They allow developers to work on separate features, bug fixes, or experiments without directly impacting the main or other branches until changes are ready to be merged.

- Changes in one branch does not affect the other until they're merged.

- To create a branch, use `git branch` command.
- **For example,** creating a branch for a new feature:

    ```bash
    git branch new-feature
    ```

- You can switch between multiple branches using `git switch` or `git checkout` command.

- Use `git merge` to merge one branch to another.

- To view changes between commits, use `git log` command.

- Try to use meaningful name for your identify your branches to easily identify their purpose.
