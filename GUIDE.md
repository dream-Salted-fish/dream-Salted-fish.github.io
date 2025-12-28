# 📖 使用指南 / User Guide

欢迎使用你的学习博客！这个指南将帮助你快速开始记录学习内容。

Welcome to your learning blog! This guide will help you quickly start documenting your learning.

## 🚀 快速开始 / Quick Start

### 1. 选择分类 / Choose a Category

根据你要学习的内容，选择合适的分类目录：

Choose the appropriate category directory based on what you're learning:

- `posts/programming/` - 编程语言相关 / Programming languages
- `posts/frameworks/` - 框架和库 / Frameworks and libraries  
- `posts/tools/` - 开发工具 / Development tools
- `posts/algorithms/` - 算法和数据结构 / Algorithms and data structures
- `posts/projects/` - 项目实践 / Project practices

### 2. 创建笔记文件 / Create a Note File

在对应的目录下创建一个新的 Markdown 文件：

Create a new Markdown file in the corresponding directory:

```bash
# 例如：在 tools 目录下创建 Docker 学习笔记
# Example: Create Docker learning notes in tools directory
touch posts/tools/docker-basics.md
```

### 3. 使用模板 / Use the Template

可以复制 `posts/TEMPLATE.md` 作为起点：

You can copy `posts/TEMPLATE.md` as a starting point:

```bash
cp posts/TEMPLATE.md posts/tools/docker-basics.md
```

### 4. 编写内容 / Write Content

使用任何文本编辑器或 IDE 编辑 Markdown 文件，填入你的学习笔记。

Use any text editor or IDE to edit the Markdown file and fill in your learning notes.

### 5. 更新主页 / Update the Homepage

在完成笔记后，可以在 `README.md` 的"最新文章"部分添加链接：

After completing your notes, add a link in the "Latest Posts" section of `README.md`:

```markdown
## 📝 最新文章 / Latest Posts

- [Docker 基础学习](./posts/tools/docker-basics.md) - 2024-01-15
- [Git 基础学习](./posts/tools/git-basics.md) - 2024-01-01
```

## 📝 编写技巧 / Writing Tips

### Markdown 基础语法 / Markdown Basic Syntax

```markdown
# 一级标题 / H1
## 二级标题 / H2
### 三级标题 / H3

**粗体文本** / **Bold text**
*斜体文本* / *Italic text*

- 列表项 1
- 列表项 2

1. 有序列表 1
2. 有序列表 2

[链接文本](URL)

![图片描述](图片URL)

`行内代码` / `inline code`

\`\`\`language
代码块
code block
\`\`\`
```

### 代码高亮 / Code Highlighting

使用语言标识符来启用语法高亮：

Use language identifiers to enable syntax highlighting:

- `python` - Python 代码
- `javascript` 或 `js` - JavaScript 代码
- `java` - Java 代码
- `cpp` - C++ 代码
- `bash` 或 `shell` - Shell 命令
- `sql` - SQL 查询
- `html` - HTML 代码
- `css` - CSS 样式

### 组织建议 / Organization Suggestions

1. **使用清晰的文件名** / Use clear file names
   - 使用小写字母和连字符：`react-hooks.md`
   - 避免空格和特殊字符

2. **保持结构一致** / Keep structure consistent
   - 使用模板确保所有笔记格式统一
   - 包含日期、标签等元数据

3. **定期更新索引** / Update indexes regularly
   - 在主 README 中列出最新文章
   - 在各分类 README 中维护目录

4. **添加标签** / Add tags
   - 使用标签方便搜索和分类
   - 例如：#python #web #backend

## 🎨 自定义 / Customization

### 修改主页 / Modify Homepage

编辑 `README.md` 来自定义你的博客首页：

Edit `README.md` to customize your blog homepage:

- 更新"关于我"部分
- 调整学习路线
- 添加或删除分类
- 添加个人社交媒体链接

### 添加新分类 / Add New Categories

如果需要新的笔记分类：

If you need new note categories:

```bash
mkdir -p posts/new-category
```

然后创建对应的 README.md 文件。

Then create a corresponding README.md file.

### 添加图片 / Add Images

可以创建 `images/` 目录来存放图片：

Create an `images/` directory to store images:

```bash
mkdir -p images
```

在笔记中引用：

Reference in notes:

```markdown
![描述](../images/screenshot.png)
```

## 💡 最佳实践 / Best Practices

1. **定期提交** / Commit regularly
   - 每次完成一篇笔记后提交到 Git
   - 使用清晰的提交信息

2. **保持简洁** / Keep it simple
   - 专注于关键内容
   - 避免过于冗长

3. **添加示例** / Add examples
   - 代码示例帮助理解
   - 实际应用场景

4. **链接相关内容** / Link related content
   - 在笔记之间建立连接
   - 引用相关学习资源

5. **定期回顾** / Review regularly
   - 复习旧笔记
   - 更新过时信息

## 🔧 Git 工作流 / Git Workflow

```bash
# 1. 创建或编辑笔记
# Create or edit notes

# 2. 查看更改
# Check changes
git status
git diff

# 3. 添加更改
# Add changes
git add .

# 4. 提交更改
# Commit changes
git commit -m "Add: [topic] learning notes"

# 5. 推送到 GitHub
# Push to GitHub
git push
```

## 📱 在 GitHub 上查看 / View on GitHub

你的学习博客将显示在你的 GitHub 个人资料页面上，因为这是一个特殊的用户名同名仓库。

Your learning blog will be displayed on your GitHub profile page because this is a special username repository.

访问：`https://github.com/[你的用户名]`

Visit: `https://github.com/[your-username]`

## 🎉 开始学习吧！/ Start Learning!

现在你已经准备好开始记录你的学习之旅了。记住：

Now you're ready to start documenting your learning journey. Remember:

- 🎯 保持一致性 / Stay consistent
- 📚 持续学习 / Keep learning
- 💪 不断进步 / Keep improving
- 🌟 享受过程 / Enjoy the process

祝你学习愉快！Happy learning!
