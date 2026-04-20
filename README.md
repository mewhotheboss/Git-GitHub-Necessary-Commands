## Initialize Git
To initialize a Git repository, run:
```
git init
```

## See the Origin
### List all remotes (with fetch/push URLs):
```
git remote -v
```
### See only the `origin` URL:
```
git remote get-url origin
```
### See detailed info about `origin`:
```
git remote show origin
```
### To start a branch with no previous commits (a fresh history):
```
git checkout --orphan <branch-name>
```
