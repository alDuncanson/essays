# Essays Template

A template repository for publishing multiple Markdown essays with [md-press](https://github.com/alDuncanson/md-press).

## Usage

1. Click "Use this template" to create your own repository
2. Enable GitHub Pages: Settings → Pages → Source → **GitHub Actions**
3. Add your essays as `.md` files in the `essays/` directory
4. Push to `main` — your essays will be published automatically

## How It Works

Each Markdown file in `essays/` is converted to:
- **HTML** — for web viewing
- **PDF** — for download

An index page with links to all essays is auto-generated at your site root.

## Preview

Once deployed, your essays will be available at:

```
https://<username>.github.io/<repository>/
```

## PDF Styling

Control PDF layout with YAML frontmatter:

```markdown
---
geometry: margin=1in
fontsize: 12pt
---

# Your Essay Title
```

See the [md-press configuration docs](https://github.com/alDuncanson/md-press/blob/main/docs/configuration.md) for all options.
