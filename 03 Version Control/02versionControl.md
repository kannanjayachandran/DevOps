# Version Control

**Version control** is a system that records changes to a file or set of files over time so that we can recall specific versions later. It does not need to be a software, version control can keep track of any kind of files in a computer. Version control is a very important part of **DevOps** also, as it allows us to keep track of changes and revert back to previous versions if needed. It also allows us to collaborate with other developers on the same project. version control also plays a key role in **CI/CD**.

There are many version control systems available, some of the most popular ones are:

- **Git**
- **Mercurial**
- **Subversion**
- **CVS**

## Git

Git is a distributed version control system. It is the most popular version control system in the world. It is used by many companies and organizations, Git is a free and open source software. Git allows us to keep track of changes in our code, it also allows us to collaborate with other developers on the same project. Git is a very important part of DevOps, it allows us to keep track of changes and revert back to previous versions if needed. It also allows us to collaborate with other developers on the same project. Git also plays a key role in CI/CD. We can use services like GitHub to host our repositories remotely.

### Essential Git commands

- `git init` - Initialize a local git repository
- `git add` - Add files to staging area
- `git add .` - Add all the files in the current directory to staging area
- `git commit -m "commit message"` - Commit changes to local repository
- `git push` - Push changes to remote repository
- `git pull` - Pull changes from remote repository
- `git clone` - Clone a remote repository
- `git status` - Check the status of the local repository
- `git log` - Check the commit history
- `git checkout` - Switch between branches
- `git branch` - Create a new branch
- `git merge` - Merge branches

### Git Branching

In Git, a branch is a separate line of development. You can create a new branch to make changes, and then merge those changes back into the main branch when you're ready. This allows you to work on multiple features or fix multiple bugs concurrently, without affecting the main codebase.

- To create a new branch, you can use the git branch command followed by the name of the new branch. For example:

 ``` git
    git branch new-branch
```

- This creates a new branch called "new-branch" based on the current branch. To switch to the new branch, you can use the git checkout command followed by the name of the branch. For example:

     ``` git
        git checkout new-branch
    ```

- Once you have made your changes and committed them to the new branch, you can switch back to the main branch and merge the changes using the git merge command. For example:

     ``` git
        git checkout main
        git merge new-branch
    ```

- It's also possible to delete a branch using the git branch -d command followed by the name of the branch. For example:

``` git
    git branch -d new-branch
```

### Some important features of Git

- Distributed version control

- Branching and merging

- Fast and efficient

- Excellent support for collaborating:

- Integrations with other tools
