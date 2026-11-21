# Personal page

🌐 **[Visit my portfolio page](https://mducducd.github.io/resume/)**
## Editing the site

Built with plain Jekyll (no plugins), so GitHub Pages builds it on push.

- **New essay:** add `_essays/<slug>.html` with front matter (`title`, `description`, `date`, `summary`) followed by the essay's `<section class="learning-blog-section">` blocks. It appears on `/blog/<slug>.html`, in the blog list and in the Study card, newest first.
- **New project:** add an entry to `_data/projects.yml`. The Work page is generated from it.
- **Shared header, footer and head:** `_includes/` and `_layouts/`.

Preview locally: `jekyll serve` (Ruby and Jekyll 3.9 or newer).
