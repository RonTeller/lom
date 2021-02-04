# lom - minimal recommended interface for git

## recommended workflows

* `git clone` ~ `git fetch`
  *
* `git push`
  * remote must be epxlicit
* `git branch`
  * local branches have no upstream
* `git grep`
* integrate built in `sed` command (add alias in .gitconfig like `sed = !sh -c 'git grep --null --full-name --name-only --perl-regexp -e \"$1\" | xargs -0 perl -i -p -e \"s/$1/$2/g\"' -`)
