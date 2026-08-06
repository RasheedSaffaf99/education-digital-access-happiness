# Education, Digital Access, and Happiness

Cross-country analysis of how education and digital connectivity relate to national happiness scores.

The notebook builds a country-year dataset, checks multicollinearity and regression assumptions, and compares OLS, ridge, lasso, elastic net, random forest, gradient boosting, and PCA regression. It also compares nested models to estimate the incremental contribution of education and digital-access variables.

## Repository contents

- `notebooks/analysis.ipynb` — data preparation, analysis, modeling, diagnostics, and figures
- `data/` — source extracts and prepared modeling datasets
- `figures/` — selected figures from the analysis
- `reports/final-report.pdf` — submitted project report

## Run

Create a Python environment and install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Open `notebooks/analysis.ipynb` and run the cells in order. Paths are relative to the notebook directory.

## Data note

The analysis combines World Happiness Report files with education, internet-access, and mobile-connectivity data. Confirm each source's redistribution terms before making the repository public. The notebook records the cleaning and merging steps used to create the final modeling table.

## Attribution

Academic project completed for Georgia Tech OMS Analytics. The analysis and interpretations are the author's work unless otherwise noted in the report.
