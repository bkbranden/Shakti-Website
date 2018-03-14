# Shakti-Website
Website prototype for Shakti Competition


This is the github page for the Shakti Website!

Basically, we will create a separate branch for each html file, so each page.

Steps to use Github:

1. Create a folder then cd into it
2. Initialize git and add the remote
```
git  init
git remote add origin https://github.com/bkbranden/Shakti-Website
```

3. Pull Everything
```
git  pull --all
```
4. Checkout  all branches (just run this) (checkout changes the branch you are on)
```
git checkout products
git checkout homepage
git checkout master
```
5. Make sure you are using your branch when you commit 
```
git checkout <your branch>
```
6. Git add, commit, and push (run these command lines)
```
git add .
git commit -m (your message of what it is ex. Homepage version 1.0
git push origin (branch name)
```

7. (optional) If it is a change that we want (merge) (have to be on the master branch)
```
git merge --no-ff (branch name)
git push origin master
```
