# Alex’s Journal

A small, responsive personal blog built with Jekyll for GitHub Pages. Warm paper colors, a chronological journal, an archive, RSS, and individual entry pages. No tracking or external fonts.

## Publish a new entry

1. Open the repository on GitHub and choose **Add file → Create new file**.
2. Name it `_posts/YYYY-MM-DD-your-title.md` (use the date of your post).
3. Copy this template and write below the second `---`:

```markdown
---
title: "Your title"
description: "A short summary of your entry."
category: Journal
---

Write your entry here.

## A heading

You can use **bold**, *italics*, and [links](https://example.com).
```

4. Choose **Commit changes** to save it to `main`. Once Pages is enabled, GitHub rebuilds the public blog automatically. Allow a few minutes.

Use today's date or an earlier one. Future-dated posts aren't published by default.

## Drafts

A starter lives in `_drafts/my-first-entry.md`. Drafts do not appear on the website. When ready, copy the text into a dated file in `_posts/`.

If this repository becomes public, draft source files are also publicly readable on GitHub. Do not store confidential entries in a public repository.

## Edit the site

- Intro text: `index.html`
- About page: `about.md`
- Site title and description: `_config.yml`
- Colors and layout: `assets/style.css`

## Hosting setup

In **Settings → Pages**, use **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
Expected URL once enabled and deployed: https://alexhadley-sys.github.io/website/

GitHub Free supports Pages from public repositories; private repositories require a plan that supports private-repository Pages. The blog itself is intended to be public.

## Local preview (optional)

Install Ruby and Bundler, run `bundle install`, then `bundle exec jekyll serve`. Open the printed local URL with `/website/`.
