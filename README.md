# MATISSE

A MATLAB Toolbox for vItal rateS SurveillancE.

MATISSE implements the statistical methods described in Miranda Filho & Rosenberg,
["Advances in statistical methods for cancer surveillance research: an age-period-cohort perspective"](https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2023.1332429/full),
Frontiers in Oncology (2024). It packages age-period-cohort modeling, joinpoint
regression, comparative APC analysis, Lexis diagram smoothing, and semiparametric
APC analysis behind a common object-oriented interface (`rates`, `apc`, `epiphany`,
`capricorn`, `joinpoint`, `sift`, `sage`, ...).

Toolbox design and code: Philip S. Rosenberg, PhD.

## Contents

- [`index.qmd`](index.qmd) / [`index.html`](index.html) — project landing page (Quarto)
- [`images/`](images) — figures used on the landing page, including real MATISSE output
- [`downloads/`](downloads) — the toolbox (`MATISSE_toolbox.zip`), the `.mlx` user's guide,
  companion slide decks, and the reference papers

## Rendering the site

```bash
quarto render index.qmd
```

## Status

Working draft — first public release in preparation.
