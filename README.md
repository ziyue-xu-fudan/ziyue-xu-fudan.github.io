# Ziyue Xu - Personal Academic Website

徐子岳的个人学术主页

## 部署到 GitHub Pages

1. 在 GitHub 上创建一个新的仓库，命名为 `ziyuexu.github.io` (将 ziyuexu 替换为你的 GitHub 用户名)

2. 上传所有文件到该仓库：
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ziyuexu/ziyuexu.github.io.git
git push -u origin main
```

3. 等待几分钟，访问 `https://ziyuexu.github.io` 即可看到你的主页

## 自定义修改

### 1. 更换头像
- 将你的照片命名为 `profile.jpg`
- 放入 `images/` 文件夹中
- 建议尺寸：正方形，至少 500x500 像素

### 2. 添加 Google Scholar 链接
- 在 index.html 中搜索 `Google Scholar`
- 将 `#` 替换为你的 Google Scholar 个人主页链接

### 3. 添加 GitHub 链接
- 在 index.html 中搜索 `GitHub`
- 将 `#` 替换为你的 GitHub 个人主页链接

### 4. 更新内容
- 直接编辑 `index.html` 文件即可修改任何内容

## 文件结构

```
.
├── index.html          # 主页面
├── README.md           # 本说明文件
├── images/             # 图片文件夹
│   └── profile.jpg     # 个人头像（需自行添加）
```

## 技术特点

- 纯 HTML/CSS/JavaScript，无需后端
- 响应式设计，支持移动端
- 基于参考网站 angelakeke.github.io 的设计风格
- 蓝色学术风格 (#122F51)

## 联系方式

- Email: ziyuexu20@fudan.edu.cn
- 电话: 159-0187-3779
