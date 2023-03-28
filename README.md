# Webserver

# git 命令
1. git clone //需要克隆的仓库地址
2. git status //进入到克隆的项目文件夹下，执行可以看到修改了什么东西
3. git add README.md
```C++
kiki@kiki:~$ git clone https://github.com/KIKI9731/Webserver.git
//这里执行了克隆
正克隆到 'Webserver'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
接收对象中: 100% (3/3), 完成.
//进入克隆的文件夹下，并修改了README.md文件
kiki@kiki:~$ cd Webserver/
kiki@kiki:~/Webserver$ git status
位于分支 main
您的分支与上游分支 'origin/main' 一致。

尚未暂存以备提交的变更：
  （使用 "git add <文件>..." 更新要提交的内容）
  （使用 "git restore <文件>..." 丢弃工作区的改动）
	修改：     README.md

修改尚未加入提交（使用 "git add" 和/或 "git commit -a"）
```
