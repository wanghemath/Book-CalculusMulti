# Multivariable Calculus in the Age of AI
 
 

**Multivariable Calculus in the Age of AI** is a modern Quarto textbook designed as a bridge from single variable calculus to graduate study in applied mathematics, statistics, data science, artificial intelligence, and machine learning.

This is a Quarto book package for a modern 27-chapter multivariable calculus textbook designed as preparation for MS Applied Mathematics, MS Statistics, data science, AI, and machine learning.


The book presents multivariable calculus as a language for geometry, approximation, optimization, probability, computation, and scientific modeling. It combines classical topics such as vectors, partial derivatives, multiple integrals, line integrals, surface integrals, Green's theorem, Stokes theorem, and the divergence theorem with computational and modern applications including gradient descent, Jacobians, automatic differentiation, likelihood functions, covariance geometry, probability densities, and machine-learning loss landscapes.

**Book site:** <https://wanghemath.github.io/Book-CalculusMulti/>  
**Repository:** <https://github.com/wanghemath/Book-CalculusMulti>

A pdf version of the book written in LaTeX (with TikZ) is avilable: - [PDF Book with TikZ]<https://github.com/wanghemath/Book-CalculusMulti/latex/calculus-multivariable-complete-book.pdf>

---

## Project vision

This book is written for students preparing for mathematically serious graduate work. The goal is not only to teach computational techniques, but also to build the conceptual habits needed for modern applied mathematics:

- Think of functions as maps between spaces.
- Read geometry from formulas and formulas from geometry.
- Use derivatives as local linear models.
- Use gradients and Hessians to understand optimization.
- Use multiple integrals to compute volume, mass, probability, and expectation.
- Use vector calculus to express flow, circulation, flux, and conservation.
- Use Python to visualize, approximate, simulate, and verify mathematical ideas.

The text is especially useful for students moving toward MS-level work in applied mathematics, statistics, data science, machine learning, AI foundations, quantitative modeling, and scientific computing.

---

## Repository structure

```text
Book-CalculusMulti/
├── _quarto.yml                 # Quarto book configuration
├── index.qmd                   # Landing page and roadmap
├── introduction.qmd            # Book introduction and study guide
├── python-labs.qmd             # Overview of Python labs with Colab links
├── interactive-htmls.qmd       # Overview of interactive HTML pages
├── references.qmd              # Reference guide
├── references.bib              # Bibliography database
├── chapters/                   # 27 textbook chapters
├── labs/                       # 27 Jupyter notebooks
├── htmls/                      # 27 interactive HTML pages
├── appendices/                 # Formula sheet and Python reference
├── figures/                    # Figure assets
├── data/                       # Data files, when needed
├── styles.css                  # Custom book styling
├── requirements.txt            # Python package requirements
└── environment.yml             # Conda environment file
```

---

## Book contents

### Part I. Geometry, Vectors, and Spaces

| Chapter | Topic |
|---:|---|
| 1 | [From Single Variable Calculus to Multivariable Thinking](chapters/chapter-01-from-single-variable-calculus-to-multivariable-thinking.qmd) |
| 2 | [Euclidean Space $\mathbb R^n$](chapters/chapter-02-euclidean-space-rn.qmd) |
| 3 | [Vectors, Norms, Dot Products, and Projections](chapters/chapter-03-vectors-norms-dot-products-and-projections.qmd) |
| 4 | [Lines, Planes, Hyperplanes, and Parametric Geometry](chapters/chapter-04-lines-planes-hyperplanes-and-parametric-geometry.qmd) |
| 5 | [Cross Products, Curves, and Motion in Space](chapters/chapter-05-cross-products-curves-and-motion-in-space.qmd) |

### Part II. Functions of Several Variables and Differentiation

| Chapter | Topic |
|---:|---|
| 6 | [Functions of Several Variables](chapters/chapter-06-functions-of-several-variables.qmd) |
| 7 | [Limits and Continuity in Several Variables](chapters/chapter-07-limits-and-continuity-in-several-variables.qmd) |
| 8 | [Partial Derivatives and the Gradient](chapters/chapter-08-partial-derivatives-and-the-gradient.qmd) |
| 9 | [Linear Approximation, Tangent Planes, and Differentials](chapters/chapter-09-linear-approximation-tangent-planes-and-differentials.qmd) |
| 10 | [Chain Rule, Jacobians, and Automatic Differentiation](chapters/chapter-10-chain-rule-jacobians-and-automatic-differentiation.qmd) |
| 11 | [Directional Derivatives, Hessians, and Optimization](chapters/chapter-11-directional-derivatives-hessians-and-optimization.qmd) |
| 12 | [Constrained Optimization and Lagrange Multipliers](chapters/chapter-12-constrained-optimization-and-lagrange-multipliers.qmd) |

### Part III. Multiple Integrals, Probability, and Change of Variables

| Chapter | Topic |
|---:|---|
| 13 | [Double Integrals and Riemann Sums](chapters/chapter-13-double-integrals-and-riemann-sums.qmd) |
| 14 | [Double Integrals over General Regions](chapters/chapter-14-double-integrals-over-general-regions.qmd) |
| 15 | [Polar Coordinates and Change of Variables in the Plane](chapters/chapter-15-polar-coordinates-and-change-of-variables-in-the-plane.qmd) |
| 16 | [Triple Integrals and Geometry in $\mathbb R^3$](chapters/chapter-16-triple-integrals-and-geometry-in-r3.qmd) |
| 17 | [Cylindrical and Spherical Coordinates](chapters/chapter-17-cylindrical-and-spherical-coordinates.qmd) |
| 18 | [Multivariable Taylor Approximation and Quadratic Forms](chapters/chapter-18-multivariable-taylor-approximation-and-quadratic-forms.qmd) |

