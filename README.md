# github-3.2-renpeng
# a) git clone
## Type git clone, and then paste the URL you copied earlier. git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY Press Enter to create your local
# b) git pull
## The git pull command is used to fetch the latest changes from a remote Git repository and merge them into the current branch. It combines two steps: git fetch and git merge
# c) git commit
## The git commit command is used to save your changes as a new commit in the Git repository. A commit represents a snapshot of the project's state at a specific point in time.
# d) git push
## The git push command is used to upload your local Git commits to a remote repository. It allows you to share your changes with others or synchronize your work across multiple machines. 
# e) git fetch
## The git fetch command is used to retrieve the latest changes from a remote Git repository without merging them into your local branch. It updates your local repository's knowledge of the remote repository's branches and their commit history.
# f) git config
## The git config command is used to set and retrieve configuration options for your Git environment. Git stores configuration settings in three levels: system, global, and local. 
# g) git add
## The git add command is used to stage changes in your working directory for inclusion in the next commit. It is an essential step in the Git workflow before committing your changes. 
# h) git branch
## list your branches. a * will appear next to the currently active branch
# i) git reset
## unstage a file while retaining the changes in working directory
# j) git log
## show all commits in the current branch’s histor
# k) git rm [file]
## delete the file from project and stage the removal for commit
# l) git stash
## Save modified and staged change
# m) git rebase [branch]
## apply any commits of current branch ahead of specified one
# n) git reset --hard [commit]
## clear staging area, rewrite working tree from specified commit
# o) git stash list
## list stack-order of stashed file change

# What are the 4 Github commands that you think you will use the most in the real project and why?
## 

## 1. `git clone`: This command allows you to create a local copy of a remote repository. It is often used when you want to start working on an existing project or collaborate with others. By cloning a repository, you can have a local version of the codebase on your machine to make changes, run tests, and contribute.

## 2. `git pull`: When you're working on a project with multiple contributors, it's crucial to keep your local copy up to date with the latest changes from the remote repository. The `git pull` command fetches the latest commits from the remote repository and merges them into your local branch. This ensures you have the most recent version of the code before making further modifications.

## 3. `git add`: Before committing changes to your local repository, you need to stage the modified files or new additions. The `git add` command allows you to specify which files should be included in the next commit. You can either add specific files (`git add file1.js file2.css`) or use wildcards to add multiple files at once (`git add *.txt`).

## 4. `git commit`: After staging the changes using `git add`, you can create a commit to save your modifications permanently in the local repository's history. The `git commit` command lets you create a new commit with a descriptive message that explains the changes you made. Commits serve as milestones in your project's development, making it easier to track changes and collaborate with others.
