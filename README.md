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
    
