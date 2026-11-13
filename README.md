# IDSC 4590: Agentic AI for Business Applications

Public course page for **IDSC 4590, Agentic AI for Business Applications**, a
7-week, no-code undergraduate course at the Carlson School of Management,
University of Minnesota.

The site is built with [Zensical](https://zensical.org) (the successor to
Material for MkDocs) and deployed to GitHub Pages by
`.github/workflows/docs.yml`.

## Local development

```bash
python3 -m venv .venv
.venv/bin/pip install zensical
.venv/bin/zensical serve   # http://127.0.0.1:8000
```

Content lives in `docs/`. The landing page is `docs/index.md` with styles in
`docs/stylesheets/extra.css`.
