# GitHub Commands
### Git setup
- git config --global user.name “[firstname lastname]”
- git config --global user.email “[valid-email]”

### Create a new local repository
- git init

### Checkout a repository
- git clone /ssh part

### Add files
- git add .
- git add <file name>

### commit changes to head (not to remoute repo)
-  git commit -m "massage"

### Commit any file that you have added with git
- git commit -a

### Send changes to the master(main) branch of your remote repo
- git push origin master(main)

### To connect local repo to a remote server
- git remote add origin <url>

### List all the repo
- git remote -v

### Create a new branch
- git checkout -b <branch name>

### List all the branches in repo (and the current branch)
- git branch

### Delete the branch
- git branch -d <branch name>

### Push the branch to remote repo
- git push origin <branch name>

### Switch from one branch to another
- git checkout <branch name>

### Push all the branches to remote repo
- git push --all origin

### Fetch and merge changes on the remote server
- git pull

### Merge a branch
- git merge <branch name>

### Check a status of repo/ code (if there any changes)
- git status

### Help with commands
- git help
-  git -a

### History of changes
- git log


