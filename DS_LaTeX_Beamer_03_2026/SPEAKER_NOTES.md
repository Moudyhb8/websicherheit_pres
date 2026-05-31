# Speaker Notes (~15 minutes) — English

| Time | Section | Content |
|------|---------|---------|
| 0:00–1:00 | Title, outline | Topic script gadgets, Lekies CCS 2017 |
| 1:00–3:00 | Motivation, 4 mitigations | XSS, second line, three strategies |
| 3:00–7:00 | Script gadgets Ch. 3 | Definition, benign HTML, DOM, attack outline, types |
| 7:00–11:00 | Bypass Ch. 4 | Request filter, sanitizer, CSP; 13/16, 19.88% |
| 11:00–12:00 | Bootstrap case study | Short course PDF illustration |
| 12:00–14:00 | Countermeasures, takeaways | Encoding, CSP limits, PoC repo |
| 14:00–15:00 | Questions | |

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
