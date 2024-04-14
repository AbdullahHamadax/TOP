Version: Vietnamese
==========================

### Git

**Git** is the most popular Distributed Version Control System (DVCS) system today. Git provides a separate repository containing the entire change history for each programmer.

The functions of VCS:

- Save the history of versions of any changes to the project. Helps review changes or revert them later.
- Facilitate sharing code.

Benefits of git in addition to the general benefits of VCS:

- Ensure no conflicts when multiple programmers work simultaneously.
- Easy to use, fast, lightweight, and very secure.
- Easily combine branches, which can make team coding workflows much simpler.
- Easy product deployment.

### Some basic commands

- `git config` set user name and email
- `git init` initialize a repository of a project. Use this command in the project's root directory.
- `git clone` clone a repo from a remote source
- `git status` view the status of all working files
- `git add <file name>` add changes to the stage
- `git commit -m "message"` save a snapshot and the changed files must be in the stage. Each commit will save changes to the code, the committer, and the committer's message. `git commit --amend # start $EDITOR to edit the message` `git commit --amend -m "New message" # set the new message directly`
- `git push <remote> <branch>` push changes to the remote.
- `git branch` list branches.
- `git checkout` switch to another branch.
- `git stash` save changes but not ready to commit.
- `git merge <branch to merge>` merge 2 branches.
- `git reset HEAD <file name>` remove the file from the stage to avoid committing it. `git reset HEAD~2 # undo last two commits, keep changes`

### Tools, courses and cheatsheets

- [Learn git](https://learngitbranching.js.org/)

- [Tools search git command](https://gitexplorer.com/)

- [Interactive Git cheatsheet](https://gitsheet.wtf)

- [Git cheatsheet](https://www.reddit.com/media?url=https%3A%2F%2Fi.redd.it%2F8341g68g1v7y.png)
