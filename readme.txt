git config --list
git config --global user.name "your name"
git config --global user.email "your@email"
git init

git add file.txt file2.txt 
git add file3.txt	//可以add 多个文件
git commit -m "提交的备注信息" // add的多个文件可以一次性提交

git status //查看 repository工作区状态

git log
git log --pretty=oneling
git reset --hard HEAD^^ 
git reset --hard HEAD~n
git reflog
git reset --hard eebc