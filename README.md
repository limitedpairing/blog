# limitedpairing

A single-page blog built with [Jekyll](https://jekyllrb.com) and hosted on
GitHub Pages at **https://limitedpairing.github.io/blog**.

The home page lists every post; each post has its own permalink.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000/blog/.

## Writing a post

Create a file in `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```yaml
---
layout: post
title: "Your title here"
date: 2026-06-10 09:00:00 +0000
tags: [example]
---
```

Write the body in Markdown below the front matter. New posts appear on the
home page automatically.

## Structure

```
_config.yml      # site configuration
index.html       # single-page home (lists all posts)
_layouts/        # default + post layouts
_posts/          # blog posts (Markdown)
assets/css/      # styles (Sass)
```

## Deployment

Push to the default branch and enable GitHub Pages (Settings → Pages → build
from the branch) — or rely on the bundled `github-pages` gem for a build that
matches GitHub's.
