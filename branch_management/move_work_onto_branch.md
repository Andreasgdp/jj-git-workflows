# [DRAFT] Move work onto a new branch

## Case
You start work on latest `origin/master`, you just make a commit directly on there, but then you want to branch out so you can make a PR for your changes. You want to move the commit you just made onto a new branch.

## git

1. git fetch
1. git switch master
1. make change and commit
1. git switch -b feature/<branch_name>

Done you can now make a PR for your changes back to `origin/master`.

## jj

1. `jj git fetch`
1. `jj new origin/master`
1. make change
1. `jj git push -c @`



