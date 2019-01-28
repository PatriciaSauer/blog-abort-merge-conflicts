# Aborting Merge Conflicts

This is a small repository which produces a merge conflict when merging branchA into branchB or vice versa. 
This repository establishes a save environment to try out git commands to abort a merge. 

## Usage

You can clone the repository, checkout branchA or branchB, and then merge the other branch into the one you checked out. 
A merge conflict will occur. You can abort the merge by trying out both git commands I mentioned in my blog post about
[how to abort a merge](http://patricia-sauer.com/git-how-to-abort-a-merge/): `git reset --merge` and `git merge --abort`.