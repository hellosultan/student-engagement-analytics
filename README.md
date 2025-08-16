# Student Engagement Analytics
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hellosultan/student-engagement-analytics/blob/main/analysis.ipynb)

This project demonstrates a simple workflow for analyzing synthetic student engagement data stored in SQLite.  
It includes a Jupyter notebook with SQL queries and plots, along with exported CSVs for quick review.

## What’s inside
- `analysis.ipynb` — main notebook (SQL + plots)
- `reports/figures/` — CSV outputs:
  - `grade_bands.csv`
  - `risk_by_attendance_decile.csv`
  - `by_gender.csv`
- `data/` — (local) SQLite DB `students.db` created from the synthetic CSV (not committed)

## Quick start (local)
```bash
# (optional) use conda if you have it
conda activate student-engagement 2>/dev/null || true

# minimal deps if you need them
pip install pandas matplotlib jupyter
