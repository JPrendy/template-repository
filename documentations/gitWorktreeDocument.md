# Git Worktree Documentation

## Description

The following documentation outlines how to use Git Worktree.

## Git Worktree

The following outlines how to `git worktree` that allows you look at another branches contents without needing to checkout to that branch. If you type `git worktree` in your terminal, you will see a list of commands you can use.

So, let's say we want to look at the contents of a branch called `test/labels`. we would do the following of either

1). `git worktree add worktreeBranch test/labels`

This will add the contents of the branch to a folder called `worktreeBranch` to your current folder.

or

2). `git worktree add ../worktreeBranch test/labels`

This will add the contents of the branch to a folder called `worktreeBranch` to your current folder but moved up by one directory. There may be cases this may be more useful as you can open this in a new window, which will make it easier to differentiate the two branches.

To list your current worktree's, use the following command `git worktree list`.

To remove any old worktrees you no longer need use the following command to git rid of the example we used, which was `worktreeBranch`.

`git worktree remove worktreeBranch`. 

If you are still having issues, refer to the following video [link](https://www.youtube.com/watch?v=cRunWRC8ye0).