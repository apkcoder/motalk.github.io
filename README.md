# 墨说

GitHub Pages + Hexo 搭建的个人博客。

- 仓库名：`motalk.github.io`
- 站点地址：<https://motalk.github.io>
- 博客名：墨说
- 副标题：把日子写成句子，把心事落成文字

## 本地开发

```bash
pnpm install
pnpm server
```

默认访问：<http://localhost:4000>

## 新建文章

```bash
npx hexo new post "文章标题"
```

## 构建

```bash
pnpm build
```

## 发布

推送到 `main` 分支后，GitHub Actions 会自动构建并发布到 GitHub Pages。

## 首次启用 GitHub Pages

如果仓库刚创建：

1. 打开 GitHub 仓库 Settings
2. 进入 Pages
3. Source 选择 **GitHub Actions**

## 自定义

站点基础配置在 `_config.yml`。

- 标题：`title`
- 副标题：`subtitle`
- 站点描述：`description`
- URL：`url`
