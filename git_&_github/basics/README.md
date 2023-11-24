# Repository

A repository, often abbreviated as `repo` is a project's folder that contains all the files and the entire history of changes made to those files.

## Working with Repository

### 2. Initializing a repo

- To initialize a directory, run:

    ```bash
    git init
    ```

- This will create a `.git` subdirectory in the project directory that stores all the version control information.
- If you have some files or directories that you don't want to track their changes, you can `.gitignore` file and put their name inside the file.

### 2. Remote repo

- To link your local repo to remote repo, use `git remote add` command.

### 3. Staging and committing

- Use `git add` to stage changes for commit.
    - **Examples:**
        - To stage all changes, use
            ```bash
            git add .
            ```
        - To stage changes in a particular file, use:
            ```bash
            git add fileName
            ```
- Use `git status` command to check which changes have been staged.
- A commit is a set of changes made in a repo. To commit changes, use `git commit` command.
- Using `git push` to upload local changes to a remote repository.
- Using `git pull` to fetch changes from a remote repository.

### 4. Cloning a remote repo

- You can also clone a remote repo repo with `git clone command`. e.g, 

    ```bash
    git clone linkToTheRepo
    ```

