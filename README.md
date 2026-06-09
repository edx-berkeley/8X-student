# DATA 88B Jupyter Notebook Materials

Public lecture and lab notebooks for **DATA 88B: Economic Analysis for Business Decisions** (edX xSeries).

This repository mirrors the [Data 8 materials-sp26](https://github.com/data-8/materials-sp26) layout: a Jupyter Book site with notebooks organized by course part.

## Contents

- **Part 1** (`lec/1/`, `lab/1/`): 12 lectures and 7 labs (lab00–lab06) — data management through simulation
- **Part 2** (`lec/2/`, `lab/2/`): 10 lectures and 7 labs (lab07–lab13) — hypothesis tests through chi-squared tests
- **Part 3** (`lec/3/`, `lab/3/`): 11 lectures and 4 labs (lab14–lab17) — linear regression through interaction

## Local development

```bash
pip install -r requirements.txt
jupyter lab
```

Open **http://localhost:8888/lab** and navigate to notebooks under `lab/`.

## Enable Binder (after pushing to GitHub)

Binder is configured in `myst.yml` for `edx-berkeley/8X-student`. After pushing to GitHub, rebuild with `jupyter-book build --html`.

## Build the book site

```bash
npm install -g jupyter-book
jupyter-book build --html
```

The built site is in `_build/html/`.

## Related courses

- [88C materials](https://github.com/edx-berkeley/88c_jupyternotebook) (when available)
- [88E materials](https://github.com/edx-berkeley/88e_jupyternotebook) (when available)
