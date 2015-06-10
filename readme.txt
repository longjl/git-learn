1、在线地址

git中文网站：
http://www.git-scm.com/

git简易指南：
http://www.bootcss.com/p/git-guide/

廖雪峰的官方网站：
http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/

github for windows：
https://help.github.com/articles/getting-started-with-github-for-windows/


2、git学习

windows下安装git：
http://msysgit.github.io/

配置用户名和邮箱：
$ git config --global user.name "your name"				// --global表示你这台机器上的所有git仓库都会使用这个配置
$ git config --global user.email "email@example.com"


创建版本库：
$ mkdir temp		//创建空目录
$ cd temp			//切换目录
$ pwd				//显示当前目录

$ git init          //初始化版本库
Initialized empty Git repository in d:/project/temp/.git/

添加文件到版本库:
$ add readme.txt
$ commit -m "add readme file"

查看文件状态：
$ git stauts

查看文件修改：
$ git diff

查看版本历史：
$ git log

回退版本：
$ git reset --hard b39ef...  //版本号没必要写全，前几位就可以了，Git会自动去找

查看git每一次命令：
$ git reflog

查看工作区和版本库里面最新版本的区别：
git diff HEAD -- readme.txt

丢弃工作区的修改(就是让这个文件回到最近一次git commit或git add时的状态)：
$ git checkout -- readme.txt  // --很重要，没有--，就变成了"创建一个新分支"的命令

把暂存区的修改撤销掉：
$ git reset HEAD reaeme.txt

删除文件：












