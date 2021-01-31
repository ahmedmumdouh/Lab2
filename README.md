[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/uses-brains.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-black-magic.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/makes-people-smile.svg)](https://forthebadge.com)

# lab2
myNewProject

# How to delete local and remote branch
* delete branch locally
  *  git branch -d test
  *  git branch -d dev

* delete branch remotely
  *  git push origin --delete test
  *  git push origin --delete dev

# How to list tags locally 
* git tag -n

# How To Delete Local and Remote Tags
* delete tag locally
 * git tag -d v1.4

* delete tag remotly
 * git push --delete origin v1.4
 
 # What is Git Rebase ?
 * Rebasing is the process of moving or combining a sequence of commits to a new base commit. Rebasing is most useful and easily visualized in the context of a feature branching workflow.
 ![Example Image](https://wac-cdn.atlassian.com/dam/jcr:d3b2abde-d06a-47b6-8955-5f3ef34e0237/03.svg?cdnVersion=1432)
 
 * Create a feature branch based off of master -> git checkout -b feature_branch master Then  Edit files -> git commit -a -m "Adds new feature" 
 * Then git rebase to merge with master
 
 This automatically rebases the current branch onto , which can be any kind of commit reference (for example an ID, a branch name, a tag, or a relative reference to HEAD).
 
 # Sample Image
 ![image url include](https://i.morioh.com/2019/11/11/1f265e2d4c43.jpg)
 
# Foobar
Foobar is a python library for dealing with word pluralization.

# Installation
use the package manager pip to install foobar.
``` python
pip install foobar
```
# Usage
``` python
import foobar

foobar.pluralize('word') #returns words
foobar.pluralize('goose') #returns geese
foobar.singularize('phenomena') #returns phenomenon
```
# Contributing
Pull requests are welcome. For major changes, please open and issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

# License
[MIT](https://mit-license.org/)

![image url include](https://i.morioh.com/2019/11/11/1f265e2d4c43.jpg)

  
