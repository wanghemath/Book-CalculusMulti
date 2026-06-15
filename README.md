# Multivariable Calculus in the Age of Data, AI, and Applied Mathematics

Repository target: <https://github.com/wanghemath/Book-CalculusMulti>

This is a Quarto book package for a modern 27-chapter multivariable calculus textbook designed as preparation for MS Applied Mathematics, MS Statistics, data science, AI, and machine learning.

A pdf version of the book written in LaTeX (with TikZ) is avilable: - [PDF Book with TikZ]<https://github.com/wanghemath/Book-CalculusMulti/latex/calculus-multivariable-complete-book.pdf>

## Structure

- `_quarto.yml` — main Quarto book configuration
- `index.qmd` — landing page
- `introduction.qmd` — book introduction
- `chapters/chapter-01-*.qmd` to `chapters/chapter-27-*.qmd` — 27 chapter files
- `labs/` — Jupyter notebook labs, one per chapter
- `htmls/` — starter standalone interactive HTML pages, one per chapter
- `appendices/` — formula sheet, Python reference, source-material map
- `styles.css` — book styling
- `.github/workflows/publish.yml` — GitHub Actions workflow for rendering and publishing

## Local build

```bash
quarto render
```

The rendered site will be written to `docs/`.

## Suggested GitHub Pages setting

Use GitHub Actions through the included workflow, or render locally and publish from the `docs/` folder.

## Python requirements

```bash
pip install -r requirements.txt
```

The initial chapters use only standard scientific Python tools. Some future labs may use additional packages.
