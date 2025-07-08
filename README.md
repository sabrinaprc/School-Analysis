# 📊 Student Performance Analysis (StrataScratch)

This project analyzes student performance data from the **StrataScratch Student Performance Analysis** dataset, comparing outcomes in **Mathematics** and **Portuguese language** classes. The analysis includes visual explorations and chi-square tests to identify significant factors impacting student achievement.

---

## 📝 Dataset

Derived from the **StrataScratch Student Performance Analysis** project, the dataset originates from two Portuguese schools and includes features such as:
- Student grades (G1, G2, G3)
- Demographics (age, gender, health, romantic status, etc.)
- Study habits (study time, extra-curricular activities)
- Family and school support
- Internet access, absences, failures, parents' education, and more :contentReference[oaicite:1]{index=1}

---

## 📌 Key Analysis Components

1. **Data Cleaning & Merging**  
   - Load and combine datasets for Math and Portuguese classes.  
   - Select relevant variables for analysis.

2. **Exploratory Data Analysis (EDA)**  
   - Plot histograms and boxplots for distributions of age, study time, failures, and grades for both subjects.

3. **Chi-Square Tests**  
   - **Mathematics:**  
     - Examined associations between school support, family support, extra‑curricular activities, romantic relationships, health status, and final grades (G3).  
   - **Portuguese:**  
     - Tested relationships between gender, internet access, parents' education, and final grades. :contentReference[oaicite:2]{index=2}

4. **Insights & Recommendations**  
   - Based on statistical significance, highlight how factors like school support, romantic relationships (for Math), and parental education (for Portuguese) influence performance.  
   - Discuss potential interventions: enhancing support programs, counseling services, parental engagement, etc.

---

## 🧪 Tech Stack

- **Python** (pandas, matplotlib/seaborn, scipy.stats)  
- **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/sabrinaprc/School-Analysis.git
   cd School-Analysis
