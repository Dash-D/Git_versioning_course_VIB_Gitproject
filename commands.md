# Commands

## Completing file names

`TAB`

Help

`--help` after any command

Checking if files were commited

`git status`

Adding to staging area

`git add <file_name_1> <file_name_2>`

Adding to local repository

`git commit -m "Your commit message"`

See history

`git log`

`git log -n`

`git log --abbrev-commit`

`git log --oneline`

`git log --name-only`

Compare differences

`git diff <old> <new>` *order matters*

`git show <old> <new>`

Connect to a remote repo

`ssh-keygen -t ed25519 -C "dan.dascenco@gmail.com"` 

`git remote add origin https://github.com/Dash-D/Git_versioning_course_VIB_Gitproject.git`

`git remote add origin git@github.com/Dash-D/Git_versioning_course_VIB_Gitproject.git`

Sync commands

`git push`

`git pull`

From remote to local

`git clone`

Recover to a previous state

`git reset` *more dangerous, you cna delete commits by mistake*

`git revert` *safe, doesn't delete anything*

Rewrite the last commit message

`git commit -amend`

Delete the bridge (to switch from https to ssh for instance)

`git remote` *lists the name, usually "origin"*

`git remote remove <name>`

Branching

`git branch <name>` creates anew branch

`git checkout <branch_name>` to select which branch I work on

`git branch --list` to get a list of all branches

`git branch -v -v -a` easy wait to check the status of all branches.