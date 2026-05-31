# E-Commerce Sales Analytics

Project notebooks and data for analyzing an e‑commerce sales dataset (Superstore). This repository contains a Jupyter notebook that explores sales, profit, and customer behaviour with visualisations and basic modeling.

## Contents
- `main.ipynb` — primary analysis notebook (exploration, visualisations, insights)
- `superstore analysis.csv` — cleaned dataset used by the notebook
- `Notes.md` — analyst notes and observations
- `screenshot/` — output images and screenshots

## Requirements
- Python 3.8+
- Typical Python libraries used:
	- `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`, `jupyter`

Install quickly with:

```bash
python -m pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

Or create a virtual environment and install:

```bash
python -m venv .venv
source .venv/Scripts/activate  # PowerShell/Windows: .\.venv\Scripts\Activate.ps1
python -m pip install -U pip
python -m pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

## Usage
1. Start Jupyter Lab or Notebook:

```bash
jupyter lab
# or
jupyter notebook
```
2. Open `main.ipynb` and run the cells top-to-bottom.
3. The notebook reads `superstore analysis.csv` from the repo root; ensure the file is present.

## What you'll find
- Data cleaning and validation steps
- Exploratory data analysis: sales, profit, discount analysis, regional breakdowns
- Visualisations (bar, line, heatmaps, and interactive charts)
- Example predictive modeling pipeline (optional)

## Notes
- If the notebook errors on missing packages, install the missing dependency and restart the kernel.
- Large visuals/screenshots are in `screenshot/`.

## License & Contact
This repo is an analysis project. For questions, open an issue or contact the author.
