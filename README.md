# dlebron12.github.io

Personal site of **Dayanara Lebrón-Aldea**, data scientist and bioinformatician.
Live at <https://dlebron12.github.io>. Built with Jekyll on GitHub Pages (no theme gem needed).

## Editing content

Most content lives in plain YAML files. Edit these and the pages update:

| File | What it controls |
|---|---|
| `_config.yml` | Name, tagline, email, LinkedIn/GitHub handles, photo |
| `_data/highlights.yml` | The four big numbers on the home page |
| `_data/case_studies.yml` | "Selected work" cards (problem → what I did → result) |
| `_data/experience.yml` | Experience timeline |
| `_data/projects.yml` | Project cards (add new projects at the top) |
| `_data/publications.yml` | Publications & patent |
| `_data/nav.yml` | Top navigation |

Pages are in `_pages/` (About, Experience, Projects, Freelance, Writing).
New blog posts go in `_posts/` as `YYYY-MM-DD-Title.md` with front matter:

```yaml
---
layout: post
title: "Your title"
categories: [Data Science]
description: One-sentence summary shown in post lists.
---
```

Styles: `assets/css/main.css` (colors are the tokens at the top).

## Local preview (optional)

```sh
bundle install
bundle exec jekyll serve
```
