# Git 命令指南

## 1. 安装 Git
- 在 [Git 官网](https://git-scm.com/) 下载并安装。

## 2. 配置 Git
- 设置用户名：`git config --global user.name "你的名字"`
- 设置邮箱：`git config --global user.email "你的邮箱"`

## 3. 创建仓库
- 初始化新仓库：`git init`
- 克隆仓库：`git clone 仓库地址`

## 4. 基本操作
- 查看状态：`git status`
- 添加文件：`git add 文件名`
- 提交更改：`git commit -m "提交信息"`

## 5. 分支管理
- 查看分支：`git branch`
- 创建分支：`git branch 分支名`
- 切换分支：`git checkout 分支名`
- 合并分支：`git merge 分支名`

## 6. 远程操作
- 查看远程仓库：`git remote -v`
- 添加远程仓库：`git remote add 名称 仓库地址`
- 推送到远程仓库：`git push 名称 分支名`
- 从远程拉取：`git pull 名称 分支名`

## 7. 查看历史
- 查看提交历史：`git log`
- 查看简洁历史：`git log --oneline`

## 8. 恢复操作
- 取消未添加的更改：`git checkout -- 文件名`
- 撤消最近的提交：`git reset --soft HEAD~1`

## 9. 标签
- 创建标签：`git tag 标签名`
- 查看标签：`git tag`

## 10. 交互式暂存
- 交互式暂存：`git add -p`

## 11. 查看帮助
- 查看帮助：`git help` 或 `man git`  

这些命令将帮助你更好地使用 Git。