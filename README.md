1 - We should create new branches for features off of production branch. Because the master branch is for testing and should only contain executable codes that are finished.
We use the production branch to merge the new features and when that particular version of the branch is executable and considered finished, we merge it into master for later testing.

//go to production branch \n
git checkout production \n
//pull the latest production branch
git pull
//create the new branch
git branch feature
//go to new branch
git checkout feature

2 - We will have to stash our changes on our current branch, then go to the bugged branch, pull it and start resolving the bug. 