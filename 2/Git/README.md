# [Git](https://github.com/green-fox-academy/teaching-materials/blob/master/workshop/command-line/README.HU.md)

Check current git version: `git --version`

Update git: `git update-git-for-windows` then press <kbd><b>y</b></kbd> and <kbd><b>Enter</b></kbd>


## Create new repository

`git init`

## Check status:

`git status`

## Adding changes

`git add .` or `git add <file-name>`; example `git add *.txt` 

## Commiting

`git commit -m "message"`

## History

`git log`

## Setup git user details

`git config --global user.email` get user email

## Remote repository

To remove addition.

`git remote add origin https://github.com/lendoo73/GitTest.git`
origin is an alias

## Pull

`git pull origin HEAD --allow-unrelated-histories`


## Pushing remotely

`git push -u origin HEAD`

## Clone repository

If the GitHub repository already created

`git clone https://github.com/lendoo73/GitTest.git`

## Differences

`git diff HEAD` or `git diff <file-name>`

Head mean the previous completed version

After adding changes `git diff <file-name>` will show nothing

`git diff --staged `
`git diff --cached <file-name>`

## Resetting the stage

`git reset <file-name>`

## Undo

To remove all modification from the file (undo).

`git checkout -- <file-name>`









