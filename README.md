# Fulnn
common command

ssh-keygen -t rsa –C “vonhimloy@163.com”
ssh -T git@github.com

git remote add origin https://github.com/vonhimloy/Note.git

git push -u origin master
git push origin master

git pull

git checkout -b dev # 创建并切换分支 == git branch dev + git checkout dev

git branch  # 查看当前分支

git checkout master

git merge dev  # 合并分支到当前分支

查看分支：git branch

创建分支：git branch name

切换分支：git checkout name

创建+切换分支：git checkout –b name

合并某分支到当前分支：git merge name

删除分支：git branch –d name

git status
git log
git log --pretty=oneline
git reflog

git reset --haed HEAD^  /HEAD^^   /~100
git reset --hard [code]

123123
