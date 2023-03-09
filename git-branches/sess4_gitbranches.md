Here is a list of all the commands needed for wirking with git branches

# command functionality

git switch -c <branchname> create a new branch and switch to it
git switch <branchname> switch branches
git branch list your branches
git branch -a list all branches (local and remote)
git branch -d <branchname> delete a branch

# General information about working with branches

- allows developers to independently work on different features on the same project at the same time
- each branch has to be reviewed by one ore more developers to be checked for mistakes or for improvement advise
- after approval, all commits of the new branch will be merged to the main branch of the project
- after merging branch and main, the main on your pc has to be updated by making a pull request towards the remote main branch
