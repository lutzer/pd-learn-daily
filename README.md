# pd-submodules
=======
# pd-submodules

## How to add this as a subtree to other repositories

* add subtree in directory sp: `git subtree add --prefix sp https://github.com/lutzer/pd-submodules.git master --squash`
* add remote: `git remote add sp https://github.com/lutzer/pd-submodules.git`
* pull changes from subtree with: `git subtree pull --prefix=sp sp master`
* after commit add changes to subtree with: `git subtree push --prefix=sp sp master`
