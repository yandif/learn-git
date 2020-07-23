## 基本状态

1. git status 查看状态
2. git add  . 添加到暂存区
3. git commit -m "描述" 提交
4. git log 查看日志
5. git log -p 修改了什么
6. git checkout  <id>  回退到之前版本
7.  git switch -c <new-branch-name>
8. git switch - 取消

## 三个状态

1. modifed 已修改
2. staged  暂存区
3. commited 已提交

 ## 标签

- git tag -a 标签名 -m “tag注释”  <id> ：添加tag
- git tag ：罗列tag
- git log --oneline 显示一行

## 分支

* git branch $branchName          : 创建分支 

* git checkout $branchName      : 切换到分支 
* git log --all --graph                   :图形化显示

## 分支合并

* git checkout -b $branchName 

* git merge $branchName 

* 原来合并一个文件是全手工活啊

## 远程仓库

* git remote add github https://github.com/yandif/learn-git.git      :添加远程仓库
* git push -u $remoteName $branchName :push到远程分支
* git remove -v                                         :远程url
* git clone $giturl                                     :克隆