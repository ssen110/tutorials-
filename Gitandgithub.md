##
  Founder : Linus Torvalds
  Git : is distributed version control system
  SCM: source code management
  Git will do the version control for us.

##

   Features:
      Trunk Based Development (We are creating Branches for work and update)


!-------------------------------------------------------------------

    All the commits are stored in the github, so we can go and the end of every commit.

## Creating Branch:
   When we working on a project and updation is there, then we should use the `BRANCH` as it can be removed.

   If we want to merge multiple branches then we have to go `Copare and pull request` and we have to `Pull request`
   There can be issue with the pull request but we have to resolve it by our self in order to merge it.


!-----------------------------------------------------------------

## Fork :(For Multiple Developers)
     `Fork` for the developer who want to contribute
     `Pull request` for the owner of the repository
!------------------------------------------------------------------
## git bash :

      git init: initialize the empty git repository

      ls -lart : all hidden files as well

      git status : will say the status of files, taking the snapshot

      git add <filename>: untracked to staging

      git commit : to commit --> what changes have done.
      in vim editor <enter commit message> , then save it ( with :wq)

      touch <file name> :  will create empty file

      `git add -A : all files are moved to untracked to staging

      `git commit -m "<message>" : Then we don't have to edit the vim editor.`

      git checkout <filename> : if accidentally something happens or or the files got deleted then we can jump into our last commit

      `git checkout -f : all files are comeback to the last commit`

      git log : shows all the commits done with date and time

      git log -<count>: last <count> logs

      git status -s : will tell us the short status

      git log -p -<count>: last <count> logs with the updation(press `q` to quit)

!-------------------------------------------------------------------

      git diff : check the modification. to working directory with staging area.

      git diff --stage : compare staging area to last commit
!-------------------------------------------------------------
## Removing a file :

       git rm <filename> : deleting the file from directory as well as from from git.

       git rm --cached <filename> : will present in our hard disk(directory) but will be removed from git `staging area`
!----------------------------------------------------------------

## Ignore :

    `touch .gitignore` : files which shouldn't be added to our project.
    if <filename> is in the gitignore file, then git will ignore those files and folder as well
     <
     ## if we want to select all the .log files should be ignored then we should write  [*.log]
     ## if we just want we just want the main folder .log file then we should write it as : [/<filename>] >

!-------------------------------------------------------------------

## Branch :
  Copy another file of original part, then we can try new things on the branch so we dont mess up with the existing model till the new branch is in development part.

  `git branch <branch name>`: will create a branch.
  
   `git brach` : show all the branches

  `git checkout <branch name>`: will change to that branch
  
  `git merge <branch name>` : will merge the branch with master
  
  `git checkout -b <branch name>` : create and switch to that branch
  
  `git branch -d <localBranchName>` : delete branch locally
  
  `git push origin --delete <remoteBranchName>` :delete branch remotely

!-----------------------------------------------------------------
## GITHUB:


  `git remote add origin <URL>` :  the URL's short name will be 'origin', so every time origin will be used for the URL.
  
  `git remote -v` : will show the URL for fetch and push.
  
  `git branch <branch name>` : create a new branch.
  
  `git checkout <branch name>` : to change the branch name.
  
  `git push -u origin <branch name>` : will push the branch name to the origin.

  `git clone <URL>` : for cloning the repository.
