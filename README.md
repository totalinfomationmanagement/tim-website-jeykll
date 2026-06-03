# TiM Ltd. Website

Total Information Management Ltd. - Jekyll site.

## Structure

```
_posts/          ← Articles (add new ones here)
_layouts/        ← Page templates
_includes/       ← Reusable components (nav, footer)
assets/css/      ← Stylesheet
news/            ← News listing page
index.html       ← Homepage
```

## Adding a new article

1. Create a new file in `_posts/` named: `YYYY-MM-DD-your-article-slug.md`
2. Copy the front matter from any existing post
3. Write content in Markdown
4. Commit and push - GitHub Pages builds automatically

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000
