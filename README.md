# Practice repository for working with Git 

## Commands Used

- git init: Create a new git repository
- git status: Compare working directory, staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show history (aka "log") of project commits
- git checkout: Switch branch and update reference to HEAD
- git mere: Merge changes from different branches

## Commit messages

Default editor is vim (this can be changed)
Or use 'git commit -m " Commit Messag"'

First line should be clear, accurate and concise
Use proper grammar and punctuation
Don't end with a '.'

For more advice, see https://chris.beams.io/posts/git-commit/

## Merging

Merging means to bring the changes from one branch into another.


- A fast forwardmerge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.
- An Automatic merge happens when the two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.
