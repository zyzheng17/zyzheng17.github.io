# zyzheng17.github.io

Academic homepage for Ziyang Zheng. Jekyll-based, al-folio style.

## Quick reference

- **Build**: `bundle install && bundle exec jekyll serve`
- **Deploy**: Push to `main` → GitHub Actions auto-deploys
- **Add paper**: thumbnail to `assets/img/publication_preview/`, entry in `_pages/publications.md` (and `_includes/selected_papers.html` if first-author)
- **Email**: obfuscated via `data-user`/`data-domain` attributes + client JS

## Structure

```
_pages/about.md          Landing page (bio + selected pubs)
_pages/publications.md   All papers by year
_pages/photography.md    Masonry photo grid
_includes/               Reusable partials
_layouts/                Page templates
assets/css/main.css      All styles (no preprocessor)
assets/img/              Images (prof_pic, publication_preview/, photography/)
```
