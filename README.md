# Common-basic-commands-of-Git
# Git的常用基本命令

1.初始化仓库

git init

2.克隆

git clone 仓库地址

3.查看是否修改文件

git status

4.查看本地分支

git branch

5.查看远程所有分支

git branch -r

6.查看本地及远程分支

git branch -a

7.同步远程分支到本地，但不会合并

git fetch

8.新建分支

git branch 新分支名称

9.切换分支

git checkout 分支名称

10.新建并切换分支

git checkout -b 新分支名称

11.更新代码到暂存区

git add .

12.添加代码到本地

git commit -m “提交备注信息”

13.提交代码至远程分支

git push origin 分支名称

14.从远程拉区代码至本地

git pull

15.回退版本

git reset 版本号

16.将分支dev与当前分支进行合并

git merge origin/dev
