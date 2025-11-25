# Git Handbook of Commands

## Definitions

**Repository**: Where the entirety of your project is stored. 

**Current Working Location**: The local environment where files are stored and modified.

**Staging Area**: The step between local and remote repository. You can preview your local work before committing it to your remote repository.

**HEAD Pointer**: Snapshot of the current working directory and the commit you are working on.

**Branch Pointer**: Snapshot of a commit made in a branch.

**Remote**: A repository stored on a server on another machine.

**Merge**: Converge a branching series of commits back into the desired series of commits. Think of a marginal street merging back into the main road.

**Rebasing**: Reorganize a branching series of commits into another series of commits. Consequently, only series of commits is left. Think of restacking traffic cones.

**Squash**: Combine a branching series of commits into a singular one. Branch still exists. 

**Cherry Picking**: merge specified commits in a specified order into master. Think of sorting a deck of cards.

**Stash**: temporarily save your changes that are not ready to commit. 

## Getting Started
Create a new Git repository:
>git init 

Configure git to get and set repository or global options:
>git-config <command/flag>

Set your Git unsername for every repository on your computer
>git config --global user.name "<username>"

Stage changes to to the repository:
>git add <file> 

Create a snapshot of your repository:
>git commit  

Apply the inverse of the latest commit, undoing said commit. Safe if done locally. 
>git revert  

Move the HEAD pointer and the branch pointer to another point in time. Caution: you may unintentionally lose work. 
>git reset  

Add a remote repository to your local configuration:
>git remote add <remote_repo_name> <remote_repo_url>  

Push a local repository to your remote repository:
>git push <remote_repo_name> <local_branch_name>  

Pull a remote repository to your local repository:
>git pull <remote_repo_name> <local_branch_name>

Temporarily save your changes without committing them:
>git stash

## Collaboration

Create an independent local copy of a repository on your machine:
>git clone

Create a linked copy of a repository:
>git fork 

Request a pull from your repository, showing the difference between repositories:
>git request-pull <start> <URL>

Join two or more development histories together
>git merge

Retrieve changes from a remote repository into your local clone without automatically merging any of the changes into your local repo:
>git fetch

Create an independent line of development within the repository, creating a fork:
>git branch <branch_name>

List all the branches in your repository
>git branch

Delete the specified branch unless it has unmerged changes:
>git branch -d <branch_name>

Delete the specified branch:
>git branch -D <branch_name>

Rename the current branch:
>git branch -m <branch_name>

Add a remote; a repository stored on a server on another machine:
>git remote add <repo_name> <repo_url>

list remotes:
>git remote -v

Update the name of an existing remote:
>git remote rename <old_repo_name> <new_repo_name>

Delete a remote:
>git remote remove <remote_repo_name>

