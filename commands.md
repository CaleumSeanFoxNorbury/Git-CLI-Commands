# Useful Git commands for development:

### Rebase

Rebase for the commit chain to be matched with the base branch. Doing this will seem like branches/features will be developed on the same branch and not seperately.

```
git fetch
git rebase origin/dev
```

### Locally pulling changes

loycally merging changes from one branch into current branch. This one on the local machine and not messing around doing this through github.

`git merge origin/dev`

### Create new branch

creates a new branch from dev or from any branch to replace dev.

```
git fetch
git checkout origin/dev
git checkout -b yourNewBranchName
```
