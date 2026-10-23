# arnoblalam.com

Source for [arnoblalam.com](https://arnoblalam.com), the personal academic website of Arnob L. Alam.

Built with Jekyll using the [al-folio](https://github.com/alshedivat/al-folio) theme and deployed to GitHub Pages by the `deploy` workflow on pushes to `main`.

## Where things live

- `_pages/about.md` – home page bio
- `_bibliography/papers.bib` – research page (rendered by jekyll-scholar)
- `_pages/teaching.md` – teaching page
- `assets/pdf/CV.pdf` – CV
- `_config.yml` – site-wide settings

## Local preview

```bash
docker compose up
```

or, with Ruby installed:

```bash
bundle install
bundle exec jekyll serve
```

See `INSTALL.md`, `CUSTOMIZE.md` and `FAQ.md` (from the theme) for more.
