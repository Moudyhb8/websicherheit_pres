# Submission: Script Gadgets Presentation

## Included

1. **Presentation (LaTeX + PDF)**  
   Folder `DS_LaTeX_Beamer_03_2026/`  
   - `main.tex`, `templates/Praesentation.tex`, `bibliography.bib`  
   - `main.pdf` (after building with LuaLaTeX + BibTeX)

2. **Speaker material** — `text.txt`, `SPEAKER_NOTES.md`, `README.md`

## Optional ZIP

```powershell
Compress-Archive -Path DS_LaTeX_Beamer_03_2026, text.txt, README.md, UPLOAD.md -DestinationPath websicherheit_presentation.zip
```

## Assignment note

Slides cover the **paper** (definition, attack outline, bypass of all mitigation classes, study results). For “show application / demonstrate exploit,” use the **course application** or the environment described in `pdf_from_friends.pdf` — no separate lab project is included here.
