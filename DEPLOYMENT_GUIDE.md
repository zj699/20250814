# 🚀 GitHub Pages 部署指南

## 第一步：创建 GitHub 仓库

1. **登录 GitHub**
   - 访问 [github.com](https://github.com)
   - 登录你的账户（如果没有账户，先注册）

2. **创建新仓库**
   - 点击右上角的 "+" 号
   - 选择 "New repository"
   - 仓库名建议：`learning-dashboard`
   - 设置为 Public（公开）
   - 不要勾选 "Add a README file"（我们已经有了）
   - 点击 "Create repository"

## 第二步：上传文件到 GitHub

### 方法一：使用 Git 命令行（推荐）

1. **安装 Git**
   - 下载：[https://git-scm.com/download](https://git-scm.com/download)
   - 按默认设置安装

2. **在项目文件夹中打开命令行**
   ```bash
   # 进入项目目录
   cd "C:\Users\leoji\.claude\projects\20250814"
   
   # 初始化 Git 仓库
   git init
   
   # 添加所有文件
   git add .
   
   # 提交文件
   git commit -m "首次提交：认知升级学习中心"
   
   # 添加远程仓库（替换为你的GitHub用户名）
   git remote add origin https://github.com/[你的用户名]/learning-dashboard.git
   
   # 推送到GitHub
   git push -u origin main
   ```

### 方法二：直接在 GitHub 网页上传

1. **进入你创建的仓库页面**
2. **点击 "uploading an existing file"**
3. **拖拽以下文件到上传区域：**
   - `index.html`
   - `README.md`
   - `.gitignore`
   - `DEPLOYMENT_GUIDE.md`
4. **添加提交信息**：`首次提交：认知升级学习中心`
5. **点击 "Commit changes"**

## 第三步：启用 GitHub Pages

1. **进入仓库设置**
   - 在你的仓库页面，点击 "Settings" 标签
   
2. **找到 Pages 设置**
   - 向下滚动找到 "Pages" 部分
   - 或直接访问：`https://github.com/[你的用户名]/learning-dashboard/settings/pages`

3. **配置 Pages**
   - Source: 选择 "Deploy from a branch"
   - Branch: 选择 "main"
   - Folder: 选择 "/ (root)"
   - 点击 "Save"

4. **等待部署完成**
   - 通常需要几分钟
   - 部署完成后，GitHub 会显示你的网站链接

## 第四步：访问你的网站

你的学习中心将在以下地址可用：
```
https://[你的GitHub用户名].github.io/learning-dashboard
```

例如，如果你的用户名是 `john123`，则地址为：
```
https://john123.github.io/learning-dashboard
```

## 📱 在手机上使用

1. **保存为书签**
   - 在手机浏览器中打开网站
   - 添加到主屏幕或收藏夹

2. **离线使用**
   - 网站设计支持离线使用
   - 首次加载后，基本功能无需网络

## 🔄 更新网站

当你需要更新内容时：

### 使用 Git：
```bash
# 修改文件后
git add .
git commit -m "更新描述"
git push
```

### 使用 GitHub 网页：
1. 点击要修改的文件
2. 点击编辑按钮（铅笔图标）
3. 修改内容
4. 提交更改

## ⚠️ 注意事项

1. **首次部署可能需要10-15分钟**
2. **确保仓库是 Public 的**
3. **主文件必须命名为 `index.html`**
4. **所有学习进度和笔记都保存在本地浏览器**

## 🆘 常见问题

**Q: 网站显示404错误**
A: 检查仓库是否为Public，且包含index.html文件

**Q: 更新后网站没变化**
A: 等待5-10分钟，或清除浏览器缓存

**Q: 手机上显示不正常**
A: 检查是否使用最新的index.html文件

**Q: 学习进度丢失了**
A: 进度保存在本地，不要清除浏览器数据

## 🎉 完成！

现在你就有了自己的在线学习中心，可以在任何设备上访问！

记住你的网址：`https://[你的用户名].github.io/learning-dashboard`