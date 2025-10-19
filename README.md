# utr491.github.io

This is a simple Jekyll blog hosted on GitHub Pages.

## How to add a blog post

1. Create a markdown file in `_posts/` with the format `YYYY-MM-DD-title.md`.
2. Include front matter at the top:

```
---
layout: post
title: "Your Post Title"
description: "Short description (optional)"
tags: [tag1, tag2]
---
```

3. Write your content in Markdown below the front matter.
4. Commit and push to `main`. GitHub Pages will rebuild automatically.

## Local development (optional)

If you want to preview locally:

```
gem install bundler jekyll
bundle init
echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Customization

- Update site settings in `_config.yml` (`title`, `description`).
- Edit `index.md` for the homepage layout.
- Edit `about.md` for the About page.