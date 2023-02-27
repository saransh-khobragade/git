# GIT COMMANDS


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