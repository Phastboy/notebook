# Branching in Git

Branching is to create a branch.

## Branches

- **Branches** are divergent lines of development within a repo.
- The default branch of a repo is the `main` branch.
- Branches allow you to separate your work from the main branch.
- They allow developers to work on separate features, bug fixes, or experiments without directly impacting the main or other branches until changes are ready to be merged.
- Changes in one branch does not affect the other until they're merged.

## Working with Branches

- To create a branch, use `git branch` command.
- **For example,** creating a branch for a new feature:

    ```bash
    git branch new-feature
    ```

- You can switch between multiple branches using `git switch` or `git checkout` command.
    - **For example:** To switch to the branch named `new-feature`, run:
        ```bash
        git switch new-feature
        ```
        or
        ```bash
        git checkout new-feature
        ```

- Use `git merge` to merge one branch to another.
    - **For example:** If you want to merge the branch named `new-feature` to the main branch, run:
        ```bash
        git merge new-feature
        ```

- To view changes between commits, use `git log` command.
    - If you think the info displayed for the command `git log` is to complicated, you can run `git log --help` to view the available options for the `git log` command.

- Try to use meaningful name for your identify your branches to easily identify their purpose.

