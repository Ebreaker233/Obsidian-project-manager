# Obsidian-project-manager

一个基于 [Obsidian](https://obsidian.md) 的个人项目管理与知识资料库，用于集中保存日常学习、工作和项目中的笔记与资料，并通过 Git 进行版本管理与多端同步。

> 本库为自用库，主要保存个人资料。

## ✨ 特性

- **本地优先**：所有笔记以 Markdown 文件形式存储在本地，不依赖任何云端服务
- **Git 版本管理**：完整的提交历史，随时回溯每一次修改
- **双向链接**：借助 Obsidian 的 `[[]]` 链接串联项目、任务与知识点
- **跨平台同步**：通过 Git 在多台设备之间保持资料一致

## 🚀 快速开始

### 环境要求

- [Obsidian](https://obsidian.md) 桌面端或移动端
- Git

### 克隆本库

```bash
git clone https://github.com/Ebreaker233/Obsidian-project-manager.git
```

### 在 Obsidian 中打开

1. 打开 Obsidian，选择 **Open folder as vault**（打开库）
2. 选择克隆下来的 `Obsidian-project-manager` 文件夹
3. 首次打开时选择 **Trust author and enable plugins**（信任并启用插件）

## 📁 目录结构

```
Obsidian-project-manager/
├── 00-Inbox/          # 收集箱：临时存放未整理的灵感与资料
├── 01-Projects/       # 项目笔记：每个进行中的项目一个文件夹
├── 02-Areas/          # 领域笔记：长期负责的事项（工作、学习、健康等）
├── 03-Resources/      # 资源库：值得保存的文章、教程、参考资料
├── 04-Archive/        # 归档：已完成或不再活跃的项目与笔记
└── 05-Daily/          # 日记：每日记录与复盘
```

> 目录结构遵循 PARA 方法（Projects / Areas / Resources / Archive），可按需调整。

## 🔄 同步流程

```bash
# 开始编辑前，先拉取远端最新内容
git pull

# 编辑完成后提交并推送
git add .
git commit -m "update notes"
git push
```

## 📝 使用建议

- **Inbox 归零**：定期清空收集箱，把内容归位到对应目录
- **善用链接**：用 `[[]]` 把相关的项目、笔记互相连接，形成知识网络
- **小步提交**：每完成一条笔记就提交一次，提交信息写清楚改了什么
- **定期归档**：项目结束后移入 `04-Archive/`，保持活跃区整洁

## 📄 许可证

本库内容为个人资料，仅作个人学习与管理使用。

---

*Maintained by [Ebreaker233](https://github.com/Ebreaker233)*
