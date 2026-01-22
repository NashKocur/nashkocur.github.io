# nashkocur.github.io

Personal blog powered by Hugo and the PaperMod theme.

## How to Use

### Publishing Blog Posts

Use the blog post editor to create and publish posts. The editor will automatically:
1. Upload images to `static/images/`
2. Create markdown files in `content/posts/`
3. GitHub Actions will automatically build and deploy your site

### Local Development

If you want to preview your blog locally:

1. Install Hugo: https://gohugo.io/installation/
2. Clone this repository
3. Run `hugo server -D`
4. Open http://localhost:1313 in your browser

### Manual Post Creation

You can also manually create posts in `content/posts/`:

```markdown
---
title: "Your Post Title"
date: 2026-01-22T00:00:00Z
draft: false
author: "Your Name"
description: "Post description"
tags: ["tag1", "tag2"]
categories: ["category"]
---

Your content here...
```

## GitHub Pages Setup

Make sure to enable GitHub Pages in your repository settings:
1. Go to Settings → Pages
2. Set Source to "GitHub Actions"
3. Your site will be available at https://nashkocur.github.io/

## Structure

- `content/posts/` - Blog posts (markdown files)
- `static/images/` - Images used in posts
- `themes/PaperMod/` - Hugo theme
- `.github/workflows/` - GitHub Actions for automatic deployment
