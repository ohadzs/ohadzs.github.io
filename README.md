# Ohad's Blog - Maintenance Notes

This repository is a static HTML blog.

## How to add a new post

1. Create a new file in `YYYY/mon/DD.html` (example: `2026/mar/22.html`).
2. Use the same structure as existing posts:
   - `<html lang="he" dir="rtl">`
   - back link: `<a href="../../">← חזרה</a>`
   - title format: `DD/MM/YYYY - <post title>`
   - content inside a `<pre>` block
3. Add the post entry at the top of `index.html` inside `#posts`:
   - `href` to the new file
   - visible text in the same `DD/MM/YYYY - title` format
   - `data-tags` with comma-separated Hebrew tags

## Style conventions

- Keep files in UTF-8.
- Keep RTL layout and Alef font setup as in existing pages.
- Preserve punctuation and line breaks in post text.
- Do not change older posts unless explicitly requested.

## Quick checklist before finishing

- New post file exists in the correct month folder.
- `index.html` points to the correct path and date.
- Tags are present and relevant for filter buttons.
- No broken references to old date/file names.
