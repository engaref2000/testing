Git and GitHub

main video is :
https://www.youtube.com/watch?v=rPL_pKNT-XI

---

                    setp1

---

install Git
download for windows is :https://git-scm.com/downloads

---

                    setp2

---

some Command use by github
1- git init .
is the first command tell the git I want this folder to be trac
2- git add [file name ] , or use git add --all
3- git status
to know what the status there
4- git log
show information about directory
5- git branch -M master
to change the branch you work on it

6 - git remote add origin https://gethub.com/[your name ]/[repository name ]
exp: git remote add origin https://github.com/engaref2000/mir.git

https://github.com/engaref2000/connection-github-with-git.git

git push -u origin main

---

                    setp3

---

Generating a new SSH key and adding it to the ssh-agent
web refrence :
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

-first go to git bash

1-
$ ssh-keygen -t ed25519 -C "engaref2000@gmail.com"

2-

# start the ssh-agent in the background

$ eval "$(ssh-agent -s)"

> Agent pid 59566

$ ssh-add ~/.ssh/id_ed25519

---

                    setp4

---

gpg GNU Privacy Guard

floww this web sit to gpg
https://docs.github.com/en/authentication/managing-commit-signature-verification/about-commit-signature-verification

---

                    setp5

---

create new repository on gitHub git the name of the repository from ssh
user this command
git remote add <name> <url>
exp:
git remote add origin git@github.com:engaref2000/testing.git

to push your code you use this command

git push -u origin HEAD
