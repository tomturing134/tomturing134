# 朱亚鹏 - 个人简历网站

基于简历内容创建的交互式个人简历网站。

## 预览

打开 [index.html](index.html) 即可查看。

## 部署到 GitHub Pages

### 方式一：创建新仓库部署

1. 在 GitHub 上创建新仓库，名称推荐 `zhu-yapeng-resume` 或 `username.github.io`
2. 将本项目文件推送到仓库：
   ```bash
   cd C:\Users\zhangyicong2\WorkBuddy\20260430215608
   git init
   git add index.html image.png .nojekyll .gitignore README.md
   git commit -m "Initial commit: 交互式简历网站"
   git branch -M main
   git remote add origin https://github.com/<你的用户名>/<仓库名>.git
   git push -u origin main
   ```
3. 进入仓库 Settings → Pages → Source 选择 `main` 分支 → Save
4. 等待1-2分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`

### 方式二：使用 username.github.io（专属域名）

1. 创建名为 `<你的用户名>.github.io` 的仓库
2. 同上推送文件
3. 自动部署到 `https://<你的用户名>.github.io/`

## 文件结构

```
├── index.html      # 主页面
├── image.png       # 个人照片
├── .nojekyll       # 禁用 Jekyll 处理
├── .gitignore      # Git 忽略规则
└── README.md       # 说明文档
```

## 技术栈

- 纯 HTML / CSS / JavaScript
- 无第三方依赖
- 响应式设计，适配桌面和移动端

## 功能

- 粒子连线动态背景
- 滚动渐显动画
- 技能条填充动画
- 数据递增动画
- 导航栏自动高亮
- 联系方式一键复制
- 返回顶部按钮
