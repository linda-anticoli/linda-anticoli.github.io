# Post sections — cheat sheet

Every post can carry a `section:` in its front matter. It shows up as a
typewriter-style slug in the top-left corner of the blog card (e.g. `/ESSAY`).

## The three sections

| Section    | Use it for                                                              |
|------------|-------------------------------------------------------------------------|
| `Essay`    | Argued, structured pieces (like "My ChatGPT told me"). The default.     |
| `Notes`    | Short, loose observations; questions without answers yet. Low bar, post freely. |
| `Research` | Posts tied to academic work: studies, findings, the questionnaire project. |

Possible future additions (only when the first post of that kind exists):
`Readings` (commentary on books/papers), `Teaching` (reflections from lecturing).

## How to use

Add one line to the post's front matter:

```yaml
---
layout: post
title: "My post title"
date: 2026-07-23
section: Essay        # or Notes, Research
---
```

Rules of thumb:

- One word, English, capitalised as above — even on Italian posts
  (language is already marked separately, see below).
- If you leave `section:` out, nothing breaks — the card corner just stays empty.
- Don't use the key `category:` — that's reserved by Jekyll and would change
  the post's URL. Always `section:`.

## Italian posts

Mark them with `lang: it` in the front matter. This shows the small `IT` tag
in the top-right corner of the card, independent of the section.

---

This file is just for reference — Jekyll ignores it because the filename has no
`YYYY-MM-DD-` date prefix, so it will never appear on the site.
