# ds1
Experiment 1: Create local repository and upload it to remote repository
$ gh auth status
You are not logged into any GitHub hosts. Run gh auth login to authenticate.
$gh auth login
$ git --version
git version 2.25.1
$ git config --global user.name "RAJESH T H"
$ git config --global user.name
RAJESH T H
$ git config --global user.email "rajesh@pestrust.edu.in"
$ git config --global user.email
rajesh@pestrust.edu.in
$ gh auth status
$ cd Project/
$ git init
$ git remote add origin https://github.com/RajeshPesitm/Calmdown.git
$ git remote -v
$ touch readme.md
# In the created file enter some text that comes to your mind
$ git add .
$ git commit -m "Your descriptive commit message"
$ git branch
$ git push origin master
$ git push origin master
Experiment 2: continuation of Experiment 1: Create Branch locally merge with local master and
push to remote maste
$ git checkout -b develop
$ code readme.md
$ git add .
$ git checkout master
$ git merge --no-ff develop
$ git push origin master
Experiment 3: continued: Make changes in remote master and pull it to local master
$ git branch
# Make changes in remote repository and pull to your local computer
$ git pull origin master:master
$ git checkout develop
Experiment 4: Make changes again in local master and make local branch to merge with local
master
$ git checkout develop
$ git merge --no-ff master
Experiment 5: Push Local Branch to remote
$ git push origin -u develop
$ git add .
$ git commit -m "Local Branch to remote branch"
$ git push origin develop
