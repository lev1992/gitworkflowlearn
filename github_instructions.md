## create branch named "develop" from main:

git checkout -b develop
git push -u origin develop

## chenge branch 
git switch 'branch name'
git checkout 'branch name'


## merge into main 
git checkout main
git merge hotfix/1.2.1
git tag 1.2.1

## create pull request
gh pr create

## sync remove branch to locally 
git fetch --prune

## delete branch locally 
git branch -d 'branch/login'

## Do not save changes
git restore index.md