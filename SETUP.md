###### Github个人资料仓库README.MD
```powershell
[在 GitHub 上新建空仓库（不要勾选 README）](https://github.com/new)
https://github.com/<username>/<username>

# 1. 创建项目目录并进入
cd E:\mywork
mkdir wzf9
cd wzf9

# 2. 初始化 Git 仓库
git init

# 3. 创建多行内容的 README（推荐）
#使用 @''@ 或 @""@" 的多行字符串
code-insiders readme.md

@'
# 项目名称

> 简短的项目描述

## 功能特点

- 特点1
- 特点2

## 快速开始

\`\`\`bash
git clone ...
\`\`\`

## 许可证

MIT
'@ > README.md


# 4. 添加并提交
# 查看修改状态
git status
# 添加修改的文件
git add README.md
# 提交（可写新的提交信息）
git commit -m "Initial commit with README"
git commit -m "Update README with latest info"
# 关联远程仓库(首次运行，以后不用)
git remote add origin https://github.com/wzf9/wzf9.git
# 推送（分支可能是 main 或 master）
git push origin main
```
