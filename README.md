# cjackson692.github.io

Source for [cjackson692.github.io](https://cjackson692.github.io/) — personal site for Carter Smith, Computational Linguist & Data Scientist.

## Structure

| File              | Purpose                                                        |
| ----------------- | -------------------------------------------------------------- |
| `index.md`        | Homepage / complete CV                                         |
| `research.md`     | Research positions, publications, presentations, and projects  |
| `teaching.md`     | Teaching experience                                            |
| `_config.yml`     | Jekyll site configuration (Midnight remote theme)              |

All pages share the same top-of-page navigation strip so they can be reordered or extended without changing the theme.

## Adding a new page

1. Create `newpage.md` at the repo root with YAML front matter:

   ```yaml
   ---
   layout: default
   title: New Page — Carter Smith
   description: Short description.
   ---
   ```

2. Copy the navigation strip from the top of any existing page and add a link to the new page.
3. Add the new link to the navigation strip in `index.md`, `research.md`, and `teaching.md`.

## Adding a new entry to an existing page

Each section is delimited by `---` rules and an `##` (or `###`) heading. To add an entry, drop a new block in the appropriate spot — entries are independent and can be reordered freely.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then visit <http://localhost:4000>.

## Theme

This site uses the [Midnight](https://github.com/pages-themes/midnight) remote theme.
