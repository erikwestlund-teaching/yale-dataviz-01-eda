# Exercise 1: First Plots and EDA

Part of the workshop **Data Visualization With AI**. Prompts are on the workshop page.

## Open the project

- **RStudio:** open the `.Rproj` file.
- **Positron or VS Code:** open this folder.
- **Claude Code or Codex:** start the tool from a terminal in this folder.

You need R with **tidyverse**, **here**, and **rmarkdown**, and Quarto (bundled with RStudio).

## What's here

| Notebook | Use |
|---|---|
| `notebooks/01_first-plot.qmd` | A first figure with your assistant, then a critique |
| `notebooks/02_grammar.qmd` | Steering with chart names vs. the grammar of graphics |
| `notebooks/03_eda.qmd` | Distributions, categorical data, and group comparisons |
| `notebooks/style-task.qmd` | The task for the skills lesson (run it here first, without a skill) |

Data: PRAMS 2011 subgroup estimates, NHANES 2021–2023, Census race and ethnicity by state, and infant mortality by country. Codebooks are in `inputs/raw/codebooks/`.

## About the folders

This project was created from a [Framework](https://framework.pub) blueprint, so it has the layout of a real analysis project: data in `inputs/raw/` (codebooks in `inputs/raw/codebooks/`), your notebooks in `notebooks/`, and results in `outputs/`. `docs/reference/` holds worked reference notebooks from Erik's data visualization course; compare them with what your assistant produces. You don't need the framework R package.
