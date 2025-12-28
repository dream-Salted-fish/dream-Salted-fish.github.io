# Git 基础学习 / Git Basics

**学习日期 / Date:** 2024-01-01  
**分类 / Category:** 工具

## 📖 概述 / Overview

学习 Git 的基本概念和常用命令，掌握版本控制的基础操作。

Learning Git basics and commonly used commands to master fundamental version control operations.

## 📚 主要内容 / Main Content

### Git 基本概念 / Git Basic Concepts

- **仓库 (Repository)**: 项目的存储空间
- **提交 (Commit)**: 保存项目的快照
- **分支 (Branch)**: 独立的开发线
- **远程仓库 (Remote)**: 托管在服务器上的仓库

### 常用命令 / Common Commands

**初始化和配置 / Initialization & Configuration**
```bash
git init                    # 初始化新仓库
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

**基本操作 / Basic Operations**
```bash
git status                  # 查看状态
git add <file>             # 添加文件到暂存区
git add .                  # 添加所有文件
git commit -m "message"    # 提交更改
```

**分支操作 / Branch Operations**
```bash
git branch                 # 查看分支
git branch <name>         # 创建分支
git checkout <name>       # 切换分支
git checkout -b <name>    # 创建并切换分支
git merge <branch>        # 合并分支
```

**远程操作 / Remote Operations**
```bash
git clone <url>           # 克隆远程仓库
git pull                  # 拉取远程更改
git push                  # 推送本地更改
```

## 💻 代码示例 / Code Examples

**典型工作流程 / Typical Workflow**
```bash
# 1. 克隆项目
git clone https://github.com/username/repo.git
cd repo

# 2. 创建新分支进行开发
git checkout -b feature/new-feature

# 3. 进行修改后提交
git add .
git commit -m "Add new feature"

# 4. 推送到远程
git push origin feature/new-feature

# 5. 切换回主分支
git checkout main

# 6. 合并功能分支
git merge feature/new-feature
```

## 🎯 重点总结 / Key Points

- Git 是分布式版本控制系统，每个开发者都有完整的代码历史
- 使用分支进行功能开发，保持主分支稳定
- 提交信息要清晰明确，描述做了什么改动
- 定期同步远程仓库，避免冲突
- 使用 `.gitignore` 忽略不需要版本控制的文件

## 🤔 问题与思考 / Questions & Reflections

- 什么时候应该创建新分支？
  - 开发新功能、修复 bug、实验性改动时都应创建新分支
- 如何写好 commit message？
  - 使用现在时态，简洁描述改动内容，必要时添加详细说明
- 遇到合并冲突怎么办？
  - 手动编辑冲突文件，保留需要的内容，然后重新提交

## 📝 总结 / Summary

通过本次学习，掌握了 Git 的基本概念和常用命令。下一步计划学习：
- Git 的高级特性（rebase, cherry-pick, stash 等）
- GitHub 的使用和协作流程
- Git 最佳实践和团队协作规范

Through this learning session, I've mastered Git basic concepts and common commands. Next steps:
- Learn Git advanced features (rebase, cherry-pick, stash, etc.)
- Learn GitHub usage and collaboration workflow
- Study Git best practices and team collaboration standards

## 🔗 参考资料 / References

- [Git 官方文档](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/zh/v2)
- [GitHub Git Cheat Sheet](https://training.github.com/)
- [Learn Git Branching](https://learngitbranching.js.org/)

---

**标签 / Tags:** #git #版本控制 #工具 #基础
