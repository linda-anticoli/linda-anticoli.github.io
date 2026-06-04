# My website

A simple Jekyll site for GitHub Pages with a blog and a projects page.

## Everyday tasks

**Add a blog post:** put a new file in the `_posts` folder, named like
`YYYY-MM-DD-title.md` (e.g. `2026-07-01-my-post.md`). Copy an existing post
to get the format right.

**Add a project square:** put a new file in the `_projects` folder (any name
ending in `.md`). Copy an existing project to get the format right. Set the
`link:` field to wherever the project should send people (a questionnaire,
a paper, another website). The clickable square appears automatically.

## How it's organised

- `_config.yml` — site title and settings
- `index.html` — home page
- `blog.html` — the blog index (lists all posts)
- `projects.html` — the grid of clickable project squares
- `_posts/` — one file per blog post
- `_projects/` — one file per project
- `_layouts/` — page templates (you rarely need to touch these)
- `assets/style.css` — the look of the site
