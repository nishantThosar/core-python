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
