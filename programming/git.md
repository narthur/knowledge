# git

## Snippets

Set your commit email address in Git \([source](https://help.github.com/en/articles/setting-your-commit-email-address-in-git)\):

```bash
$ git config --global user.email "email@example.com"
```

Undo your most recent commit \([source](https://stackoverflow.com/a/927386/937377)\):

```bash
$ git commit -m "Something terribly misguided"
$ git reset HEAD~
<< edit files as necessary >>
$ git add ...
$ git commit -c ORIG_HEAD
```

Move an existing submodule within the same git repository \([source](https://stackoverflow.com/a/24767348/937377)\):

```bash
git mv old/submod new/submod
```

Resolve a detached head \([source](https://stackoverflow.com/questions/5772192/how-can-i-reconcile-detached-head-with-master-origin)\):

```bash
git branch temp # base new branch on detached head
git checkout master
git merge temp
git branch -d temp
```

Make an empty commit \(good for debugging CI\):

```bash
git commit --allow-empty -m "Empty commit to trigger post_receive hooks"
```

Initialize all submodules recursively \([source](https://stackoverflow.com/a/10168693/937377)\):

```bash
git submodule update --init --recursive
```

## Links

* [Conventional Commits](https://www.conventionalcommits.org/) - "A specification for adding human and machine readable meaning to commit messages"
* [Git-cherry-pick](https://git-scm.com/docs/git-cherry-pick) \#article - “Apply the changes introduced by some existing commits”
  * [Applying git commits to working tree unadded?](https://stackoverflow.com/a/26618896/937377) \#article
    * git cherry-pick --no-commit 4..8
* [Git housekeeping tutorial: clean-up outdated branches in local and remote repositories](https://railsware.com/blog/2014/08/11/git-housekeeping-tutorial-clean-up-outdated-branches-in-local-and-remote-repositories/) \#article - “After working with branch per feature for a while any Git-repository becomes a mess of outdated and not finished branches. To deal with this issue, we need to clean-up three kinds of branches…”
* [Git: How to rebase your feature branch from one branch to another](https://makandracards.com/makandra/10173-git-how-to-rebase-your-feature-branch-from-one-branch-to-another) \#article
  * [How do I properly force a Git push?](https://stackoverflow.com/a/12610763/937377) \#article
* [GitKraken](https://www.gitkraken.com/) \#software - “The legendary Git GUI client for Windows, Mac and Linux”
* [GitUp](http://gitup.co/) \#software - “Work quickly, safely, and without headaches. The Git interface you've been missing all your life has finally arrived.”
* [Global Git ignore](https://stackoverflow.com/a/7335487/937377) \#article - git config --global core.excludesfile '~/.gitignore'
* [How to copy commits from one branch to another?](https://stackoverflow.com/a/2474371) \#article
  * git cherry-pick &lt;SHA of commit to cherry-pick&gt;
* [Quick Tip: Autocomplete Git Commands and Branch Names in Bash](http://code-worrier.com/blog/autocomplete-git/) \#article - “In bash in Mac OS X, you can use \[TAB\] to autocomplete file paths. Wouldn’t it be nice if you could do the same with git commands and branch names?”
* [so-fancy/diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - “Good-lookin' diffs. Actually… nah… The best-lookin' diffs. 🎉”
* [Undo working copy modifications of one file in Git?](https://stackoverflow.com/a/692329/937377) \#article
  * git checkout -- file

