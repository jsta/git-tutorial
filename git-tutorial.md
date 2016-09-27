# Git tutorial

## Create Github account

**Does everyone have RStudio?**

## Why git?

![](phd101212s.gif)
![](https://cdn.rawgit.com/aht/whatisgit/master/git-local-remotes.png)

## Open the Shell
* Rstudio -> tools -> shell

## Configure git
* Setup user.name

`> git config --global user.name 'Joseph Stachelek'`

* Setup user.email

`> git config --global user.email 'jstachelek@utexas.edu'`

* Check settings

`> git config --global --list`

## Workflows

### Create new on Github

* `+` -> `New Repository` -> `gitdemo` -> `Initialize with a README`

* `Clone or Download` -> Copy URL to clipboard

#### RStudio
* Projects -> New Project -> `Version Control` -> `Git repository` -> Paste git URL

![](https://cdn.rawgit.com/aht/whatisgit/master/git-local-remotes.png)

* Open file from file pane and make a change

* Git tab -> "check box" -> Commit

* Look at history tab -> Push

* Look at Git drop-down menu for individual files


### Create new on local Computer

* Create a folder
* Create a README.md file

`> git init`

`> git add README.md`

`> git commit -m "added README"`

* Github -> `+` -> `New Repository` -> `gitdemo2`
  
`> git remote add origin https://github.com/jsta/gitdemo2.git`

`> git push -u origin master`

## Collaborating with others

![](https://cdn.rawgit.com/aht/whatisgit/master/workflow-c.png)

* Fork my repo at [https://github.com/jsta/git_collaborate](https://github.com/jsta/git_collaborate)

* Clone the repo locally

* Make a change to the README

* Push to your clone

* Initiate a pull request

## Demo GitKraken

[https://www.gitkraken.com/](https://www.gitkraken.com/)

