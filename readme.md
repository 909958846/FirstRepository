![](C:\Users\jamli\git\FirstRepository\git.png)
git廖雪峰教程
https://www.liaoxuefeng.com/wiki/896043488029600
访问远程服务器时需要采用ssh协议，也就是服务需要知道谁在访问，并在服务器上设置访问名单
在本地电脑获取令牌：也就是这台电脑的信息
ssh-keygen -t rsa -C "youremail@example.com"
在服务器设置访问名单：
点“Add SSH Key”，填上任意Title，在Key文本框里粘贴id_rsa.pub文件的内容

Git is a version control system.
Git is free software.

add git to rtt-studio.

git init				//把目录变成git仓库
git add readme.txt 			//添加文件到index
git commit -m "commit的comments"	//commit到本地Repository

在github添加一个Repository
git remote add origin git@github.com:909958846/FirstRepository.git	//把本地的仓库和远程（origin）的仓库关联
git push -u origin master		//第一次推送，将本地库的所有内容都推送到远程库上,并把本地的master分支和远程的master分支关联	


git add -A 			//添加所有变化到index,
git commit -m "修改了xxx"		//commit到本地Repository
git push origin master		//第二次推送，将本地库的所有内容都推送到远程库上

git add -A 			//添加所有变化到index, 
git add -u				//添加修改和删除的文件，不包括新文件
git add .				//添加新的文件和被修改的文件，不包括删除的文件





