# Simple Git
<hr/>
A simple repository used to experiment with and learn Git.

## What is git?
https://git-scm.com/book/en/v1/Getting-Started-Git-Basics

## If you have Windows
1. Download git bash

## What to Learn About Git
1. When in doubt?
        
        git help
2. Forking a repo
3. Cloning a repo

        git clone repo-url
4. Edit the files on your local machine, and save them
5. Pulling updates and pushing changes on one branch:

        a. edit a file on github
        
        b. git pull origin master
        
        c. git status
        
        d. git add . ## add all of the files to the working directory
        
        e. git add filename ## add only the file of interest to working directory
        
        f. git commit -m "First commit message"
        
        g. git remote -v      # lists remote branches 
        
        h. git branch         # lists local branches
        
        i. git push origin master 
        
 5. Creating another branch
 
        First, you create your branch locally:
          a. git checkout -b <branch-name> # Create a new branch and check it out
          
          b. make some changes to a file and save
          
          c. add and commit the changes (see above)
        
        The remote branch is automatically created when you push it to the remote server
          d. git push <remote-name> <branch-name> 
          
          
:fire: :fire: :fire: :fire:
