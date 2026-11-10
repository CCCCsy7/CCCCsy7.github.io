# Shuying Cao's academic website

个人学术主页，使用官方 [al-folio](https://github.com/alshedivat/al-folio) v1 模板。主题由 `al_folio_core` 1.0.15 提供；没有混用其他主题，也不包含模板示例论文、项目或博客。

## 内容维护

| 内容 | 文件 |
| --- | --- |
| 简介与头像信息 | `_pages/about.md` |
| 首页研究兴趣、教育与技能 | `_data/home_sections.yml` |
| 首页板块的排版与顺序 | `_includes/home_sections.liquid`、`assets/css/home-sections.css` |
| 已发表论文 | `_bibliography/papers.bib` |
| 准备中与审稿中的论文 | `_data/manuscripts.yml`，用 `status` 区分状态 |
| 项目 | `_projects/` |
| 新闻 | `_news/` |
| 博客 | `_posts/YYYY-MM-DD-title.md` |
| 网页版 CV | `_data/cv.yml` |
| PDF CV | `files/Shuying_Cao_CV.pdf` |
| 社交链接 | `_data/socials.yml` |
| 姓名、网址及主题功能 | `_config.yml` |

添加论文时，在 BibTeX 条目中设置 `selected = {true}` 即可在首页展示。论文预览图放在 `assets/img/publication_preview/`，用 `preview` 字段引用文件名。

添加博客时，文件名使用日期加标题，front matter 至少填写 `layout: post`、`title` 和 `date`。目前没有个人博客文章，页面显示空状态。

新闻 `date` 用于排序，`display_date` 保留原信息的日期精度；只知道年份时，不会显示未经确认的具体月日。

## 本地预览

使用 Ruby 3.3 或更新版本及 Bundler：

```sh
bundle install
bundle exec jekyll serve
```

浏览器打开 `http://localhost:4000`。正式构建：

```sh
JEKYLL_ENV=production bundle exec jekyll build
```

## GitHub Pages

仓库地址为 `CCCCsy7/CCCCsy7.github.io`，网站地址为 <https://ccccsy7.github.io>。在仓库 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**。推送至 `master` 或 `main` 后，`.github/workflows/deploy.yml` 会构建并发布；Pull Request 只验证构建。

al-folio 使用 GitHub Pages 默认构建不支持的插件，因此需要该 Actions 工作流。

## 主题更新

主题和功能插件的版本固定在 `Gemfile`，实际解析版本记录在 `Gemfile.lock`。升级时先修改版本并运行 `bundle update`，再构建和检查：

```sh
bundle exec al-folio upgrade audit
bundle exec al-folio upgrade overrides audit
```

主题局部覆盖保留了 al-folio 的布局：`news.liquid` 增加 `display_date` 支持；`name.liquid` 及首页、导航、页脚、论文和 CV 的局部覆盖统一将完整姓名加粗。已通过 `.al-folio-overrides.yml` 记录所基于的主题版本。

本次迁移参考官方 starter 提交 `8158dd07b40eda745da47a55a8a711332286dbf5`。
