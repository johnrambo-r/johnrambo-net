# johnrambo.net

Personal website of John Rambo Rajendran — hosted free on GitHub Pages with Jekyll.

## Repo Structure

```
.
├── index.html          # Homepage (static, no layout needed)
├── CNAME               # Custom domain: johnrambo.net
├── _config.yml         # Jekyll configuration
├── _layouts/
│   ├── post.html       # Layout for individual blog posts
│   └── blog.html       # Layout for the /blog/ listing page
├── blog/
│   └── index.html      # Blog listing page (uses blog layout)
└── _posts/
    └── YYYY-MM-DD-slug.md   # Blog posts in Markdown
```

## Writing a New Post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this header:

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-01-01
tags: [Recruiting]
read_time: 3
---

Your content here in plain Markdown.
```

GitHub Pages will automatically build and publish it.

## Deploying to GitHub Pages

1. Create a GitHub repo (e.g. `johnrambo-net`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. GitHub will detect Jekyll and build automatically

## DNS Setup at Your Registrar

Point `johnrambo.net` to GitHub Pages with these A records:

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

DNS propagation takes up to 48 hours. GitHub Pages will auto-provision HTTPS once it resolves.
