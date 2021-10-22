# Learn Git and Github 🚀


## Basic Workflow ⚡

To intilalized local git directory

    git init

To add untracked files or changes

    git add <file-name>

To add all changes on a at once

    git add .

To commit added changes or files

    git commit -m "your message"

## Configure username & emial ⚙

To use git with github, you have to configure your git with github. To configure run following commands

> for github username
```git
git config --global user.name "Your github-username"
```
> for email

    git config --global user.email "your email"


## Remote Setup 🛠
To push your code from your local directory to remote you have to link your local directory with github repository. To link your local git directory with remote repository run

    git remote add origin <repo-url>

To push your changes from local directory to remote repository

    git push -u origin master

## Branching 🌿

When the size of the project increases, it is recomended to break your project into several branches to manage your codebase efficiently.

To create a branch

    git branch <branch-name>

To switch to that branch

    git checkout <branch-name>

you can also use a shortcut to create and switch to a branch at the same time

    git checkout -b <branch-name>


to merge a branch i.e **temp-br** into another branch i.e **master**, first switch to that branch by running

    git checkout master

then run

    git merge temp-br

or you can push your branch into github by 

    git push origin <branch-name>

After merging a branch into another, it's redundant to keep the merged branch. To delete a branch run

    git branch -d <branch-name>

## Cloning 🔽
To clone/download a github repository into your computer run 

    git clone <repo-url>

## Author 👨‍💻
Yo👋 it's Meer. Let's get connected

- [LinkedIn](https://www.linkedin.com/in/meerhamza1421/)
- [Twitter](https://twitter.com/MeerHamza1421)
- [DEV](https://dev.to/meerhamza1421)

>Spare a star ⭐ if you like this repo