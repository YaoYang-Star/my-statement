# 我的声明网站

这是一个静态单页网站，用于发布事件声明。

## 本地预览

直接在浏览器中打开 `index.html` 即可预览。

## 部署到 GitHub Pages

### 1. 创建 GitHub 仓库

在 GitHub 上创建一个新仓库（可以是 public 或 private）。

### 2. 初始化 Git 并推送

```bash
cd my-static-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

### 3. 启用 GitHub Pages

1. 进入仓库的 **Settings**
2. 点击左侧菜单的 **Pages**
3. 在 **Build and deployment** 下：
   - **Source**: 选择 `Deploy from a branch`
   - **Branch**: 选择 `main` 分支，文件夹选择 `/ (root)`
4. 点击 **Save**

### 4. 访问网站

几分钟后，你的网站将可通过以下地址访问：

```
https://你的用户名.github.io/你的仓库名/
```

## 自定义内容

编辑 `index.html` 文件底部的 `translations` 对象，修改 `zh`（中文）和 `en`（英文）的文案即可。
