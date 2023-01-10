GIT - Version changes can be tracked using software.It is source code control or version control.


GIT COMMAND:
	int
	Pull
	Push
	Commit
                Repository
Remote repository
Local repository
Branch
Master branch
Develop branch
Feature branch
Hotfix
Bugfix
Stash
Merge
Switch

               	
	
	





int:
	used to initialize blank repository. It creates a .git folder(will create hidden folder that can be visible only by enabling setting ) in the current working directory.


add:
	used to add the new files in the current directory to the staging area.

status:
	used to display the state of current repository and staging area.

Clone:
	used to create a copy of the target repository.

Pull:
	To fetch and download the content from remote repository and immediately update the local repository to match that content.
	                   Remote →Local

Push:
	To upload the content of local repository to remote repository.
		   	   Local →Remote 

Commit:
	Records or captures the snapshot of the currently staged(arangaetrapatathu)(eg:annual-+
day stage not every dancer will perform on the stage in same time) changes.

Repository:
	Contains all your project files and each files revision history.

Remote repository:
	Stored on another computer / miles away 
Local repository:
	Stored in our computer 

Branch:
branch refers to the independent line of the development.
branch command is used to create, find list,rename and delete branches.

Master Branch:(trunk of the tree)
	Contains production code. all the development code merged sometimes in master.

Develop Branch:
	Contains pre-production code. When the features are finished then they are merged into develop.

Feature branch:(stem of the tree)
        It is the copy of main codebase where individual or team of software developers can work on a new features until it complete.

Hotfix branch:
	A fix on live, active software or app.

Bugfix:
	A fix for issues found through development lifecycle but before release; applied during production or testing phase.


Switch/Checkout:
	Checkout command operates on three distint entities;
files
commits
branches


Stash (pathukivaikka):
	User can retrive all files put in the stash.
	Git stash temporarily shelves(or stashes) changes you have made to your working copy so that you can work on something else and again come back and reapply them later on.
	
Merge:
In git , the merging is the9++6+ procedure to connect forked history.
It joins two or more development history.
It is used to integrate different branches into single branch.
Used to combine two branches.	

FETCH VS PULL:
git fetch is the command that tells your local git to retrieve the latest
meta-data info from the original (yet doesn't do any file transferring.
It's more like just checking to see if there are any changes
available). git pull on the other hand does that AND brings (copy)
those changes from the remote repository.

PROCESS:


                
REMOTE REPOSITORY

                      

CLONE (will be in master branch;makes repository available)


                
SWITCH TO DEVELOP



CREATE FEATURE BRANCH



DO CHANGES



GIT ADD(only new files)



COMMIT(new files & modified; will commit in local)



PUSH to repository

