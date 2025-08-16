# Student Engagement Analytics

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hellosultan/student-engagement-analytics/blob/main/analysis.ipynb)

This project demonstrates a simple workflow for analyzing **synthetic student engagement data** stored in SQLite.  
It includes a Jupyter Notebook with SQL queries, visualizations, and CSV exports for quick review.

---

## 📂 What's Inside

- **`analysis.ipynb`** — main notebook (SQL queries + plots)
- **`reports/figures/`** — generated outputs (CSV + plots)
  - `grade_bands.csv`
  - `risk_by_attendance_decile.csv`
  - `by_gender.csv`
  - Histograms (`hist_age.png`, `hist_avg_grade.png`, `hist_attendance_rate.png`, etc.)
- **`data/`** — synthetic SQLite DB (`students.db`) auto-created by notebook  
  _(not committed — generated locally or in Colab)_

---

## 🚀 Quick Start (Local)

```bash
# (optional) if you use conda
conda activate student-engagement 2>/dev/null || true

# minimal dependencies
pip install pandas matplotlib jupyter sqlite3
```

Run the notebook:

```bash
jupyter lab analysis.ipynb
```

---

## ▶️ Run in Google Colab

Click the badge above ☝ to open the notebook directly in Colab.  
The notebook includes setup cells that will:

1. Clone this repo inside Colab
2. Auto-create the `students.db` SQLite database
3. Run SQL queries + visualizations
4. Export CSVs into `reports/figures/`

---

## 📊 Example Outputs

- Grade distribution by band
- Attendance risk analysis by decile
- Engagement by gender
- Histograms for age, attendance, grades, parent contacts, late submissions

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share.
