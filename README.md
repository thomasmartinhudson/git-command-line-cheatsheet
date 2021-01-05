# Git Command Line Cheat Sheet

## Contents

1. [Modifying Local Branch](#modifying-local-branch)
1. [Tags](#tags)
1. [Undo Changes](#undo-changes)

## Modifying Local Branch

Switch branch: `git checkout <branch-name>`

## Tags

Delete Tag locally: `git tag -d <tag-id>`

Delete Tag on origin: `git push origin :<tag-id>`

## Undo Changes

Remove added files in staging area: `git clean -fd`

List all commits: `git log`

Exit log: `q`

Revert local branch to commit: `git reset --hard <commit-id>`

Update origin master to commit: `git push --force origin <branch-name>`
