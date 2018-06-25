/* First you have to goto Credential Manager --> windows Credential --> General Credential --> and remove the github Credential

$ cd ~/Desktop/

$ mkdir gitPracticalProject/

$ cd gitPracticalProject/

$ echo "# hello-world" >> README.md

$ git init

$ git config --global http.proxy 192.168.222.1:3128

$ git config --global user.name TharukaSiriwardena

$ git config --global user.email tharukasiriwardena27@gmail.com

$ git add README.md

git status

$ git commit -m "first commit"

$ git remote add origin https://github.com/TharukaSiriwardena/hello-world.git

$ git push -u origin master

/* ==========log in to your account ========= */

/* now check the git repository to updated or not */

/* adding a new branch with its tasks */
$ git checkout -b firstbranch

$ git branch

/* push a branch to github */
$ git push origin firstbranch


/* change the branch */
$ git checkout master
$ git checkout firstbranch


/* create pull request */
$ git pull origin master


/* undoing changes */
$ git revert 3cee036 <hash code>





