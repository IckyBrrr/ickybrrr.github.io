# Academic website

Plain HTML/CSS site hosted on GitHub Pages at https://ickybrrr.github.io

## Structure
| File | What it is |
|---|---|
| `index.html` | Home: bio, job market banner, JMP, fields, references |
| `research.html` | JMP, publications, working papers, work in progress |
| `teaching.html` | Teaching experience, statement, evaluations |
| `cv.pdf` | Your CV (add this file) |
| `files/` | Paper PDFs, slides, statements |
| `assets/style.css` | All styling. Change `--accent` to your school color |
| `assets/photo.svg` | Placeholder photo. Replace with `photo.jpg` and update `index.html` |

## Common edits
- **Add a paper:** copy a `<div class="paper">…</div>` block in `research.html` and edit it.
- **Replace placeholders:** search all files for `Your Name`, `University Name`, `Professor Name`, `Field 1`.
- **Preview locally:** `python -m http.server 8000` in this folder, then open http://localhost:8000
- **Publish:** `git add -A && git commit -m "Update" && git push`. The site updates in about a minute.
