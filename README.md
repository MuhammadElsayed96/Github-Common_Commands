# Github-Common_Commands
This is a repo that contains all of my daily used Github commands

## keeping a fork repo up-to-date
### 1. Clone your fork repo:

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

### 3. Updating your localy forked repo from original repo to keep up with their changes:

    git pull upstream master

### 4. Updating your remote forked repo from your local repo:
  
    git push origin master
 
