# 🚀 快速部署指南

## 第一步：准备工作

你需要确认以下内容：
- ✅ 你有一个 GitHub 账号 (adonxx)
- ✅ 你已经创建了仓库 yasil66
- ✅ 本地已安装 Git

## 第二步：上传代码

### 方法一：使用命令行 (推荐)

1. 打开终端/命令提示符，进入博客文件夹
```bash
cd yasil-blog
```

2. 初始化 Git 仓库
```bash
git init
git add .
git commit -m "初始化博客"
```

3. 连接到你的 GitHub 仓库
```bash
git remote add origin https://github.com/adonxx/yasil66.git
git branch -M main
git push -u origin main
```

### 方法二：使用 VS Code

1. 在 VS Code 中打开 `yasil-blog` 文件夹
2. 点击左侧的源代码管理图标（分支图标）
3. 点击"初始化存储库"
4. 在上方输入提交信息："初始化博客"
5. 点击"提交"
6. 点击"发布分支"
7. 选择 "yasil66" 仓库

## 第三步：启用 GitHub Pages

1. 访问 https://github.com/adonxx/yasil66
2. 点击 Settings (设置)
3. 在左侧菜单找到 Pages
4. 在 Source 下拉菜单选择 `main` 分支
5. 点击 Save

等待 2-3 分钟，你的网站就会发布在：
**https://adonxx.github.io/yasil66/**

## 第四步：更换背景图

### 方法 A：使用在线图片

编辑 `assets/css/style.css`，找到第 114 行左右的 `.hero-section`：

```css
.hero-section {
    height: 100vh;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    /* 修改下面这一行，使用你喜欢的图片链接 */
    background-image: url('你的图片URL');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
```

### 方法 B：使用本地图片

1. 将你的图片（例如 `hero-bg.jpg`）放入 `assets/images/` 文件夹
2. 编辑 `assets/css/style.css`：

```css
.hero-section {
    background-image: url('../images/hero-bg.jpg');
}
```

3. 重新提交代码：
```bash
git add .
git commit -m "更新背景图"
git push
```

## 第五步：修改个性签名

编辑 `_config.yml` 文件：

```yaml
title: Yasil's Blog
description: 你的个性签名在这里！  # 修改这一行
```

保存后推送：
```bash
git add _config.yml
git commit -m "更新个性签名"
git push
```

## 常见问题

### Q1: 推送代码时需要输入用户名密码？

A: GitHub 现在使用个人访问令牌(Token)：
1. 访问 https://github.com/settings/tokens
2. 生成新的 token
3. 使用 token 作为密码

### Q2: 修改后网站没有更新？

A: 等待 3-5 分钟，GitHub Pages 需要时间重新构建。可以在仓库的 Actions 标签查看构建状态。

### Q3: 网站显示 404？

A: 检查：
- baseurl 是否正确设置为 "/yasil66"
- 仓库名是否为 yasil66
- GitHub Pages 是否已启用

### Q4: 本地想预览效果？

A: 需要安装 Ruby 和 Jekyll：

```bash
# Windows 用户下载 RubyInstaller
# Mac/Linux 用户
gem install bundler jekyll
cd yasil-blog
bundle install
bundle exec jekyll serve
```

访问 http://localhost:4000/yasil66/

## 🎉 完成！

现在你已经有了一个功能完整的个人博客！

接下来你可以：
- 📝 在 `_posts` 文件夹添加博客文章
- 🎨 自定义颜色和样式
- 📷 添加更多图片和内容
- 🔗 在社交媒体分享你的博客

有问题随时问我！
