# Introduction to Git

## Version Control

Version control is the practice of tracking and managing changes to software code, documents, or other collections of information.

**version control systems**

Version control systems are software tools that help software team manage changes to source code over time.

Version control software keeps track of every modification to the code in a special kind of database.
One of the most popular version control system is `Git`.

### Importance of Version Control

1. **History Tracking:** Version control systems keep a detailed history of changes made to codespace.

2. **Collaboration:** It allows developers to work on different parts of the code simultaneously, and then merge their changes together. 

3. **Code revert and rollback:** In case a change introduces a bug or a feature doesn't work as expected, version control allows you to revert to a previous, stable state of the code.

4. **Branching and parallel development:** Version control systems support branching, which enables developers to work on isolated features or bug fixes without affecting the main codebase.

5. **Code reviews:** Version control facilitates code reviews by providing a clear view of the changes made in a particular commit.

6. **Continous Integration and deployment (CI/CD):** Modern development practices often involve automated processes for building, testing, and deploying code changes.

7. **Documentation:** Commit messages in version control systems serve as a form of documentation. They provide insights into the rationale behind specific changes, making it easier for developers to understand the context of the code modifications.

## Git and GitHub

Git is an open source distributed version control system that tracks changes in any set of computer files.

GitHub is web-based platform for hosting and collaborating on Git repositories.

### Importance of Git and GitHub

1. **Version control:** 
    - Git allows developers to track changes in their codebase over time. This means you can go back to a specific version of your project, compare changes, and understand how your code evolved.
    - GitHub complements this by providing a centralized platform to host Git repositories, making it easy to manage and visualize the entire history of a project.

2. **Collaboration:** 
    - Git enables multiple developers to work on the same project simultaneously. It manages changes made by each person and helps merge those changes seamlessly.
    - GitHub serves as a centralized hub for sharing code with the global developer community.
    - Forking repositories allows developers to create their copies of a project, make changes, and propose these changes back to the original project through pull requests.

3. **Branching:**
    - Git provides a powerful branching system. This allows developers to work on new features or bug fixes in isolation without affecting the main codebase. Once the work is complete, branches can be merged back into the main branch.

4. **Backup and Restore:** Git serves as a backup mechanism. Every commit is a snapshot of your project at a specific point, offering a safety net in case something goes wrong. If needed, you can restore the entire project to any previous state.

5. **Traceability and Accountability:** 
    - Git logs all changes made to the code, including who made the change and when. This traceability helps in identifying issues, understanding the evolution of the codebase, and holding contributors accountable.

6. **Continuous Integration and Deployment:**
    - GitHub Actions automates the process of continuous integration and deployment, enhancing the reliability and efficiency of software development pipelines.
    - This integration allows developers to test and deploy their code directly from the GitHub repository.

7. **Community Engagement:**
    - GitHub features like Discussions and Actions Marketplace enable developers to share knowledge, seek help, and collaborate on various aspects beyond just code.

## Setting up Git

### Installing Git

#### Linux Installation

- You can install Git on Linux Ubuntu and Debian by running:

    ```bash
    sudo apt install git
    ```
***This for Ubuntu and Debian distribution and will not work for other distribution.***

- After installation, verify Git by running:

    ```bash
    git --version
    ```

#### macOS installation

- You can install Git on macOS by running:

    ```bash
    brew install git
    ```

- After installation, verify Git by running:

    ```bash
    git --version
    ```

### Configure Username, Email and default Branch

#### 1. Configure Username and Email

- Set your Git username and email using the following commands:

    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

#### 2. Configure Default Branch

- By default, Git uses the term "master" for the main branch. However, there's a move towards more inclusive language, and some repositories may use "main" instead. You can configure Git to use "main" as the default branch globally with:

    ```bash
    git config --global init.defaultBranch main
    ```

- This ensures that every time you initialize a new repository, it will default to creating a "main" branch instead of "master."
