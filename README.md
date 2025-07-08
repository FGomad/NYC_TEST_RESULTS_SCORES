# 🎓 NYC Schools SAT Performance Analysis (From my datacamp's data analyst with Pythons Course)

This project analyzes SAT scores across New York City public high schools using Python and pandas. The dataset includes average SAT section scores and school/borough information.

---

## 📁 Dataset

The analysis is based on `schools.csv`, which contains:
- `school_name`
- `borough`
- `average_math`
- `average_reading`
- `average_writing`

---

## 📊 Key Objectives

- Calculate total SAT scores for each school
- Identify the **top 10 performing schools** based on total SAT
- Find **schools with top math performance** (≥ 640 out of 800)
- Analyze **borough-level SAT trends**:
  - Number of schools
  - Average total SAT
  - Standard deviation of total SAT
- Determine which **borough has the most SAT variation**

---

## ✅ Tools Used

- Python
- pandas

---

## 🔍 Results

- A new column `total_SAT` was created
- `top_10_schools`: highest SAT performing schools
- `best_math_schools`: schools scoring ≥ 80% in math
- `largest_std_dev`: borough with the largest standard deviation in SAT scores

---

## 📂 Files

- `schools.csv` — input dataset
- `notebook.ipynb` or `analysis.py` — core analysis code
- `README.md` — project overview

---

## 📬 Contact

For questions or feedback, feel free to open an issue or reach out.
