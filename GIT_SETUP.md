# Git 使用指南

本文件夹是 Techno-Aesthetic-jewellery 项目的本地工作副本。

## 当前状态

由于系统未安装 Git,当前文件结构已手动创建并包含:
- 文献综述: `docs/文献综述_技术哲学与技术美学.md`
- 项目结构: docs/, chapters/, references/, methodology/, bibliography/
- 项目说明: README.md

## 如何与 GitHub 同步

要使用以下命令,您需要先安装 Git:
1. 下载并安装 Git: https://git-scm.com/downloads
2. 安装完成后,在 PowerShell 中执行以下命令:

### 初始化本地仓库并连接 GitHub

```powershell
cd c:/Users/armstrong/WorkBuddy/20260320222740/Techno-Aesthetic-jewellery
git init
git remote add origin https://github.com/francescolu/Techno-Aesthetic-jewellery.git
```

### 提交本地更改

```powershell
git add .
git commit -m "添加文献综述和项目结构"
git push -u origin master
```

### 从 GitHub 拉取最新内容

```powershell
git pull origin master
```

## 项目结构

```
Techno-Aesthetic-jewellery/
├── docs/                    # 研究文档
│   └── 文献综述_技术哲学与技术美学.md
├── chapters/                # 论文章节
├── references/              # 参考文献
├── methodology/             # 方法论
├── bibliography/            # 参考文献数据库
├── GIT_SETUP.md            # 本文件
└── README.md               # 项目说明
```

## 注意事项

- 建议定期提交更改到 GitHub 以备份您的研究成果
- 在推送前确保文件已添加到 .gitignore(如有敏感信息)
- 如需团队协作,请使用分支功能
