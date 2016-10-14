git config --global user.name "name"
git config --global user.email "my.email"

mkdir git_repository
cd git_repository
git init 格式化创建版本库

vim readme.txt
git add readme.txt 添加文件到缓存
git commit -m "add new file to git" 提交到仓库

git status 查看状态
git diff 对比查看修改

git log 查看提交记录
git log --pretty=oneline 查看提交记录，只显示id版本号

git reset --hard HEAD^  回退到上一个版本
git reset --hard HEAD^^ 回退到上上个版本
git reset --hard HEAD~5 回退到末尾第五个版本

git reset --hard 342454 回退到指定版本


git test 

git reflog 记录命令历史记录，如history
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

git rm listen.txt
git commit -m "remove listen.txt"
git log --pretty=oneline
git reset --hard HEAD^
git checkout -- listen.txt

git push -u origin master 
git push origin master

git remote add origin git@github.com:MrNiuYH/git_repository.git
git push -u origin master
git push origin master

git branch dev 创建分支
git checkout dev 切换分支

git checkout -b dev 创建并切换分支
git branch 查看当前分支

git merge dev 合并指定分支到主分支
git branch -d dev 删除分支

add git master
add test1

git log --pretty=oneline --graph

git merge --no-ff -m "--no-ff is no fast forward"
git log --pretty=oneline --graph
git status
git stash list

git stash

git stash apply     git stash drop
git stash pop
git stash list
git stash apply stash@{0}

git tag name
git tag -a name -m "name bescribe"
git tag      select * from tag


git tag
git tag -d v0.1

git push origin tagname
git push origin --tags

git tag -d v0.1 
git push origin :refs/tags/v0.1
