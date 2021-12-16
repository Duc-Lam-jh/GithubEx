## Answer 1
We should create new branches for features off of production branch. Because the master branch is for testing and should only contain executable codes that are finished.
We use the production branch to merge the new features and when that particular version of the branch is executable and considered finished, we merge it into master for later testing.
1. git checkout production 
2. git pull
3. git branch feature
4. git checkout feature

## Answer 2
We will have to stash our changes on our current branch, then go to the bugged branch, pull it and start resolving the bug. 
1. git stash save -u "comebacklater"
2. git checkout feature
3. git pull

## Answer 3
__If the merge and the latest commit has already been pushed__
__If the merge and the latest commit has not been pushed__