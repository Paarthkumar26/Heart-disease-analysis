# Heart Disease Data Exploration

A Python notebook exploring a heart disease dataset. It examines the data, handles zero values in cholesterol and resting blood pressure, visualizes feature distributions and outcome relationships, encodes categorical features, and scales numeric columns.

## Files

- `heart-disease-analysis.ipynb` — Jupyter notebook
- `heart.csv` — dataset used by the notebook
- `requirements.txt` — Python dependencies

## Run it

1. Install Python 3.10 or newer.
2. Install dependencies with `pip install -r requirements.txt`.
3. Launch Jupyter with `jupyter notebook`.
4. Open the notebook in this folder and run cells from top to bottom.

The notebook uses `%pip` to install `sheryanalysis` in its own cell. If you already installed dependencies from `requirements.txt`, you can skip that cell.

## Scope and caveats

This is an exploratory data analysis and preprocessing exercise. It does not train or validate a diagnostic model, and it is not medical advice. Replacing zero values with the feature mean is a simple demonstration and may not be appropriate for clinical analysis. Check the original dataset source and license before redistributing `heart.csv` in a public repository.
