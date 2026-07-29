# 职校生问个明白投稿管理工具

这是用于微博开发者认证和项目说明的静态网站，包含：

- 项目主页 `index.html`
- 隐私政策 `privacy.html`
- 响应式样式 `styles.css`
- 项目标志 `assets/mark.svg`

## 微博开发者认证填写内容

网站名称：

```text
职校生问个明白投稿管理工具
```

网站地址：

```text
https://abagaelx.github.io/zhixiaosheng-bot/
```

应用简介：

```text
为微博账号“职校生问个明白”提供中职、高职及贯通培养投稿的整理、隐私脱敏、人工审核和内容发布辅助。仅处理投稿者主动提交的信息，所有公开发布操作均由运营者确认。
```

## 发布到 GitHub Pages

1. 登录 GitHub 账号 `AbagaelX`，新建公开仓库 `zhixiaosheng-bot`，不要初始化 README。
2. 在本文件夹运行以下命令：

```powershell
git add .
git commit -m "Create project information site"
git branch -M main
git remote add origin https://github.com/AbagaelX/zhixiaosheng-bot.git
git push -u origin main
```

3. 打开 GitHub 仓库的 `Settings > Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/ (root)`，保存。
6. 等待页面生成后，访问 `https://abagaelx.github.io/zhixiaosheng-bot/`。
7. 使用未登录浏览器检查主页、隐私政策和问卷链接，再将网址提交给微博。

## 本地预览

双击 `index.html` 即可预览。网站没有服务端依赖，也不会在本地收集数据。
