# 我的个人博客

这是我的个人博客网站，使用纯 HTML + CSS 构建，托管在 GitHub Pages 上。

## 📁 文件结构

```
my-blog/
├── index.html          # 首页
├── style.css           # 样式文件
├── about.html          # 关于页面
├── archive.html        # 文章归档
├── posts/              # 文章目录
│   ├── hello-world.html
│   └── stock-analysis.html
└── README.md           # 本文件
```

## 🚀 本地预览

1. 用浏览器打开 `index.html` 文件
2. 或者使用本地服务器：
   ```bash
   # 如果你有 Python
   python -m http.server 8000
   
   # 然后访问 http://localhost:8000
   ```

## 📝 如何写文章

1. 在 `posts/` 目录下创建新的 HTML 文件
2. 复制 `posts/hello-world.html` 作为模板
3. 修改标题、日期、内容
4. 在 `index.html` 和 `archive.html` 中添加文章链接

## 🌐 部署到 GitHub Pages

### 第一步：创建 GitHub 仓库

1. 访问 https://github.com/new
2. 仓库名：`my-blog`（或你喜欢的名字）
3. 选择 "Public"（公开）
4. 点击 "Create repository"

### 第二步：上传代码

```bash
# 在 my-blog 文件夹中打开命令行
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的用户名/my-blog.git
git push -u origin main
```

### 第三步：启用 GitHub Pages

1. 在 GitHub 仓库页面，点击 "Settings"
2. 左侧菜单点击 "Pages"
3. Source 选择 "Deploy from a branch"
4. Branch 选择 "main"，文件夹选择 "/ (root)"
5. 点击 "Save"
6. 等待几分钟，访问 `https://你的用户名.github.io/my-blog/`

## 🎨 自定义

### 修改网站标题
编辑所有 HTML 文件中的 `<title>` 和 `<div class="logo">`

### 修改颜色
编辑 `style.css` 中的颜色值，如 `#2563eb`（蓝色）

### 添加新页面
1. 复制 `about.html`
2. 修改文件名和内容
3. 在导航栏添加链接

## 📚 学习资源

- [MDN Web Docs](https://developer.mozilla.org/zh-CN/) - Web 技术文档
- [GitHub Pages 文档](https://docs.github.com/zh/pages)
- [W3Schools HTML 教程](https://www.w3schools.com/html/)

## 💡 进阶改进

- 添加评论功能（使用 Disqus）
- 添加网站统计（使用 Google Analytics）
- 使用 Jekyll/Hugo 生成静态网站
- 绑定自定义域名

---

**祝你写作愉快！** ✍️
