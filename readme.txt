<This is a test text>
Git is a version control system.
Git is free software.

帮助文档：
<自报家门>
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

<创建版本库 repository>
$ mkdir （目录名称）
$ cd（目录名称）	//打开目录
$ pwd	//显示当前目录

$ git init	//目录变为Git管理仓库

<添加文件>
！！文件需在仓库目录下！！
$ git add （文件名称）	//添加文件，可反复多次使用，添加多个文件
$ git commit -m "（添加说明）"	//添加本次提交说明

<文件查看>
$ git status	//查看仓库当前状态
$ git diff	//查看修改内容

<版本回溯>
$ git log	//查看修改历史
$ git log --pretty=oneline	//功能同上，简化显示
$ git reset --hard HEAD^	//回到上一个版本 其中HEAD^上个版本 HEAD^^上上个版本 HEAD~n 上n个版本
$ git reset --hard （commit id版本号）	//回溯到commit id所对应版本
$ git reflog	//查看命令历史，也可找到commit id
