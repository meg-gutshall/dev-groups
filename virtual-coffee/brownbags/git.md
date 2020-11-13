---
description: 11/13/20
---

# Git

> **Presenter:** Keith Dahlby  
> Creator of [up-for-grabs.net](https://up-for-grabs.net/)

## Local Workflow

git branch --move

git checkout -b branch-1

git checkout master -b &lt;branch-name&gt; --&gt; use master branch as the base of the new branch

git commit --allow-empty -m 'Commit message' --&gt; commit message with no code changes

git reset master --&gt; forcibly move head of current branch to master

git log master..HEAD --reverse --&gt; show all changes since master, adding the --online flag shows it as a summary \(alias above to git new\)

git merge is shuffling the deck of cards, git rebase is cutting the deck

git rebase branch-1 --onto master --&gt; take changes from branch-1 and move them onto the master branch

git log --graph --all --&gt; will show a graph of all branches

git commit -am --&gt; adds all files and commits with a message, but **will not** detect newly added files

git add -p --&gt; breaks things into _parts_ \(i.e. when I usually go to GitKraken\), almost always commit using this command

git add --intent-to-add . --&gt; allows you to add new files to be staged and manipulated by the -p flag

git commit --amend --&gt; change the previous commit

git revert HEAD --&gt; undo last commit

* Push as soon as you have something you would be sad to lose

git commit --fixup &lt;SHA or HEAD~4&gt; \(where 4 is the number of commits before HEAD\) --&gt; add a change to a previous commit; this won't disrupt the workflow of other contributors  
Adds "fixup!" to the commit message until you rebase it.

git rebase -i --&gt; edit the commit history _interactively_  
If you get a merge conflict message, fix it and then enter git rebase --continue to keep going

End up with **a nice, clean git history!!**

git reflog --&gt; shows everything you did step-by-step

Cardinal rule of git: If you have committed it, you can get it back.





