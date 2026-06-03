# Speaker Notes (~15 minutes) — English

| Time | Section | Content |
|------|---------|---------|
| 0:00–1:00 | Title, outline | Opening sentence: defenses vs. trusted JS |
| 1:00–3:30 | XSS, motivation, 4 mitigations, bridge | Classic payload → defenses → key question |
| 3:30–7:30 | Script gadgets Ch. 3 | Definition (after bridge), benign HTML, DOM, attack outline, types |
| 7:30–11:30 | Bypass Ch. 4 | Request filter, sanitizer, CSP; 13/16, 19.88% |
| 11:30–12:30 | Bootstrap case study | Short course PDF illustration |
| 12:30–14:30 | Countermeasures, takeaways | Encoding, CSP limits, PoC repo |
| 14:30–15:00 | Questions | |

## Build

```powershell
cd DS_LaTeX_Beamer_03_2026
lualatex main.tex
bibtex main
lualatex main.tex
lualatex main.tex
```

## Main source

`paper.pdf` — Lekies et al., *Code-Reuse Attacks for the Web: Breaking XSS Mitigations via Script Gadgets*, CCS 2017.

## Full script

See [../text.txt](../text.txt) for slide-by-slide wording.
