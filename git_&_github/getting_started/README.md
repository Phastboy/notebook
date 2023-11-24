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

