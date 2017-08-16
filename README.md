1.创建仓库步骤
	1.1 现在github官网上新建一个仓库(repository)，例如名字叫：momo
	1.2 在本地文件夹下启动git bush，将本地文件夹声明为一个git仓库输入命令：git init
	1.3 如果在github上没有创建readme的话，这时可以先创建一个readme.md 
		1.3.1 git add readme.md  -- 这是将readme添加到仓库类似一个缓冲区的地方，并没有真正的提交
		1.3.2 git commit -m ‘comment’ --将缓冲区的内容提交到本地仓库的版本库中
		1.3.3 git remote add origin https://github.com/kangruiwen/gitOperate.git  这个命令是添加远程仓库，具体我也没看明白呢，待明天看明白
		1.3.4 git push -u origin master 
	到这时为止一般都OK了，但是如果在远程仓库中有文件的存在，而本地第一次添加远程仓库后提交项目，1.3.4步骤中的参数-u 有时需要改为 -f 才能成功
	
 
 