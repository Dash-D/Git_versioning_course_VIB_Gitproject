# Dictionary of concepts

## Differentiating

- git: a software/tool to track changes in files and folders. 

- github: A navigator. A backup of your timeline/git repository.

## Meaningful message

- Why?

- How?

- Effects.

- Limitations.

## Conceptual area

1. Development area: the project folder.

2. Staging area: organize and add files before committing. 

3. Local Repo: .git file where git software is managing all the versions.

## Files to always include

- README.md: a description of the project, files, installations, etc

- .gitignore: list of files to ignore. They must not have been pushed.

## From local to remote

- ssh key: why it is important? It's a way to securely connect to a remote computer/server.

`ssh-keygen -t ed25519 -C "dan.dascenco@gmail.com"` 

- how to create a repo on Github: add the SSH key then open a remote connection ("bridge").

`git remote add origin https://github.com/Dash-D/Git_versioning_course_VIB_Gitproject.git`

- I should always sync the changes. Git Push will send changes to my collaborators and to my backup. Git Pull will sync my local repo with the remote one, allowing to incorporate changes by collaborators or made on another machine.

- HEAD: most recent commit. Can be moved in case of revert or reset.

## Branch

- Give it a new_name, make it meaningful.

- Alternative history of commits.

- Here I'm testing how Github deals with branches pushed without "stumps'.