# Web Security – Script Gadgets (Presentation)

English LaTeX Beamer presentation (~15 min.) based on **paper.pdf** (Lekies et al., CCS 2017).

## Presentation

| Path | Description |
|------|-------------|
| [DS_LaTeX_Beamer_03_2026/main.tex](DS_LaTeX_Beamer_03_2026/main.tex) | Slide content |
| [DS_LaTeX_Beamer_03_2026/templates/Praesentation.tex](DS_LaTeX_Beamer_03_2026/templates/Praesentation.tex) | Title, name, institute |
| [DS_LaTeX_Beamer_03_2026/main.pdf](DS_LaTeX_Beamer_03_2026/main.pdf) | Compiled PDF (after build) |
| [DS_LaTeX_Beamer_03_2026/SPEAKER_NOTES.md](DS_LaTeX_Beamer_03_2026/SPEAKER_NOTES.md) | 15-minute timing guide |
| [text.txt](text.txt) | Per-slide explanation and what to say |

### Build (LuaLaTeX)

```powershell
cd DS_LaTeX_Beamer_03_2026
lualatex main.tex
bibtex main
lualatex main.tex
lualatex main.tex
```

Enter your name in `templates/Praesentation.tex` before building.

## Sources

- **paper.pdf** — main source (theory, bypass, study)
- **pdf_from_friends.pdf** — optional course example (Bootstrap tooltip), one slide

## Submission

See [UPLOAD.md](UPLOAD.md).
