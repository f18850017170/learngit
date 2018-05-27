1、git config --list //查看配置信息
2、git config --global user.name "your name" //--global 所有的Git仓库都会使用这个配置
3、git config --global user.email "your@email"//--global 所有的Git仓库都会使用这个配置

4、git init //将当前目录初始化为git repository
5、ls -ah查看.directory 隐藏目录

git add file.txt file2.txt 
git add file3.txt	//可以add 多个文件
git commit -m "提交的备注信息" // add的多个文件可以一次性提交

git status //查看当前repository 工作区和暂存区状态
git diff //查看修改的内容 工作目录working directory与 stage暂存区的比较

git reset --hard HEAD^ //HEAD 执行的是当前的版本 HEAD^ 则是上个版本 HEAD^^ 上上个版本 HEAD~n 指向n个版本前
git log //查看提交历史 commit 操作
git log --pretty=oneline //打印到同一行

git reflog //查看命令历史 所有的版本操作  包括commit 和reset 操作

git checkout -- file.txt //将工作区的文件恢复到 stage暂存区中的版本(暂存器无未commit内容，则为上一次commit内容，即当前分支版本内容)
git reset HEAD file.txt //撤销暂存器的修改，恢复未add之前，工作区的变更可以再次add

ssh-keygen -t rsa -C "your@email" //创建密钥对 ssh-keygen中间没有空格
