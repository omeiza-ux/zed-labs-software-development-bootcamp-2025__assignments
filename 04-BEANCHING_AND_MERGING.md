# NOTES ON BRANCHING AND MERGING

1. Branching

- A branch is like a separate line of development in Git.

- The default branch is usually main or master.

- Developers create branches to work on new features, bug fixes, or experiments without affecting the main codebase.

2.  Merging

- Merging means combining changes from one branch into another.

- Typically, you merge a feature branch into main after the work is tested.

- There are different merge strategies:

- Fast-forward merge → simply moves the pointer forward if no conflict.

- Three-way merge → creates a new merge commit if histories have diverged.

## BASH COMMAND FOR BRANCHING 
### Create a new branch
git branch branch-name

### Switch to a branch
git checkout branch-name

### Create and switch to a new branch
git checkout -b branch-name

### List all branches
git branch

### Delete a branch (local)
git branch -d branch-name


## BASH COMMAND FOR MERGING
### Merge a branch into the current branch
git merge branch-name

### Abort a merge in progress
git merge --abort.

