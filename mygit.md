### 常用的command
git clone（这样clone来的库直接就相关联了）  （如何解除关联）

[添加远程库](https://www.liaoxuefeng.com/wiki/896043488029600/898732864121440)
将本地的文件夹/项目仓库。推送到远程（远程新建了一个空的仓库） git remote add origin （项目ssh链接）  
添加远程库之后就可以git push -u origin master远程库的git默认名字就是origin。（这是推送的master分支，当然可以推送分支，-u参数表示第一次，建立链接）  

[克隆一个仓库](https://www.liaoxuefeng.com/wiki/896043488029600/898732792973664)从远程端clone这样默认的就是建立过连接的（不用git push -u了）

本地初始化一个仓库（在工作目录，要空的啊）  首先git init（就会生成.git文件，这里有版本控制信息）  

pull：就是拉取（from remote） git pull（从远程获取最新版并且merge到本地，这个时候可能会发生异常）  
push：译为推送（从本地推送）

git add ‘filename’  
git commit -m “info”  
在添加一个文件夹时要使用add dir/  
修改（添加了）一个文件要用git add 命令  然后commit  
然而如果你想删除某个文件（你可以
### 分支管理&冲突


### 教程
[git简明教程](http://rogerdudler.github.io/git-guide/index.zh.html
)
