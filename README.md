# project
My 1st repository


Git commands
============

git init - initializing git repository
git add - adding file or directory inside the git 
git status - identify the current state of work done so far
git commit -m "message" - commit your changes 

git rm --cached filename - remove added file


configure proxy
===============
git config --global http.proxy proxyaddress
git config --global https.proxy proxyaddress

configure username and password
===============================

git config --global user.username githubusername
git config --global user.password githubpassword


branches
=======

git branch --list available branch
git checkout <branch name> -- create new branch
git checkout <branch name> --merge different modifications from different branches
git branch -d <branch name> --delete the specific branch
