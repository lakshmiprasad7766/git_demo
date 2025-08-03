Git demo by Telusko  (Udemy)

Git -> VCS -> used to update/ to make the changes in the file

Installation:

in mac -> default installed, not in windows

-> git --version

#ti get the user details:
-> git config --global --list

# To set the user configuration

-> git config  --global user.name "Prasad"
#set email ID

-> git config  --global user.email "lakshmiprasad7766@gmail.com"


## Git Init

-> open Vscode
-> open folder  -> it is working directory
->open terminal -> 

# working directory; staging area : where user wants to track the folder/files using this git ->tc of these files
 # Others u can ignore
# commit history -> where we see can the commiting details

# in terminal
-> git init -> creates local repository in local machine/project
           # it shows the file path as well -> hidden folder -> git trackes  thsi file.

(This is most important command, so that git recognizs that this is the part of Git Repo to take care).

# if you work in file and save it, it won't save in Git repo untill you git tracks this file.

->  git status -> now it works -> On brach master && No commits yet
                # we dont need mastr, we need main

To delete the file:
-> rm -rf .git  _ it shows error (delete from local machine)

-> git status  ; not a git repo (empty folder)

# To get main 

-> git init -b main  -> branch is main; No commits




## Git commits

-> git status ; no commits; empty file

-> click new project;
working directory -> your code/file in local machine
Local repo -> local .git file ;
need to push in staging area

#To commit the file we need to use add command

-> git add firstcode.txt
-> git status ; first code file in staging area

-> git log
-> git commit ; file goto local repo

# For every	commit give "message" to the commit you hve changed

-> git commit -m "my first commit"

# Now this file is tracked by Git
-> git log


## Git skipping

-> working directory -> staging area (add) -> local repo in git (commmit) 

To skip the staging area, we can use -a comand

-> git commit -a -m "My third commit"


# Git Diff
 It will show the what are the commits I have changed in the file.

-> git add Fiestcode.txt
-> git diff
-> git diff --staged   ; To know the commits made in the staging area

#To remove a file
 -> 
















