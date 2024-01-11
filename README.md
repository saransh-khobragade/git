# GIT COMMANDS

## Check status of git branch
```
git status
```

## Check how many branches are there
```
git branch
```

## Add changes for commit
```
git add FILEPATH
```

## Add all changes for commit
```
git add .
```

## Commiting your changes with message
```
git commit -m "MESSAGE"
```

## Take all changes from remote to local same branch
```
git pull
```

## Push all changes to remote from local same branch
```
git push
```

## Take all changes from any remote branch to local branch
```
git pull origin BRANCH_NAME
```

## Create new branch
```
git checkout -b BRANCHNAME
```

## Change branch
```
git checkout BRANCHNAME
```

## Delete new branch
```
git branch -d BRANCHNAME
```

## Get first commit
```
git rev-list --max-parents=0 HEAD
```

## Sqaush all commits to one and push to remote
```
git reset (first commit)
git commit -m "message"
git push -f
```
