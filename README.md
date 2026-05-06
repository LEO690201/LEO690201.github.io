# LEO690201.github.io

This repository hosts <https://leo690201.github.io>.

The root homepage now uses the [al-folio](https://github.com/alshedivat/al-folio) academic Jekyll template.

Preserved legacy pages:

- <https://leo690201.github.io/calendar/>
- <https://leo690201.github.io/research/>
- <https://leo690201.github.io/beat_xyy/>
- <https://leo690201.github.io/beat_yjy/>

Important files:

- `_config.yml`: site identity, URL, social links, and al-folio settings.
- `_pages/about.md`: root homepage content.
- `_pages/links.md`: navigation page linking to preserved pages.
- `_projects/`: project cards, currently redirecting to preserved pages.
- `.github/workflows/deploy.yml`: builds the Jekyll site and deploys `_site`.

For GitHub Pages, use the generated deployment branch from the workflow (`gh-pages`) or configure Pages according to the al-folio deployment workflow.
