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

- # _Git and Github_

  - git clone (repo-url)
  - git remote -v // check remote branches
  - git remote add (remote-repo-name) (url)
  - git push origin (remote-branch-name)
  - git push -u origin (remote-branch-name) // set upstream
  - git remote rename (old-remote-repo-name) (new-remote-repo-name)
  - git remote remove (remote-repo-name)
  - git branch -r // check remote tracking branch

- # _Open source contribution Commands and pull request_

  - git fetch (remote-repo-name)
  - git fetch (remote-repo-name) (branch-name) // fetch changes of a particular branch but not integrate them to working directory
  - git pull // shorter syntax
  - git pull (remote-repo-name) (branch-name) // pull changes of a particular branch into working directory.
  - Forking and clone
    - Used for open source collaboration. Steps:
      - fork and clone the repository
      - Also set a remote branch "upstream" of the original repository to fetch latest changes and our repo to push changes to.

- # _Rebasing_

  - git rebase (master/main) // alternative to merging

- # _Tags_
  - git tag // list all Tags
  - git tag -l "(name/regex)" lists all tags containing name or whatever was specified in brackets
  - git tag (tag-name) // create tag
  - git tag -a (tag-name) // creates anotated tags
  - git show (tag-name) // shows the creator and more details of tags
  - git tag (tag-name) (commit-hash/HEAD~{1 to so on}) // tag aparticular commit
  - git tag -d (tagname) // delete tag
  - git push --tags // push all tags to a remote repo (by default tags are not pushed to remote repository)
