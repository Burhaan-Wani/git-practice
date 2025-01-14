# Git Learning

- _what is git_
- _who uses git_
- _History of git_
- _installation of git on windows_

## Basics of Git

- # _Configuring the git_

  - git config --global user.name "<name>"
  - git config --global user.email "<emailId>"

- # _Basic commands_

  - git init // initialize a git repo
  - git status // check if git is initialized in a folder or not
  - git add <fileName> / git add . // stage a single change or all files
  - git commit -m "<your-message>" // save changes
  - git log / git log --oneline // check commits
  - git commit --amend // add changes to the previous commit

- # _Branching in git_

  - git branch // list branches
  - git branch (branch-name) // create a new branch
  - git switch / checkout (branch-name) switch to different branch
  - git checkout -b (branch-name) create as well as switch to different branch
  - git switch -c (branch-name) same as the above commands
  - git branch -D (branch-name) // delete a branch
  - git branch -m (branch-name) // change branch name
  - git merge (branch-name) // merge two branches
  - git diff
  - git diff HEAD
  - git diff (commit1)..(commit2)
  - git diff --staged / --cached

- # _Staching in git_

  - git stash
  - git stash pop
  - git stash apply
  - git stash apply stash@{stash_id}
  - git stash drop stash@{stash_id}
  - git stash list // List all stashes
