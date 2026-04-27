# Dictionary of concepts

## Differentiating

- git: a software/tool to track changes in files and folders. 

- github: A navigator. A backup of your timeline/git repository.

## Conceptual area

1. Development area: the project folder.

2. Staging area: organize and add files before committing. 

3. Local Repo: .git file where git software is managing all the versions.

## From local to remote

- ssh key: why it is important? It's a way to securely connect to a remote computer/server.

`ssh-keygen -t ed25519 -C "dan.dascecno@gmail.com"` *VIB password*

- how to create a repo on Github: add the SSH key then open a remote connection ("bridge").

`git remote add origin https://github.com/Dash-D/Git_versioning_course_VIB_Gitproject.git`

- I should always sync the changes. Git Push will send changes to my collaborators and to my backup. Git Pull will sync my local repo with the remote one, allowing to incorporate changes by collaborators or made on another machine.
