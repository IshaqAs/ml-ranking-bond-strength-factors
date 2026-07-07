# ml-ranking-bond-strength-factors
This repository contains the machine-learning pipeline used for the revised manuscript analysis.

## Files

- `ml_pipeline_github_formatted.py` — sequential Python script version.
- `Revised_ML_GitHub_formatted.ipynb` — notebook version with the same workflow.
- `requirements.txt` — Python package dependencies.

## How to run

1. Create a virtual environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Place the Excel data file in the project root and name it:

```text
inputxlxs1.xlsx
```

Alternatively, edit `DATA_PATH` in the configuration section.

4. Run the notebook or script from top to bottom.

## Outputs

All figures and CSV outputs are saved to:

```text
analysis_outputs/
```

## Reproducibility

The global random seed is fixed as:

```python
RANDOM_STATE = 42
```

The hyperparameter ranges are retained from the manuscript to maintain methodological consistency during revision.
