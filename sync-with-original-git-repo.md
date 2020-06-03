- fork the original git, `git submodule add theforked`
- git pull to local, modify the forked.
- sync with upstream, with git, 
    - `git remote add upstream original-git-url`
    - `git fetch upstream`.
    - `git merge upstream/master`, fix conflicts.


`git pull` is like `git fetch` + `git merge`.
