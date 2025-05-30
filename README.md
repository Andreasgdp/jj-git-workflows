# `jj` as a replacement for `git`
This repo is an investigation in the different workflows I currently use git for and how they can be replaced with `jj`. The goal is to find out if `jj` can be used as a drop-in replacement for `git` in my daily workflow as well as to find out if there are any workflows that `jj` can improve upon. 

## TODO
- [x] Create a repo for testing
- [x] Make TODO for advanced Git usages
- [ ] Walk through jj equivalent for Git usages
- [ ] Explore unique jj features

## Use Cases
### Branch Management
- [ ] [Start work on branch convert to new branch](branch_management/move_work_onto_branch.md) - e.g. new commit on `master` branch -> feature/`<branch_name>` branch with master base + new commit
- [ ] [Do stacked branches](branch_management/stacked_branches.md) - working on multiple branches at once to be merged chronologically
- [ ] [Continue work on colleague's branch](branch_management/colleague_branch.md)
- [ ] [Working with multiple long-lived branches](branch_management/multiple_branches.md) e.g. `master`, `staging`, `production`

### Commit Management
- [x] [Create a new commit/change](commit_management/create_commit.md)
- [ ] [Revert commit](commit_management/revert_commit.md)
- [ ] [Undoing changes](commit_management/undo_changes.md)
- [ ] [Reset changes](commit_management/reset_changes.md) - e.g. `git reset --hard origin/master`

### Remote Operations
- [ ] [Push changes to a remote repo](remote_operations/push_changes.md)
- [ ] [Pull changes from a remote repo](remote_operations/pull_changes.md)
- [ ] [Get latest changes from target branch](remote_operations/get_latest_changes.md) - e.g. `master` or `staging` to `feature` branch
- [ ] [PRs](remote_operations/pull_requests.md) - how to create a PR for a branch in `jj` and how to review a PR

### Change Management
- [ ] [Cherry-pick changes from one branch to another](change_management/cherry_pick.md)
- [ ] [Stash changes](change_management/stash_changes.md) - when switching tasks, how to deal with uncommitted/unfinished changes

### Viewing and Analysis
- [ ] [View commit differences](viewing_analysis/view_commit_differences.md)
- [ ] [View commit details](viewing_analysis/view_commit_details.md)
- [ ] [View commit graph](viewing_analysis/view_commit_graph.md)
- [ ] [View commit blame](viewing_analysis/view_commit_blame.md)

## `jj` specific features
- [ ] ???

## What is `jj` ([Jujutsu](https://github.com/jj-vcs/jj))?
`jj` is a new version control system that is designed to be a drop-in replacement for `git`. It is built on top of the same concepts as `git`, but it is designed to be more user-friendly and to have a more intuitive command set. It is also designed to be more efficient and to have better performance than `git`.

>> Jujutsu is a powerful version control system for software projects. You use it to get a copy of your code, track changes to the code, and finally publish those changes for others to see and use. It is designed from the ground up to be easy to use—whether you're new or experienced, working on brand new projects alone, or large scale software projects with large histories and teams.

>> Jujutsu is unlike most other systems, because internally it abstracts the user interface and version control algorithms from the storage systems used to serve your content. This allows it to serve as a VCS with many possible physical backends, that may have their own data or networking models—like Mercurial or Breezy, or hybrid systems like Google's cloud-based design, Piper/CitC.

>> Today, we use Git repositories as a storage layer to serve and track content, making it compatible with many of your favorite Git-based tools, right now! All core developers use Jujutsu to develop Jujutsu, right here on GitHub. But it should hopefully work with your favorite Git forges, too.

## Why `jj`?
- `jj` is designed to be a drop-in replacement for `git`, so it should be easy to switch to.
- `jj` is designed to be more user-friendly and to have a more intuitive command set.
- `jj` is designed with a different mindset to making changes, which I'm keen to explore.

## What is `jj` not?
`jj` is not a replacement for `git` in all cases. It is designed to be a drop-in replacement for `git`, but it is not designed to be a replacement for all of the features of `git`. It is designed to be a replacement for the most common use cases of `git`, but it is not designed to be a replacement for all of the advanced features of `git`.

## How to use this repo
This repo is designed to be a reference for the different workflows I currently use git for and how they can be replaced with `jj`. It is not designed to be a tutorial on how to use `jj`, but it is designed to be a reference for the different workflows I currently use git (and working in a team using git and PRs for repositories) for and how they can be replaced with `jj`.

## How to contribute
If you have any suggestions for workflows that you think would be useful to add to this repo, please feel free to open an issue or a pull request. I am always looking for ways to improve this repo and to make it more useful for others.

## License
This repo is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
