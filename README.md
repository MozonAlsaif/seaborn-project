# Seaborn Statistical Visualization Project

## Overview
This project explores statistical data visualization using **Seaborn** on the built-in `tips` dataset. It covers distribution plots with grouping, faceted display of categorical distributions, and cumulative distribution functions, each with custom styling and color palettes.

## Technologies Used
- Python
- Jupyter Notebook
- Seaborn
- Matplotlib
- Pandas

## Key Concepts / Skills Demonstrated
- Loading a built-in dataset with `sns.load_dataset('tips')`
- Applying global plot styles with `sns.set_style()` and `sns.set(font_scale=...)`
- Creating a step histogram of a numeric variable grouped by a categorical variable (`sns.histplot` with `hue` and `element='step'`)
- Building a grouped/dodged distribution plot across categories with a custom palette and explicit hue order (`sns.displot`)
- Plotting an Empirical Cumulative Distribution Function (`sns.ecdfplot`) grouped by category with custom color palette and line width

## Project Files
- `Seaborn_Project.ipynb` — Jupyter notebook containing all Seaborn visualization exercises and their outputs.

## How to Run
1. Ensure Python 3 and Jupyter are installed.
2. Install the required dependencies:
   ```bash
   pip install seaborn matplotlib pandas
   ```
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook Seaborn_Project.ipynb
   ```
4. Run all cells from top to bottom. The `tips` dataset is loaded automatically via Seaborn's built-in dataset repository (requires internet access on first load).

## Requirements / Dependencies
- Python 3.x
- Jupyter Notebook
- `seaborn`
- `matplotlib`
- `pandas`
- Internet access on first run (to download the built-in `tips` dataset)
