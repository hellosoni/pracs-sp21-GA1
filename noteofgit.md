# Overview Git (Week 3)
**Git** is one of the *Version Control Systems*. <br>
**GitHub** (https://github.com/) is the website that host several repositories. <br>
Version control using Git is done by "commit" or saving the snapshots of the progress. <br>
There are three important commands for Git
```
#Stage files to be committed:
$ git add
#Commit all currently staged changes:
$ git commit
#Get the status of the repository:
$ git status
```
# Simple workflow for a Git project

```
# Load the Git module:
$ module load git
#Create a directory and initialize the new repository:
$ git init
#Check status of the repository:
$ git status
#Create a sample text file in the repository:
$ touch file.txt
# Write some content in the file:
$ echo "Content..." > file.txt
# Start tracking the file, and stage it:
$ git add file.txt
# Check the status of the file again:
$ git status
# IF everything looks OK. Commit the file with a message:
$ git commit -m "Commit message"
```







