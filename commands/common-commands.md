## My most commonly used git commands

### git clone
    * [git clone docs](https://git-scm.com/docs/git-clone)
    * use - will clone a remote repo into a local directory
    * ex. `git clone https://github.com/hardimanhk/learning-overview.git`
    * good to know:
        * `git pull` without arguments will update all the remote-tracking branches and then merge the remote master branch into the current master branch

### git checkout
    * [git checkout docs](https://git-scm.com/docs/git-checkout)
    * uses: 
        * can switch active branches
        * with the -b argument can create a new branch and switch to that branch as the active branch
        * when provided a file name it can effectively undo any local changes made to that file since the last commit
    * ex.
        * `git checkout other-branch`
        * `git checkout -b new-branch`
        * `git checkout -- file.js`
    * good to know:
        * git checkout can be used to view previous commits in the git history, this causes a state called "detached head" which means what you are viewing and working on is in a untrackable state (not on a branch) - if you were to make changes and then checkout a branch there would be no way to reference the changes you made