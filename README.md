<div align="center">

<img src="https://cdn.simpleicons.org/numpy/013243" width="40" height="40" alt="numpy logo" />

# NumPy Practice

A structured, hands-on journey through **NumPy** — each folder is one topic, each notebook mixes **little theory with real code**.

<br/>

[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![NumPy](https://img.shields.io/badge/NumPy-1.26-013243?style=for-the-badge&logo=numpy&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)]()
[![Notebooks](https://img.shields.io/badge/Notebooks-15-blue?style=for-the-badge)]()
[![Made with ❤️](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F-black?style=for-the-badge)]()

</div>

---

## About

This repository demonstrates the essential workflow of **numerical computing** with NumPy:

<img src="https://api.iconify.design/material-symbols/add-box.svg?color=%23013243" width="20" height="20" alt="create"/> **Create**
→ <img src="https://api.iconify.design/material-symbols/grid-view.svg?color=%23013243" width="20" height="20" alt="shape"/> **Shape**
→ <img src="https://api.iconify.design/material-symbols/crop.svg?color=%23013243" width="20" height="20" alt="select"/> **Select**
→ <img src="https://api.iconify.design/material-symbols/transform.svg?color=%23013243" width="20" height="20" alt="transform"/> **Transform**
→ <img src="https://api.iconify.design/material-symbols/calculate.svg?color=%23013243" width="20" height="20" alt="compute"/> **Compute**
→ <img src="https://api.iconify.design/material-symbols/cleaning-services.svg?color=%23013243" width="20" height="20" alt="clean"/> **Clean**

The notebooks are numbered — **start at `01-basic`** and work your way up. Every topic ends with a **Summary** and a pointer to the next one.

---

## 📚 Learning Path

| # | Topic | What you'll learn |
|---|-------|-------------------|
| <img src="https://api.iconify.design/material-symbols/view-module.svg?color=%23013243" width="22" height="22" alt="basics"/> | **[01 · NumPy Basics](01-basic/01-basic.ipynb)** | `ndarray`, `np.array`, `zeros`, `ones`, `full`, `arange`, `linspace`, `eye`, attributes (`shape`, `dtype`, `ndim`) |
| <img src="https://api.iconify.design/material-symbols/crop.svg?color=%23013243" width="22" height="22" alt="indexing"/> | **[02 · Indexing & Slicing](02-indexing-slicing/02-indexing-slicing.ipynb)** | 1D/2D indexing, negative indexing, `start:stop:step`, boolean masks, views vs copies |
| <img src="https://api.iconify.design/material-symbols/transform.svg?color=%23013243" width="22" height="22" alt="manipulation"/> | **[03 · Array Manipulation](03-array-manipulation/03-array-manipulation.ipynb)** | `reshape()`, `ravel()` / `flatten()`, `.T`, `concatenate`, `vstack`, `hstack`, `np.flip` |
| <img src="https://api.iconify.design/material-symbols/calculate.svg?color=%23013243" width="22" height="22" alt="operations"/> | **[04 · Math Operations](04-math-operations/04-math-operations.ipynb)** | element-wise arithmetic, ufuncs (`sqrt`, `abs`, `exp`), aggregations, `axis=`, `argmin`/`argmax`, masks, `np.where` |
| <img src="https://api.iconify.design/material-symbols/hub.svg?color=%23013243" width="22" height="22" alt="broadcasting"/> | **[05 · Broadcasting](05-broadcasting/05-broadcasting.ipynb)** | the broadcasting rules, scalar + array, column + row grids, normalising data, vectorisation speed |
| <img src="https://api.iconify.design/material-symbols/data-loss-prevention.svg?color=%23013243" width="22" height="22" alt="missing"/> | **[06 · Handling Missing Values](06-missing-values/06-missing-values.ipynb)** | `np.isnan`, `np.isinf`, `np.isfinite`, `nan_to_num`, filtering, `nanmean` / `nansum` |
| <img src="https://api.iconify.design/material-symbols/select-all.svg?color=%23013243" width="22" height="22" alt="fancy indexing"/> | **[07 · Fancy Indexing](07-fancy-indexing/07-fancy-indexing.ipynb)** | integer-array indexing, boolean indexing, `np.take`, `np.choose`, combining masks |
| <img src="https://api.iconify.design/material-symbols/grid-on.svg?color=%23013243" width="22" height="22" alt="linear algebra"/> | **[08 · Linear Algebra](08-linear-algebra/08-linear-algebra.ipynb)** | `np.matmul` / `@`, `dot`, `transpose`, `linalg.inv`, `solve`, `eig`, `norm`, `trace` |
| <img src="https://api.iconify.design/material-symbols/functions.svg?color=%23013243" width="22" height="22" alt="ufuncs"/> | **[09 · Universal Functions](09-universal-functions/09-universal-functions.ipynb)** | ufunc basics, `out=`, `reduce` / `accumulate`, `outer`, broadcasting ufuncs, custom ufuncs |
| <img src="https://api.iconify.design/material-symbols/casino.svg?color=%23013243" width="22" height="22" alt="random"/> | **[10 · Random Numbers](10-random-numbers/10-random-numbers.ipynb)** | `default_rng`, seeds, distributions, sampling, shuffling, random walks, Monte Carlo, bootstrapping |
| <img src="https://api.iconify.design/material-symbols/sort.svg?color=%23013243" width="22" height="22" alt="sorting"/> | **[11 · Sorting & Searching](11-sorting-searching/11-sorting-searching.ipynb)** | `sort`, `argsort`, `partition`, `searchsorted`, `where` / `nonzero`, `unique`, `bincount` |
| <img src="https://api.iconify.design/material-symbols/database.svg?color=%23013243" width="22" height="22" alt="structured arrays"/> | **[12 · Structured Arrays](12-structured-arrays/12-structured-arrays.ipynb)** | field dtypes, `arr["field"]`, record arrays, `np.rec.fromarrays`, filtering and sorting tables |
| <img src="https://api.iconify.design/material-symbols/save.svg?color=%23013243" width="22" height="22" alt="file io"/> | **[13 · File I/O](13-file-io/13-file-io.ipynb)** | `loadtxt` / `savetxt`, `genfromtxt`, `save` / `load` (`.npy`), `savez` (`.npz`), `memmap` |
| <img src="https://api.iconify.design/material-symbols/bolt.svg?color=%23013243" width="22" height="22" alt="performance"/> | **[14 · Performance](14-performance/14-performance.ipynb)** | C/F ordering & strides, views vs copies, vectorisation vs loops, `fromiter`, `ufunc.at`, `einsum`, dtypes |
| <img src="https://api.iconify.design/material-symbols/rocket-launch.svg?color=%23013243" width="22" height="22" alt="workflow"/> | **[15 · Analysis Workflow](15-analysis-workflow/15-analysis-workflow.ipynb)** | a full pipeline: generate, inspect, clean, transform, group, aggregate, report, persist |

---

## ⚙️ Prerequisites

<div align="center">

| | |
|---|---|
| <img src="https://cdn.simpleicons.org/python/3776AB" width="20" height="20" alt="python"/> | Python 3.x |
| <img src="https://cdn.simpleicons.org/jupyter/F37626" width="20" height="20" alt="jupyter"/> | Jupyter Notebook or JupyterLab |
| <img src="https://cdn.simpleicons.org/numpy/013243" width="20" height="20" alt="numpy"/> | NumPy (`pip install numpy`) |

</div>

---

## 🚀 Getting Started

1. **Clone** the repository:

```bash
git clone https://github.com/Dev-with-Mouzan/Numpy.git
cd Numpy
```

2. **Install** the required libraries:

```bash
pip install numpy jupyter
```

3. **Launch** Jupyter and open any notebook — the folders are numbered so the order is clear:

```bash
jupyter notebook
```

---

## 🧭 Suggested Order

Work through the notebooks in numerical order. Each one ends with a **Summary** and a pointer to the next topic:

**Core (01–06)** — the fundamentals every NumPy user needs:

1. [01 · NumPy Basics](01-basic/01-basic.ipynb) — create arrays and learn their attributes
2. [02 · Indexing & Slicing](02-indexing-slicing/02-indexing-slicing.ipynb) — read elements and sub-arrays
3. [03 · Array Manipulation](03-array-manipulation/03-array-manipulation.ipynb) — reshape, flatten and combine
4. [04 · Math Operations](04-math-operations/04-math-operations.ipynb) — arithmetic, aggregations and conditions
5. [05 · Broadcasting](05-broadcasting/05-broadcasting.ipynb) — combine different shapes without loops
6. [06 · Handling Missing Values](06-missing-values/06-missing-values.ipynb) — deal with `NaN` and infinity

**Advanced (07–15)** — when you're ready to go deeper:

7. [07 · Fancy Indexing](07-fancy-indexing/07-fancy-indexing.ipynb) — select arbitrary elements in one go
8. [08 · Linear Algebra](08-linear-algebra/08-linear-algebra.ipynb) — matrices, inverses, solving systems, eigenvalues
9. [09 · Universal Functions](09-universal-functions/09-universal-functions.ipynb) — NumPy's vectorised function engine
10. [10 · Random Numbers](10-random-numbers/10-random-numbers.ipynb) — generators, distributions and simulation
11. [11 · Sorting & Searching](11-sorting-searching/11-sorting-searching.ipynb) — order and find values fast
12. [12 · Structured Arrays](12-structured-arrays/12-structured-arrays.ipynb) — tables inside an array
13. [13 · File I/O](13-file-io/13-file-io.ipynb) — read and write arrays to disk
14. [14 · Performance](14-performance/14-performance.ipynb) — memory layout and vectorisation tricks
15. [15 · Analysis Workflow](15-analysis-workflow/15-analysis-workflow.ipynb) — the full pipeline, end to end

---

<div align="center">

**Built for learning NumPy, one notebook at a time.** &nbsp;|&nbsp;
[Dev-with-Mouzan](https://github.com/Dev-with-Mouzan)

<sub>Icons: [Material Symbols](https://iconify.design) · [Simple Icons](https://simpleicons.org) · [Shields.io](https://shields.io)</sub>

</div>
