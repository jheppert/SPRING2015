#School Project
A project for school

- Make a thing
- Use Git
- Be awesome

There are other things that will be done, but that is for a later time.

##Here are the steps for Git:
- git init
- git status
- git add .
- git status
- git commit -m "initial commit"

##Alternative commit command
###Skips the git add . command if files have been added already
- git commit -a -m "updated message"

##Steps to send stuff to GitHub
- git commit -m "updated message"
- git push -u origin master

###Shorthand push command
- git push

##Git Status Commands
- git status
- git log

###git log options
- git log --graph
- git log --pretty="%h - %s"
- git log --pretty="%h - %s" --graph

##Branching
Make a new branch:
- git checkout -b new_branch_name source_branch_name
Then pull code down:
- git pull [HTTPS URL of source to clone]
Git will merge files, flag any conflicts, and rely on you to resolve them

##Conflicts
- <<<<<<< HEAD
- Your code
- =======
- Their code
- >>>>>>> 01a090e97f3f630ce6dc24ca05009c235dcd4aba
