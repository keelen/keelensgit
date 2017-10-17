<This is a test message>

帮助文档：
<自报家门>
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

<创建版本库 repository>
$ mkdir （目录名称）	//创建目录
$ cd（目录名称）	//打开目录
$ cat （文件名称）	//打开文件
$ pwd	//显示当前目录
$ git init	//目录变为Git管理仓库

<添加文件>
！！文件需在仓库目录下！！
$ git add （文件名称）	//添加文件至暂存区（stage），可反复多次使用，添加多个文件
$ git commit -m "（添加说明）"	//将暂存区所有修改提交到分支，同时必须添加本次提交说明

<文件查看>
$ git status	//查看暂存区当前状态
$ git diff	（文件名称）//查看修改内容

<版本库回退>
$ git log	//查看修改历史
$ git log --pretty=oneline	//功能同上，简化显示
$ git reset --hard HEAD^	//回到上一个版本 其中HEAD^上个版本 HEAD^^上上个版本 HEAD~n 上n个版本
$ git reset --hard （commit id版本号）	//回退到commit id所对应版本
$ git reflog	//查看命令历史，也可找到commit id

<撤销修改>
$ git checkout -- （文件名称）	//用版本库版本替换工作区版本
$ git reset HEAD （文件名称）	//回退暂存区修改至工作区

<删除文件>
$ git rm （文件名称）	//删除文件

<添加远程库>
$ git remote add origin （github网址）	//关联github远程库
$ git push origin master	//master分支最新修改推至github（$ git push -u origin master 第一次推送）
