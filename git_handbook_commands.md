#Git Handbook of Commands

##Definitions\
Repository: Where the entirety of your project is stored. 
Current Working Location: The local environment where files are stored and modified.
Staging Area: The step between local and remote repository. You can preview your local work before committing it to your remote repository.
HEAD Pointer: Snapshot of the current working directory and the commit you are working on.
Branch Pointer: Snapshot of a commit made in a branch.

##Getting Started\
Create a new Git repository:
>git init \

Stage changes to to the repository:
>git add <file> \   

Create a snapshot of your repository:
>git commit  

Apply the inverse of the latest commit, undoing said commit. Safe if done locally. 
>git revert  

Move the HEAD pointer and the branch pointer to another point in time. Caution: you may unintentionally lose work. 
>git reset  

Add a remote repository to your local configuration:
>git remote add <remote_repo_name> <remote_repo_url>  

Push a local repository to your remote repository:
>git push -u <remote_repo_name> <local_branch_name>  
