# Personal academic website

A [Jekyll](https://jekyllrb.com/) site hosted on **GitHub Pages**. Every time you
push to the `master` branch, GitHub rebuilds the site automatically — there is no
separate "deploy" step.

This README is the only thing you need to edit the site. The rule of thumb:

> **You edit _content_ and _settings_. You almost never touch the theme.**

---

## 1. Where everything lives

| I want to change…                | Edit this                                   |
| -------------------------------- | ------------------------------------------- |
| Site title, description, URL     | `_config.yml` (top of file)                 |
| The sidebar (name, photo, links) | `_config.yml` → `author:` block             |
| The top menu / navigation        | `_data/navigation.yml`                      |
| The home page                    | `_pages/about.md`                           |
| My CV                            | `_pages/cv.md`                              |
| A publication                    | `_publications/`                            |
| A portfolio item                 | `_portfolio/`                               |
| Downloadable files (PDFs, etc.)  | `files/`  → served at `/files/<name>`       |
| Images                           | `images/` → referenced as `/images/<name>`  |

The site currently has three sections in the menu: **Publications**, **Portfolio**,
and **CV** (plus the home page). Everything else (`_layouts/`, `_includes/`,
`_sass/`, `assets/`) is the **theme** — you don't need to open these to run the site.

---

## 2. Adding content

Each piece of content is **one Markdown file**. The fastest, safest way to add a
new one is to **copy an existing file in the same folder and change the values** —
the existing files are working templates.

The block at the top of each file between `---` lines is "front matter": structured
data the theme reads. The text below the second `---` is the body (plain Markdown).

### Publication — `_publications/`
Filename convention: `YYYY-MM-DD-short-name.md`.
```yaml
---
title: "Paper title"
collection: publications
category: manuscripts          # books | manuscripts | conferences (see _config.yml)
permalink: /publication/2025-01-31-short-name
excerpt: 'One-line summary.'
date: 2025-01-31
venue: 'Journal or conference name'
paperurl: 'http://.../files/paper.pdf'   # optional
slidesurl: 'http://.../files/slides.pdf' # optional
bibtexurl: 'http://.../files/cite.bib'   # optional
citation: 'Your Name. (2025). "Paper title." <i>Venue</i>.'
---
```

### Portfolio — `_portfolio/`
```yaml
---
title: "Project name"
excerpt: "Short description.<br/><img src='/images/project.png'>"
collection: portfolio
---
Longer description here.
```

### Standalone page — `_pages/`
Set a `permalink` to control the URL, then add it to the menu in
`_data/navigation.yml` if you want it in the header.

### Adding a new section later (e.g. Talks, Teaching, Blog)
This site was trimmed to Publications + Portfolio. To bring back another section,
register a collection under `collections:` in `_config.yml`, create the matching
`_<name>/` folder with entries, add a page in `_pages/` to list them, and link it
in `_data/navigation.yml`.

---

## 3. Previewing locally (optional)

You don't have to preview — pushing to GitHub already builds the live site. But to
check changes before pushing:

```bash
bundle install            # first time only
bundle exec jekyll serve  # then open http://localhost:4000
```

---

## 4. Publishing

```bash
git add -A
git commit -m "Update content"
git push
```

GitHub Pages rebuilds and the live site updates within a minute or two.

---

This site is based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
template (MIT License, see `LICENSE`), trimmed down to the parts in use.
