# 从零开始学Git

### 一 基础命令

1). 查看工作目录和暂存区的状态

`git status`

1). 将文件添加到暂存区

`git add ./fileName`

2). 将文件提交到本地仓库并添加提交注释

`git commit -m "commit message info"`

3). 从远端拉取代码到本地仓库

`git pull /--rebase origin <baranchName>`

> <p> 最好使用 git pull --rabase
> <p> git pull = git fetch + git merge
> <p> git pull --rabase = git fetch + git rebase

*可以看这个教程=>*[rabase用法](https://www.cnblogs.com/ellen-mylife/p/12794245.html)

### 二 分支

1). 从指定分支拉去最新代码

`git pull origin <branchName>`

2). 新建分支

`git branch <branchName>`

3). 切换分支

`git checkout <branchName>`

4). 新建分支并切换该分支

`git checkout -b <branchName>`

5). 本地分支推送到远端

`git push origin <branchName>`