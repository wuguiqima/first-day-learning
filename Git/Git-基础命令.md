# Git 基础命令

## 配置

| 命令 | 说明 |
|------|------|
| `git config --global user.name "用户名"` | 设置全局用户名 |
| `git config --global user.email "邮箱"` | 设置全局邮箱 |
| `git config --global init.defaultBranch main` | 设置默认分支名为 main |
| `git config --global credential.helper manager` | 配置凭证管理器 |

## 仓库操作

| 命令 | 说明 |
|------|------|
| `git init` | 初始化本地仓库 |
| `git clone <url>` | 克隆远程仓库到本地 |

## 日常操作

| 命令 | 说明 |
|------|------|
| `git status` | 查看当前文件状态 |
| `git add <文件>` | 添加文件到暂存区 |
| `git add .` | 添加所有文件到暂存区 |
| `git commit -m "提交信息"` | 提交暂存区的变更 |
| `git log` | 查看提交历史 |
| `git log --oneline` | 简洁模式查看提交历史 |

## 远程操作

| 命令 | 说明 |
|------|------|
| `git remote add origin <url>` | 关联远程仓库 |
| `git push -u origin main` | 首次推送并建立关联 |
| `git push` | 推送到远程仓库 |

## 小贴士

- `git add .` 和 `git commit -m ""` 可以合并为 `git commit -am ""`（仅对已追踪文件有效）
- 多人协作时，推送前先 `git pull` 拉取最新代码
