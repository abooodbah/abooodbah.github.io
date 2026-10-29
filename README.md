# abooodbah.github.io

The Lean Apps page at https://abooodbah.github.io/: one static page that links
three free, read-only desktop viewers.

- [LeanDoc](https://abooodbah.github.io/leandoc/), a Word (.docx) viewer for Windows, Linux and macOS
- [LeanRows](https://abooodbah.github.io/leanrows/), a large CSV viewer for Windows
- [LeanMark](https://abooodbah.github.io/leanmark/), a Markdown viewer with Mermaid for Windows, Linux and macOS

This repository also holds the root `robots.txt`, which lists the sitemap of
this page and of each app site. Search engines read `robots.txt` only at the
host root, so the copies inside each app site are not used.

The project sites are served by their own repositories at `/leandoc/`,
`/leanrows/`, and `/leanmark/`. Do not add folders with those names here.

There is no build step, no script, and no outside request. Preview with:

```sh
python -m http.server 8080
```

The IBM Plex fonts in `assets/fonts/` are under the SIL Open Font License 1.1
(`assets/fonts/OFL.txt`). The page itself is MIT licensed (`LICENSE`).
