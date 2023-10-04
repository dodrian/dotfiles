# Git Commands

`git rebase -i origin/<branch>` - interactive rebase
`git stash` - save current working state
`git stash list` - list stashes
`git stash apply [stash@{n}]` - Apply stash [most recent or n]
`git checkout <branch/ref> -- <filename>` - get single file from branch and overwrite local
`git reset --hard <origin/branch-name>` - set local branch to origin (overwrites local)
`git checkout --patch <branch> <file>` - Merge file from another branch
	

## Cleaning local branches

`git remote prune origin` - remove remote branches that have been deleted
`git branch -vv | grep ': gone]' | awk '{print $1}' | xargs git branch -D` - remove local branches that are gone on remote
