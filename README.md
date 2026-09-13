# yuanyu1016.github.io

这是 Yuanyu 的个人网站，使用 GitHub Pages + Jekyll + Minimal Mistakes 搭建。

## 技术基础

- GitHub Pages
- Jekyll
- Minimal Mistakes remote theme
- 自定义样式与脚本放在 `_includes/head/custom.html` 和 `_includes/footer/custom.html`

主题仓库：

```text
https://github.com/mmistakes/minimal-mistakes
```

## 页面结构

- 首页：`index.md`
- 关于我：`about.md`
- 项目与研究：`projects.md`
- 文章：`posts.md`
- 文章内容：`_posts/`
- AI 原生：`ai-native.md`
- 经历：`experience.md`
- 理想：`dreams.md`
- 简历：`resume.md`
- 单页简历 HTML：`assets/resume/Yuanyu_He_Resume.html`
- 简历 PDF：`assets/resume/Yuanyu_He_Resume.pdf`
- 联系：`contact.md`
- 导航：`_data/navigation.yml`
- 站点配置：`_config.yml`

## 资源目录

- 通用图片资源：`assets/`
- logo 与机构图片：`assets/`、`assets/logos/`
- 网站图标资源：`assets/icons/`
- 当前 favicon：`assets/icons/icon_1_cut.png`
- 简历导出文件：`assets/resume/`

网站 favicon 在 `_includes/head/custom.html` 中引用：

```html
<link rel="icon" type="image/png" href="{{ '/assets/icons/icon_1_cut.png' | relative_url }}">
```

## 交互与样式

当前站点在 Minimal Mistakes 主题基础上做了较多自定义：

- 固定顶部导航，跨页面保持一致。
- 首页使用全屏分段滚动体验。
- 页面切换使用 PJAX 风格的平滑过渡。
- 支持手动明暗主题切换，并将选择保存在浏览器本地。
- 支持中英文语言切换，主要页面内容通过前端脚本完成翻译覆盖。
- 简历以 `resume.md` 作为主路由，同时保留导出的 HTML 与 PDF 文件。

## 本地预览

安装依赖：

```powershell
bundle install
```

启动本地服务：

```powershell
bundle exec jekyll serve
```

默认访问：

```text
http://127.0.0.1:4000/
```

## 部署

提交并推送到 GitHub 后，GitHub Pages 会自动构建并发布：

```powershell
git add .
git commit -m "Update website"
git push
```

发布地址：

```text
https://yuanyu1016.github.io/
```
