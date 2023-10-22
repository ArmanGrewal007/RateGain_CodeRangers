# RateGain_CodeRangers

STEPS for first commit --> 
1. Initialize this repo with README.md
2. Go to a folder in your desktop, and `git init`
3. `git remote add origin https://github.com/ArmanGrewal007/RateGain_CodeRangers/`
4. You can see all the branches using --> `git branch`. You'll notice there is no master branch here (but github desktop has that branch 🤔🤔 why so?)
5. Create a branch master --> `git checkout -b master`
6. Pull the already existing changes (README.md) --> `git pull origin master`
7. Add the files you want to push manually
8. Add them to staging --> `git add .`
9. See which files are added --> `git status`
10. Make a commit "added problem statements" --> `git commit -m "added problem statements`
11. Push upstream --> `git push -u origin master`

STEPS for further commits --> 
1. Check which branch you are on --> `git branch`
2. If you are not on master, go there --> `git checkout master`
3. Pull any changes that are there in remote repo, but not in your own repo (maybe added by another collaborator) --> `git pull origin master`
4. Add the files and repeat steps --> add + commit + push
