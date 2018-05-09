# Github-Common_Commands
This is a repo that contains all of my daily used Github commands



## keeping a fork repo up-to-date
##### 1. Clone your fork repo:

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

##### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

##### 3. Updating your localy forked repo from original repo to keep up with their changes:

    git pull upstream master

##### 4. Updating your remote forked repo from your local repo:
  
    git push origin master
 
 
 
## Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| git init | Initialize a local Git repository |
| git clone ssh://git@github.com/[username]/[repository-name].git | Create a local copy of a remote repository |



## Basic Commands

| Command | Description |
| ------- | ----------- |
| git status | Check status |
| git add [file-name.txt] | Add a file to the staging area |
| git add -A | Add all new and changed files to the staging area |
| git commit -m "[commit message]" | Commit changes |
| git rm -r [file-name.txt] | Remove a file (or folder) |


## Branching & Merging Commands

| Command | Description |
| ------- | ----------- |
| git branch | List branches (the asterisk denotes the current branch) |
| git branch -a | List all branches (local and remote) |
| git branch [branch name] | Create a new branch |
| git branch -d [branch name] | Delete a branch |
| git push origin --delete [branchName] | Delete a remote branch |
| git checkout -b [branch name] | Create a new branch and switch to it |
| git checkout -b [branch name] origin/[branch name] | Clone a remote branch and switch to it |
| git checkout [branch name] | Switch to a branch |
| git checkout - | Switch to the branch last checked out |
| git checkout -- [file-name.txt] | Discard changes to a file |
| git merge [branch name] | Merge a branch into the active branch |
| git merge [source branch] [target branch] | Merge a branch into a target branch |
| git stash | Stash changes in a dirty working directory |
| git stash clear | Remove all stashed entries |
