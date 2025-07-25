# 🧠 Mental Health in Tech – Data Analysis (Python | SQL | Tableau)

## Project Overview
This project analyzes **mental health treatment trends among working professionals** using the public **OSMI Mental Health in Tech Survey (2014)** dataset.  
It demonstrates end‑to‑end data analytics skills:
- ✅ Data Cleaning & EDA in **Python (Pandas, Matplotlib, Seaborn)**
- ✅ Querying and aggregating insights with **SQL (SQLite)**
- ✅ Dashboard in **Tableau**

---

## 📊 Dataset
**Source:** [Kaggle – Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)

**Key Columns**
- `Age`, `Gender`, `Country`, `state`
- `treatment` – whether respondent sought mental health treatment
- `family_history`, `remote_work`, `wellness_program`, `benefits`, etc.

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| **Python (Google Colab)** | Data cleaning, preprocessing, EDA |
| **SQLite (SQL)** | Querying insights (grouping, aggregations) |
| **Tableau** | Interactive dashboards & visualizations |

---

## 🔑 Key Findings
✔ **Family history:** respondents with family history are more likely to seek treatment (28.67% vs 21.45%).  
✔ **Remote work:** non‑remote workers reported higher treatment rates (34.71% vs 15.41%).  
✔ **Wellness programs:** lack of wellness program associated with higher treatment reporting (33.12%).  
✔ **Gender:** treatment patterns differ across genders with high numbers under males (34.95%).

---

## 📈 Tableau Dashboard
<img width="1185" height="812" alt="image" src="https://github.com/user-attachments/assets/eaf05d66-dc26-4e7c-9dd5-dfe780b5a36c" />


**Dashboard Views**
- 🌍 Top 10 countries with treatment
- 👩‍💻 Treatment % by gender
- 👨‍👩‍👧‍👦 Treatment % by family history
- 🏢 Treatment % vs wellness programs
- 🏠 Treatment % vs remote work

---

## 🚀 How to Run
### 🔹 Python EDA
1. Open `mental_health_analysis.ipynb` in Google Colab.
2. Mount your Google Drive and load `survey_cleaned.csv`.
3. Run cells step by step to see cleaning, EDA, and correlation analysis.

### 🔹 SQL Queries
1. Run `mental_health_queries.sql` or see queries inside notebook. ( Ran in Python Colab and SQL commands also mentioned in separate txt file )
2. SQLite was used to group by gender, country, family history, etc.

### 🔹 Tableau
1. Open `Mental_Health_Analysis.twbx` in Tableau Desktop or Tableau Public.
2. Explore the dashboard.

---

---

## Author
**Haribabu Ambati – MSBA International Student at Barton Business School, Wichita State University**  
*Passionate about Business Analytics, Data Visualization, and Data‑driven insights.*

⭐ If you like this project, feel free to star the repo.
Thank you.


