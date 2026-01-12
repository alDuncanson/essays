---
geometry: margin=1in
fontsize: 11pt
---

# Essay Two

This is a sample essay to demonstrate multi-file publishing with md-press.

## Introduction

Replace this content with your own writing. Each Markdown file in the `essays/` directory will be converted to both HTML and PDF formats.

## How It Works

When you push changes to the `main` branch:

1. All `.md` files in `essays/` are discovered
2. Each file is converted to HTML and PDF
3. An index page with links to all essays is generated
4. Everything is deployed to GitHub Pages

## Formatting Tips

You can use standard Markdown formatting:

- **Bold text** and *italic text*
- [Links](https://example.com)
- `inline code`
- Block quotes, lists, and more

The PDF output respects the YAML frontmatter at the top of each file for margins, font size, and other LaTeX options.
