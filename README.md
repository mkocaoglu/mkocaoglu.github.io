# muratkocaoglu.com

Personal academic website of Murat Kocaoglu, Assistant Professor in the
Department of Computer Science at Johns Hopkins University. Built with Jekyll on
the [AcademicPages](https://github.com/academicpages/academicpages.github.io)
template (a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes))
and deployed via GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve     # or: bundle exec jekyll liveserve
```

Then open <http://localhost:4000>.

## Where things live

- `_config.yml` — site-wide configuration.
- `_pages/` — top-level pages (about/home, CV, teaching, service, personal, ...).
- `_data/publications.yml` — the publication list rendered by `_pages/publications.md`.
- `_data/navigation.yml` — the top navigation bar.
- `assets/css/main.scss` — stylesheet entry point. Site-specific variable
  overrides sit at the top (before the theme import); custom rules live in
  `_sass/_custom.scss`.
- `_includes/page-banner.html` — the banner image shown at the top of pages.
- `images/`, `files/` — images and downloadable files (CV, syllabi, papers).
