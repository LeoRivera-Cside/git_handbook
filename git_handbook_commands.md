#Git Handbook of Commands

##Definitions
Current Working Location: The local environment where files are stored and modified.\
Staging Area: The step between local and remote repository. You can preview your local work before committing it to your remote repository.\
HEAD Pointer: Snapshot of the current working directory and the commit you are working on.\ 
Branch Pointer: Snapshot of a commit made in a branch.\

##Getting Started
Create a new Git repository:
```
git init
```\

Create a snapshot of your repository:
```
git commit
```\

Apply the inverse of the latest commit, undoing said commit. Safe if done locally. 
```
git revert
```\

Move the HEAD pointer and the branch pointer to another point in time. Caution: you may unintentionally lose work. 
```
git reset
```\

