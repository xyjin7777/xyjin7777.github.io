# Xiangyu Jin — personal website

Hugo site using the re-Terminal theme, single page with a floating section bar.

## Files you'll edit

| What | Where |
|---|---|
| All page text | `content/_index.md` |
| Your photo | replace `static/img/headshot.jpg` (keep the name, or change `src` in `_index.md`) |
| Research figure | `static/img/research/J0226p0302_illustrative_cartoon_no_xray.png` |
| CV | add `static/files/cv.pdf` |
| Links in the floating bar | `[[languages.en.menu.main]]` blocks in `hugo.toml` |
| Font, page width, photo size, colours | top of `static/style.css` |

A nav link's `url` must match its heading: `## About Me` → `#about-me`,
`## Other Activities` → `#other-activities`.

## Preview

    hugo server

then open the address it prints.

## Publish

Push to `main`, then on GitHub: Settings → Pages → Source → GitHub Actions.
