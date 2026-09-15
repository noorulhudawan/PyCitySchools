# 🏫 PyCity Schools Analysis

A Pandas-based data analysis project exploring student performance (math & reading scores) across a school district of 15 schools and 39,170 students — comparing outcomes by school type, size, and budget per student.

This project was completed as part of my journey learning **Python & Pandas**, and marks the completion of my Pandas module. 🎉

## 📊 Project Overview

Using two raw datasets — school-level data (type, size, budget) and student-level data (scores) — this project merges, cleans, and aggregates the data with Pandas to answer questions like:

- How does the district perform overall in math and reading?
- Which schools have the highest and lowest passing rates?
- Does spending more per student improve outcomes?
- Do smaller schools perform better than larger ones?
- Does school type (Charter vs. District) affect performance?

## 🔑 Key Findings

- **Charter schools significantly outperform District schools** — 90.4% overall passing rate vs. 53.7%, despite similar per-student spending.
- **Higher spending per student did *not* correlate with better outcomes** in this dataset — likely explained by school size/type rather than spending itself.
- **Smaller and mid-sized schools (under 2,000 students)** post ~90% overall passing rates, while **large schools (2,000–5,000 students)** average only 58.3%.
- **Reading scores are consistently stronger than math scores** across every school and grade level.
- Performance is fairly stable across grades 9–12 within each school, suggesting gaps are established before high school.

## 🛠️ Tools & Skills Used

- **Python**
- **Pandas** (merging, grouping, aggregation, `pd.cut` binning, DataFrame formatting)
- Jupyter Notebook

## 📁 Repository Contents

| File | Description |
|---|---|
| `PyCitySchools.ipynb` | Main analysis notebook |
| `Resources/schools_complete.csv` | Raw school-level data |
| `Resources/students_complete.csv` | Raw student-level data |
| `PyCitySchools_Analysis_Report.docx` | Formatted written report with tables and key findings |

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/pycity-schools.git
cd pycity-schools
pip install pandas jupyter
jupyter notebook PyCitySchools.ipynb
```

## 📌 Notes

While building this project, I also learned to catch and debug logic errors in Pandas aggregations (e.g., accidentally referencing district-wide values instead of per-school groupby results) — a great reminder to always sanity-check summary statistics before trusting them.

## ✅ Status

Pandas fundamentals: **completed**.
Next up: Matplotlib / data visualization.

---

*Feel free to fork, explore, or reach out with feedback!*
