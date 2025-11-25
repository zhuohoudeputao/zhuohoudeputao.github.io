# Zhuohoudeputao Jekyll 多页面站点

## 本地预览

1. 安装 Jekyll（需 Ruby 环境）：
   ```bash
   gem install bundler jekyll
   ```
2. 在项目根目录运行：
   ```bash
   bundle init # 如果没有 Gemfile
   echo 'gem "jekyll"' >> Gemfile
   bundle install
   bundle exec jekyll serve
   ```
3. 浏览器访问 http://localhost:4000

## 目录说明
- `home.md`：Jekyll 主页（/）
- `index.html`：原纪念页，保留为独立页面
- `_layouts/`、`_includes/`：Jekyll 布局与片段
- `about.html`、`projects.html`：示例多页面

## 部署
推送到 GitHub，GitHub Pages 会自动构建 Jekyll 站点。

如需自定义域名，确保 `CNAME` 文件存在且内容正确。