初始化 git init
添加文件到Git仓库：
	1 git add <file>	//可以反复使用，添加多个文件
	2 git commit
查看工作区状态 git status
	git diff 查看修改内容
HEAD指向的版本就是当前版本，因此，Git允许我们在版本的历史之间穿梭，使用命令git reset --hard commit_id
git log 查看提交历史，以便确定要回退到哪个版本。
git reflog 查看命令历史，以便确定要回到未来的哪个版本。
删除文件 git rm

远程仓库
	创建ssh $ ssh-keygen -t rsa -C "youremail@example.com"
	添加文件到仓库 
	1 git remote add origin git@github.com:cnfanhua/TESTGIT.git	//github. TESTGIT是仓库名
	2 git push -u origin master
