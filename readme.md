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
  - git switch / checkout (branch-name)
  - git checkout -b (branch-name)
  - git switch -c (branch-name)
