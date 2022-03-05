Git is a version control system.
Git is free software.

add git to rtt-studio.

git init				//把目录变成git仓库
git add readme.txt 			//添加文件到index
git commit -m "commit的comments"	//commit到本地Repository

在github添加一个Repository
git remote add origin git@github.com:909958846/FirstRepository.git	//把本地的仓库和远程（origin）的仓库关联
git push -u origin master		//第一次推送，将本地库的所有内容都推送到远程库上,并把本地的master分支和远程的master分支关联	//第二次推送

git push origin master		//将本地库的所有内容都推送到远程库上

git add -A 			//添加所有变化到index, 
git add -u				//添加修改和删除的文件，不包括新文件
git add .				//添加新的文件和被修改的文件，不包括删除的文件





