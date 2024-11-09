# Weighted K-Nearest Neighbors

**Weighted KNN** on a numeric classification dataset: z-score scaling, custom distance/loss,
weight optimization, and comparison with vanilla KNN and feature-subset experiments.

Built for a Machine Learning course assignment.

## What this project covers

- Preprocessing and 90/10 train-test split
- Weighted KNN loss and numerical weight optimization
- Random subsets vs. top-weight feature selection

## Project layout

| File | Description |
|------|-------------|
| `main.ipynb` | Weighted KNN experiments |
| `P3.csv` | Dataset |
| `Project_Description.pdf` | Assignment brief |
| `Report.pdf` | Report |

## Quick start

```bash
python -m venv .venv
.venv\\Scripts\\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Notebook outputs are saved so plots render on GitHub.
