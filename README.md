# git-assignment2

below commands are used for this assignments.

git clone https://github.com/Ramjogesh/git-assignment2.git
cd git-assignment2/
git pull origin main --allow-unrelated-histories
git branch -a
git checkout develop
touch develop.txt
git stash
git status
git add .
git status
git stash
git checkout feature1
touch new.txt
git status
git add .
git commit -m "added new file"
git checkout develop
git stash pop
