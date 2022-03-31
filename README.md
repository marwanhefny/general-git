# General GIT commands
## GIT Squash
```
git log --oneline 
```
then know how many commits you want to remove, lets assume we have 5 commits then
```
git rebase -i Head~5
```
then leave the first one as pick then the reset should be 's' then
```
wq #without !
```
then
```
git push origin [branch] -f
```
