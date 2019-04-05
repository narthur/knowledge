# git

* [Git-cherry-pick](https://git-scm.com/docs/git-cherry-pick) \#article - “Apply the changes introduced by some existing commits”
  * [Applying git commits to working tree unadded?](https://stackoverflow.com/a/26618896/937377) \#article
    * git cherry-pick --no-commit 4..8
* [Git housekeeping tutorial: clean-up outdated branches in local and remote repositories](https://railsware.com/blog/2014/08/11/git-housekeeping-tutorial-clean-up-outdated-branches-in-local-and-remote-repositories/) \#article - “After working with branch per feature for a while any Git-repository becomes a mess of outdated and not finished branches. To deal with this issue, we need to clean-up three kinds of branches…”
* [Git: How to rebase your feature branch from one branch to another](https://makandracards.com/makandra/10173-git-how-to-rebase-your-feature-branch-from-one-branch-to-another) \#article
  * [How do I properly force a Git push?](https://stackoverflow.com/a/12610763/937377) \#article
* [GitKraken](https://www.gitkraken.com/) \#software - “The legendary Git GUI client for Windows, Mac and Linux”
* [GitUp](http://gitup.co/) \#software - “Work quickly, safely, and without headaches. The Git interface you've been missing all your life has finally arrived.”
* [Global Git ignore](https://stackoverflow.com/a/7335487/937377) \#article - git config --global core.excludesfile '~/.gitignore'
* [How can I reconcile detached HEAD with master/origin?](https://stackoverflow.com/questions/5772192/how-can-i-reconcile-detached-head-with-master-origin) \#article
  * git branch temp \# create a new branch based on your detached head
  * git checkout temp
  * git checkout master
  * git merge temp
  * git branch -d temp
* [How to copy commits from one branch to another?](https://stackoverflow.com/a/2474371) \#article
  * git cherry-pick &lt;SHA of commit to cherry-pick&gt;
* [How to undo the most recent commits in Git?](https://stackoverflow.com/questions/927358/how-to-undo-the-most-recent-commits-in-git) \#article
  * ![](https://lh4.googleusercontent.com/LUTg4c80Ya5a8wO8GORnV4CXXuCklGMwBviwz-0MKVIAxf2Fx21yIiqBBIw7LVuyIUDnqXIunEBULC7ctDjlagxfPXhCeg2jWdijkWex8OBsz_v_zpVqDhtDZrOz0INh2x7C6dfo)
* [How do I move an existing Git submodule within a Git repository?](https://stackoverflow.com/a/24767348/937377) \#article
  * git mv old/submod new/submod
* Make an empty commit, good for debugging CI
  * git commit --allow-empty -m "Empty commit to trigger post\_receive hooks"
* [so-fancy/diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - “Good-lookin' diffs. Actually… nah… The best-lookin' diffs. 🎉”
* [Quick Tip: Autocomplete Git Commands and Branch Names in Bash](http://code-worrier.com/blog/autocomplete-git/) \#article - “In bash in Mac OS X, you can use \[TAB\] to autocomplete file paths. Wouldn’t it be nice if you could do the same with git commands and branch names?”
* [Undo working copy modifications of one file in Git?](https://stackoverflow.com/a/692329/937377) \#article
  * git checkout -- file

