git config --global user.name "name"
git config --global user.email "my.email"

mkdir git_repository
cd git_repository
git init

vim readme.txt
git add readme.txt
git commit -m "add new file to git"

git status
git diff

git log
git log --pretty=oneline

git reset --hard HEAD^
git reset --hard HEAD^^
git reset --hard HEAD~5

git reset --hard 342454


git test

git reflog
git reset --hard 34245

git add to stage
git commit to master
touch newfile

git add one line

git add two line
git add two line

git diff HEAD -- readme.txt
git checkout -- readme.txt
git reset HEAD readme.txt && git checkout -- readme.txt