### Part IV. Vector Calculus, Fields, and Global Theorems

| Chapter | Topic |
|---:|---|
| 19 | [Vector Fields and Gradient Fields](chapters/chapter-19-vector-fields-and-gradient-fields.qmd) |
| 20 | [Line Integrals and Work](chapters/chapter-20-line-integrals-and-work.qmd) |
| 21 | [Conservative Fields, Potentials, and Green's Theorem](chapters/chapter-21-conservative-fields-potentials-and-green-s-theorem.qmd) |
| 22 | [Curl, Divergence, and Surface Integrals](chapters/chapter-22-curl-divergence-and-surface-integrals.qmd) |
| 23 | [Stokes Theorem and the Divergence Theorem](chapters/chapter-23-stokes-theorem-and-the-divergence-theorem.qmd) |

### Part V. Modern Applications for Graduate Preparation

| Chapter | Topic |
|---:|---|
| 24 | [Multivariable Calculus for Probability and Statistics](chapters/chapter-24-multivariable-calculus-for-probability-and-statistics.qmd) |
| 25 | [Multivariable Calculus for Data Science and Machine Learning](chapters/chapter-25-multivariable-calculus-for-data-science-and-machine-learning.qmd) |
| 26 | [Multivariable Calculus for Applied Mathematics](chapters/chapter-26-multivariable-calculus-for-applied-mathematics.qmd) |
| 27 | [Review, Synthesis, and Bridge to Graduate Study](chapters/chapter-27-review-synthesis-and-bridge-to-graduate-study.qmd) |

---

## Computational resources

The book includes two companion resource collections.

### Python labs

The `labs/` folder contains one Jupyter notebook for each chapter. These labs are designed for exploration, visualization, numerical approximation, simulation, and model-building.

Start here:

- [Python Labs Overview](python-labs.qmd)
- Example notebook: [`labs/Chapter01_From_Single_Variable_Calculus_to_Multivariable_Thinking.ipynb`](labs/Chapter01_From_Single_Variable_Calculus_to_Multivariable_Thinking.ipynb)

Students can open the notebooks locally or through Google Colab using the links on the Python labs page.

### Interactive HTML pages

The `htmls/` folder contains one interactive HTML page for each chapter. These pages are intended for quick review, visual exploration, and independent study.

Start here:

- [Interactive HTMLs Overview](interactive-htmls.qmd)

---

## Appendices

- [Formula Sheet](appendices/formula-sheet.qmd): a compact reference for core formulas and theorems.
- [Python Reference](appendices/python-reference.qmd): reusable code patterns for vectors, plots, gradients, optimization, integration, probability, and vector fields.
- [Source Material Map](appendices/source-material-map.qmd): a guide to how the course materials inform the book structure.

---

## Local setup

### Option 1: Use Conda

```bash
conda env create -f environment.yml
conda activate calculusmulti
```

### Option 2: Use pip

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

On Windows PowerShell, activate the environment with:

```powershell
.venv\Scripts\Activate.ps1
```

---

## Rendering the book

Install Quarto from <https://quarto.org/>. Then, from the repository root, run:

```bash
quarto render
```

To preview locally:

```bash
quarto preview
```

The rendered site is written to the `docs/` folder, as configured in `_quarto.yml`.

---

## Suggested learning path

A student preparing for graduate-level applied work can use the book in three passes.

**First pass: geometric fluency.**  
Read Chapters 1--7 and focus on vectors, spaces, functions, surfaces, level sets, and limits.

**Second pass: approximation and optimization.**  
Read Chapters 8--12 and 18. Focus on gradients, Jacobians, Hessians, Taylor approximation, and optimization.

**Third pass: integration, probability, and fields.**  
Read Chapters 13--17 and 19--26. Focus on multiple integrals, coordinate transformations, probability densities, vector fields, flux, circulation, and conservation laws.

Chapter 27 provides a synthesis and bridge to graduate study.

---

## Teaching design

Each chapter is written in a consistent structure:

1. Conceptual motivation
2. Core definitions and formulas
3. Worked examples
4. Geometric interpretation
5. Python-based visualization or computation
6. Connections to statistics, data science, AI, machine learning, or applied mathematics
7. Practice problems and synthesis questions

This structure is intended to support lectures, independent reading, active learning, computational labs, and project-based assignments.

---

## Technology philosophy

The computational parts of the book are not meant to replace mathematical reasoning. They are meant to strengthen it.

Python is used to:

- draw geometric objects that are hard to visualize by hand,
- approximate derivatives and integrals,
- simulate probability models,
- explore optimization dynamics,
- check symbolic formulas numerically,
- connect calculus to modern scientific computing.

Students should learn to move between formulas, pictures, numerical experiments, and written explanations.

---

## Contributing and development notes

This repository is organized as a Quarto book. Suggested development workflow:

```bash
git clone https://github.com/wanghemath/Book-CalculusMulti.git
cd Book-CalculusMulti
quarto preview
```

When editing chapters:

- Keep chapter files inside `chapters/`.
- Keep notebooks inside `labs/`.
- Keep standalone interactive pages inside `htmls/`.
- Use `$...$` for inline math and `$$...$$` for display math.
- Use single quotes for YAML figure captions containing LaTeX.
- Avoid hard-coding local absolute paths.

---

## License and use

This repository is intended for educational use. Please check the repository license before redistributing or adapting the materials.

---

## Author

**He Wang**  
Department of Mathematics  
Northeastern University

Website: <https://wanghemath.github.io/>
