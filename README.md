# test
test repo

# First test - creating a new remote github repo and merge with existing local repo
created to test changes with a new repository.
First test
- existing repo on local machine. No existing repo on github.
- create a new black project on github
- connect the the two

Issues
- needed to use a flag to allow merging of unrelated histories

Series of commands once the repositories are connected
- git checkout main 
- git merge main master --allow-unrelated-histories
- git push

# Second test - a branch has been removed locally but still exists on remote. Remove the branch on remote

- git push origin -d master
where [origin] is the restult on git remote and [master] is the branch on remote that you wish to delete
