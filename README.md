# Hello-World



## 基础操作

### `git init` —— 初始化仓库

### `git status` —— 查看仓库的状态

### `git add` —— 向暂存区中添加文件

### `git commit` —— 保存仓库的历史记录

`git log`

`git diff`



---------------  feature-A

## 分支操作

`git branch` —— 显示分支一览表

```shell
git checkout -b feature-A # 创建名为 feature-A 的分支  等价于下方两条命令
## 创建 feature-A 分支，并将当前分支切换为 feature-A 分支
git branch feature-A
git checkout feature-A
```



`git merge` —— 合并分支

`git log --graph` —— 以图表形式查看分支



## 更改提交的操作

`git reset` —— 回溯历史版本

