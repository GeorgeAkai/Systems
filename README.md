# CSCI 32 - Spring 2023 #

### What is this repository for? ###

* Class Lecture Files
* Class Exercise Files
* Class Lab Files

### How do I use this repository? ###

+ The main branch has this README.
+ To list available branches to checkout run the following
    *  cd ~/environment
    *  git branch -a
+ To checkout a particular branch run the following:
    *  git checkout BRANCHNAME
+ To get back to the main branch:
    *  cd ~/environment
    *  git checkout main


### How to get new files into the repository if you already have created it ###

* Open up your terminal
+ Run the following commands in the terminal:
    * cd ~/environment
    * git fetch class
    * git checkout main (or whatever branch you want to checkout)
- Your repository should now be up to date

### How to setup your repository to get new files from me ###
* Open up your terminal
+ Run the following commands in the terminal:
    * cd ~/environment
    * git remote add class https://github.com/WD2sp23/wd2sp23.git