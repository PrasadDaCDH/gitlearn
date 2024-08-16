1>#To create a git repository locally
git init

2>#TO get status of the repository created to get information on the files.
git status

3>#To add a file into the repository so git can keep track of that file
git add filename

4>#To check what changes are made to the files that git is tracking
git diff

5>#to commit the changes to file in git and give it message as a version lable 
git commit -m "the mesage"

6>#TO SEE THE git logs and will also display the commits
git log

7>#To change the version to the privious or any commit you want
git reset --hard COmmit_number

8>#To remove file from tracking by git
git checkout filename

9>To share the file in github
git push -u orgin main

10>#to add the remote repository is needed to act as origin
git remote add origin "git URL"

11>#to push first you need to set the name and email for the git
git config --global user.email "useremailaddress"
git config --glober user.name "username"

12>#you need PAT from github to push the repo's to chace it use
git config --global credential.helper cache/store (store for permanent)

