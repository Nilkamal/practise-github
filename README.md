# practice-github
This repository is to practice github workflow

# Feature based branch workflow

* Sync with master
git checkout master
git fetch origin
git reset --hard origin/master

* Create new branch
git checkout -b new-feature

* Edit, stage, commit changes 
git add .
git commit -m "Message here"

* Push branch to central repository and set as tracking branch
git push -u origin new-feature


