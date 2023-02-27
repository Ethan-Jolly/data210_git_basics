# DATA210 Git Basics

## Cloning a repo

* Start off by getting the repo link from github
* Then use that link in the git clone command
* e.g. **git clone https://github.com/Ethan-Jolly/data210_git_basics.git**

## Make any changes to your local

* Once you have the repo cloned to your machine, you can make any changes you wish to the files.

## Stage changes

* Once you are happy with your changes, you first need to stage them so we can add them to the repo.
* To do this we do **git add file_name** (or **git add .** to include all files with changes).
* We can also check the status of the git staging, checking which files are staged by doing: **git status**.

## Commit changes

* After adding all the files you made changes to, you want to use **git commit -m "<commit_message>"** to commit the changes you made to your local repo.

## Pushing to GitHub

* After commiting your changes to your local repo, you can use **git push -u origin <branch_name>** to push your changes to the GitHub repo.

## Branches

* If you want to create a new branch for the repo, you can do this by using **git checkout -b <branch_name>** (to switch between branches remove the **-b** flag).