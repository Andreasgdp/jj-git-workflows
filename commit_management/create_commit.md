# Create a new commit/change

## git

With git you can create a new commit/change by:

1. Making changes to the files in your repository
1. Staging the changes you want to stage using `git add <file(s)>`
1. Committing the changes using `git commit -m "<commit message>"`

## jj

With `jj` you are by default already doing a "commit" or more specifically a change. In order to finalize/save the change you simply start a new one:

```bash
jj new
```

This will create a new commit with the changes you made in the previous commit.

NOTE: commits/changes are never final in `jj`. You can always go back and edit them, or even remove them if you want to with simple commands compared to git.
