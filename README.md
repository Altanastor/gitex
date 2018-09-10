# gitex
Examples of how to use git and github branches
* Warning: This repo is just for learning purpouses

# Git Branches

## How to create branches

We are going to make an excercise using a branch's name : ``develop``. In the console write:

- `git branch develop`

Then switch to the branch :

- `git checkout develop`

To check the status of the current branch, write:

- `git status`  

That's all. Now we can work in the new branch and modify our code as we usually do.


## Commit changes in the branch

Part of the work can be commited in the current branch. We can comment and commit at the same time, using the next expression:

- `git commit -am "new commit in the branch"

## Merge branch in master

If we are ready to merge all the modifications from the branch into the master, firstly, we need to switch to the ``master`` branch.  

- `git checkout master`

Secondly, we merge all the changes into the master branch.

- `git merge develop` 


## Push the branch into GitHub

To publish all the changes into the GitHub repository, we need to swap to the develop branch 

- `git checkout develop`

Then, push to the origin (master) branch in GitHub.

- `git push -u origin develop`


