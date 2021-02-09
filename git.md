# Git

## Git initial setup
### 00. Using inbuilt Git help
> * git help
> * git help [command]

### 01. Configuring user
> * git config --global user.name "aniket pawar"
> * git config --global user.email "oneaniket@gmail.com"

### 02. To view all the configs
> * git config --list

### 03. Create first local repository
> * Create a empty folder/directory in you machine 
> * cd  "new folder/directory"
> * git init # initialize git in this directory. Check the content of this directory now. Make sure you can view hidden files

### 04. Commiting changes to local repository
> * Add a file in your local repo
> * git status
> * git add "filename"
> * git commit -m "meaningful msg"

### 05. Check changes in the file
> * git diff    # git diff will show the changes between staging area and working area. 
> * git diff --staged # To view the changes from staging area

### 06. Adding a remote repository
> * Create a empty folder/directory in you machine 
> * cd  "new folder/directory"
> * git init
> * git remote add origin "repo https link"

## Git branch
### 01. Creating a new branch
> * git branch "branch_name"
> * git checkout "branch_name" change to "branch_name" from master/main branch
> * git checkout -b "branch_name"   # create and change to "branch_name"

### 02. Merging of branch
> * switch to you master branch and run below two commands
> * git merge "branch_name" # this will merge the branch on your local repostitory. 
> * git push origin master

### Note : Your current branch from where you ran merge command will be your target branch. Run this command from master branch. "branch_name" will be merged with master branch

### 03. Revert commit 
> * git reset HEAD "filename" # Revert from staging area to working area
> * git reset HEAD~ "filename" # Revert from last commit
