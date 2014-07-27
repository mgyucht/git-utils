# git-utils

A selection of utilities for git that I think make my life better.

## subm-commit

This function, called as

    git subm-commit

with the same options as `git commit`, allows the user to make a commit in a submodule, then recursively adds the updated repo to the parent git repository and committing the changed submodule. This takes all the pain out of committing in submodules! This utility will stash any uncommited (both staged and unstaged) files in your parent repository before committing the subrepo with an identical commit message appended with the name of the repo.
