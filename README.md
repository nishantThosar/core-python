# CDAC-python
This is first library officially made during CDAC
GIT = Version control system (DVCS= distributed version control sys)
People working on different systems for a collabrative project all can have copy of this file on local machine but the code resides on github repo.
Once one dev completed and has pushed on the repo & after that another dev pusheshes some file again on the same repo, the git will deny the push it will say that there are some changes on the repo & need to sync with yor sys.
Currently GITHub is owned by Mucrosoft no more open source.
By default Main branch is created.
We can merge the branches to main after testting.
Gitlab is an micro verson of github. used by many startups.

SSH generating key (pki (public private infra))
1) run command "ssh-keygen"
2) go to home/.ssh "~/.ssh"
3) cat id_rsa.pub
4) go to profile->setting->SSH & GPG Keys->New SSH Key->Insert Title & key
5) git config --global user.email <github email>
6) git config --global user.name <github username>
7) conform with command "git config --list"

GIT cloning

1)Go to repo

2)Copy the ssh by clicking "code" (green button)

3)Now go to the file where you want to clone the git repo

4)Open terminal at that path and type "git clone ssh_that_you_copied"

5)Now the repo will be copied to your local maching at that path in which you opend the terminal.

To list the branch of GIT type "git branch"
To make a new branch "git checkout -b branch_name" //This will also switch to a new branch
To get the changes of file "git status"

Commands to push the files on GITHub
1)
