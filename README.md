# Git Demo

This is a demo git repo with a list of commands as a cheat sheet.

## Creating a local repo

1) Change into the required folder:
	PC: 
    ` cd %HOME%\Source\Repos\ `
	MAC:
    `cd ~/Source/Repos`

2) Create New Folder:
	`mkdir Project-Name`

3) Change into the new folder
	`cd Project-Name`
    
4) Initialise with git
	`git init`
    
5) Change master to main
	`git branch -m master main`

6) Check the status
	`git status`
    
7) Create a .gitignore
	MAC:
	`touch .gitignore`
    PC:
    `echo "" > .gitignore`
    
8) Add required "ignores" to the .gitignore file. Recommend that you use a known .gitignore or head to [http://gitignore.io](http://gitignore.io) 

9) Check the status
	`git status`
    
10) Add and commit the ignore file to version control
	`git add .gitignore`
     `git commit -m "Original Commit`
     
11) Verify commit
	`git status`
    
### Adding files to Tracking
`git add filename`
`git add -A`
`git add foldername/*`
`git add.`

### Checking the logs
`git log`

### Create a branch
`git branch Branch_name`

### Changing branch
`git checkout Branch_name`
    
### Merging changes from one branch into main
`git checkout main`
`git status`
`git merge Branch_name`
`git status`
`git log`

## Remote Repositories
Before you ca use remote repository(repo) you need to have created it on the remote system

We will use GitHub for this purpose, other remote repositories that use Git are also valid

### Create a remote repo
1) Head to http://github.com
2) If you do not have an account, create a github account
3) Create a new repo making sure that:
	- Do not add a README.md
	- Do not add a License
	- Do not add a .gitignore
	- In other words: Do not add anything to the blank repo

### Connecting a remote repo
`git remote add origin https://github.com/bijit85/git-command-help.git`

origin = alias for the remote

### Asides
| Heading1 | Heading2 | Heading3|
|----------|----------|---------|