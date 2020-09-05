Download and Install Git Version Control System
Download and Install Smart Git

Main Git Operations
	Add
	Commit
	Push
	Pull

Other Git Operations 
	Branching
	Merging
	Rebasing

Imprtant Terms
	Local Rep
		Working Directory
		Staging Area
		Local Repository
	Remote Rep
		Remote Repository
		

File Status LifeCycle
	UnTracked
	UnModified
	Modified
	Staged
	
Unstaged Color: Red
Staged Color:   Green

Branch
Stash

	
	
	
	
	
	
	
Important Commands
	git init                            			// To initialize current Working Directory
	git add .                           			// Add file/folder to be tracked by git
	git commit -m message 					// Commit git repository with message
	git reset                           			// To unstage all staged files but not for commit files
	git reset --hard                     			// To unstage file and reset changes also
	path/to/file.ext OR filename OR *.ext OR /* 		//To ignore files and folders, Here make folder .gitignore and write what to ignore
	
	git branch						//To show all the branches
	git branch -v						//Show Branches with details
	git branch branchname					//To create new branch, Here branchname is name of branch
	git checkout branchname					//To switch to specific branch
	git log branch1..branch2				//To compare two branches or to see changes
	git merge branchname					//To merge specific branch in main branch
	
	git stash						//To save text on clipboard temporarily
	git stash list						//Show list of stashes
	git stash save stashname				//save stash with specific name
	git stash pop						//Apply latest stash and remove it from clipboard
	git stash apply stashname				//Apply stash with specific name and also keep in clipboard
	git stash clear						//To clear all stashes
	
	git clone https://url					//Clone/copy repository to local machine
	git push origin master					//To push repository to server, here master can be replaced with desired branch name
	git fetch						//To fetch changes from remote repository
	git merge						//merge chenges that were feched from remote repository
	git pull						//To fetch and merge changes from remote repository
	git remote -v						//Show remote repository urls
	git remote show origin					//Show complete details of fetch, pull, branches etc
	git remote add myremote http://url			//To connect local repository to remote repository on given url
	
	
	
	
	
Updating this file to check commits
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
