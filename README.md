# Leyi Wu Personal Page

This repository hosts [yuevii.github.io](https://yuevii.github.io/), built with the [al-folio](https://github.com/alshedivat/al-folio) academic website template.

## Local preview

Use Ruby 3.3+:

```bash
bundle install
bundle exec jekyll serve
```

Or preview with Docker:

```bash
docker run --rm -p 4000:4000 -v "$PWD":/site -w /site ruby:3.3-bookworm bash -lc \
  'gem install bundler -v 4.0.6 --no-document && bundle _4.0.6_ install && bundle _4.0.6_ exec jekyll serve --host 0.0.0.0 --port 4000'
```

The site content lives mainly in:

- `_pages/about.md`
- `_bibliography/papers.bib`
- `_data/cv.yml`
- `_news/`
- `assets/img/publication_preview/`
- `assets/pdf/Leyi_Wu_CV.pdf`
