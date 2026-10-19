# git_learning

学习 Git 与 GitHub 的练习仓库。

## 目录

仓库目前处于初始化阶段，后续会陆续加入学习笔记与练习代码。

## 本地环境

- Git for Windows 2.56.0
- 默认分支：`main`
- 远端：`https://github.com/Morrismht/git_learning.git`

## 常用命令速查

```bash
git status                 # 查看工作区状态
git add .                  # 暂存全部改动
git commit -m "message"    # 提交
git push                   # 推送到远端
git pull                   # 拉取远端更新
git log --oneline --graph  # 查看提交历史
```

## 提交约定

- 一次提交只做一件事，提交信息用一句话说明「做了什么」。
- 推送前先 `git pull --rebase`，避免产生无意义的合并提交。
