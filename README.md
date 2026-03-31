# 外贸贸易网站

基于纯前端技术构建的外贸展示网站。

## 功能特性

- 商品轮播展示
- 商品详情页（支持图片轮播）
- 在线询盘功能
- 管理员系统（商品管理、留言管理、访问统计）
- 数据本地持久化（localStorage）

## 快速部署到 GitHub Pages

1. **创建仓库**
   - 登录 [GitHub](https://github.com)
   - 创建新仓库，名称设为 `huamao-website`
   - 选择 Public，点击 Create repository

2. **上传文件**
   - 在仓库页面点击 "uploading an existing file"
   - 将本项目的 `index.html` 文件拖入上传
   - 点击 Commit changes

3. **启用 GitHub Pages**
   - 进入仓库 Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main"，文件夹保持 "/root"
   - 点击 Save

4. **绑定域名**（可选）
   - 在 Settings → Pages → Custom domain 输入 `www.huamao.com`
   - 根据提示配置 DNS 记录

## 访问方式

- GitHub Pages: `https://你的用户名.github.io/huamao-website/`
- 绑定域名后: `https://www.huamao.com`

## 管理员账号

- 用户名: `admin`
- 密码: `admin123`

登录后可管理商品、查看留言和访问统计。