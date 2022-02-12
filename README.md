# React_infopage_template
Template for a very simple react web page

## Setup

### Git Guide (including cloning)
* make sure gits installed
* git clone https://github.com/shaunkaufmann01/React_infopage_template.git | this will clone the repo
* git init| go to root dir and run "git init" to initialize git repo
* (if needed) git remote add origin https://github.com/shaunkaufmann01/React_infopage_template.git | if the remote repo called "origin" does not exist this will add it.
* git checkout -b <branch-name> # Create a new branch and check it out
* git push --set-upstream <remote repo name(typically "origin")> <branch-name> # make branch remote
* git add <filename>|add specific file to staging area OR git add --all |add all files to staging area
* git rm <filename> remove file from staging area
* git commit -m '<commit description goes here>' | create a commit
* git push | push changes to branch
* typical sequence when developing a new feature:
    * create and checkout on new local branch with "git checkout -b <branch-name>"
    * make remote branch push --set-upstream <remote repo name(typically "origin")> <branch-name>
    * while developing feature:
        * make changes to code in file and save
        * add file to staging with git add <filename> or --all
        * commit changes with git commit -m '<commit description goes here>'
        * push to remote branch with git push
        * repeat until feature is build and passing tests
    * once finished get a a review to check your code
    * request a merge to merge branch
    * merge branch with (while on master branch) git merge <other branch name> 
    

### yarn guide
