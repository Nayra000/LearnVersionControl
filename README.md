To remove branches locally
git branch -d dev 
git branch -d test

****************************
To remove branches remotely
git push origin --delete test
git push origin --delete dev

***************************
To  checkout another branch without commit 
changes
git stach
git checkout <branch name>
git stach pop
