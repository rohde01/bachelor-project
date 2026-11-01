# Bachelor's thesis: Constraint-based Scheduling in CP-SAT

University of Copenhagen · BSc Computer Science and Economics · Spring 2025 · 15 ECTS.

My bachelor project models a real scheduling problem as constraint optimisation and solves it with Google's CP-SAT solver, including several objectives at once. It discusses where multi-objective optimisation works and where it falls short.

## Contents

| Folder | Contents |
| --- | --- |
| `main.tex, main.pdf` | The thesis |
| `KUstyle.sty, KU-logo.pdf` | The KU thesis template |
| `AI-deklaration-DK.pdf` | AI declaration |

## Topics

- Constraint programming
- CP-SAT
- Multi-objective optimisation

## Tools

Python, OR-Tools, LaTeX

## Build

Each LaTeX source sits next to its PDF. Rebuild a PDF from its folder with:

```bash
tectonic -Z continue-on-errors main.tex
```

## Notes

Written with Emil Oliver Olesen. The template needs XeLaTeX, which tectonic uses. The scheduling tool's code is in [field-schedule](https://github.com/rohde01/field-schedule).
