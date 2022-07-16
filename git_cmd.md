文件状态
	- Untracked : 未跟踪
	- Unmodify : 文件已入库,未修改
	- Modified : 已修改
	- Staged : 暂存状态

生成公/私钥
	ssh-keygen -t ed25519 -C "your_email@example.com"


1. git init
	初始化git仓库
2. git clone [url]
	下载远程仓库到本地
3. git status [filename]
	查看[所有]文件状态
4. git add .
	添加所有文件到暂存区
5. git commit -m [msg]
	提交暂存区中的文件至本地
6. git push [arigin] main
	推送到远程仓库
7. git pull [origin] main
	
