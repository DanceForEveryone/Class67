git commands
------------
pwd: present working directory
cd: change directory
ls: list all files and folders
mkdir: make directory

git init-intialize your repository with git and git starts tracking changes in your files
local
-----
working directory-{locally we do changes here and we do "git add file name"}, after git add file goes to staging area
staging area-here we do git commit -m "any message"
local repository- here we do git push, which takes the files to the remote repository

remote
------
remote repository
-----------------
git clone <github url>
git status-(it will show the names of modified files)
git add <fileName>
git commit -m "any message"
git remote add <remote repository name> <remote github url>
git push
--------
git diff -- staged: shows the difference between working directory and the previous commit
git log: shows all your commits with commit number
git checkout <commit id>: commit id is the first characters of commit id, it will take us to previous commit
git branch: shows all your branches
git checkout <branch name>: switch to a particular branch name
git branch <branch name>: to create a new branch
git diff <branch A> <branch B>: shows the difference between branches
git remote add origin <empty github url>
git push origin master
by default the branch is master