# 📊 Student Performance Analysis

This project explores the factors influencing student performance in exams using a public dataset from Kaggle. The goal is to uncover insights through exploratory data analysis (EDA) and data visualization.

---

## 📂 Dataset

**Source**: [Students Performance in Exams - Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

**Features:**
- `gender`
- `race/ethnicity`
- `parental level of education`
- `lunch`
- `test preparation course`
- `math score`, `reading score`, `writing score`

---

## 🎯 Objectives


- Investigate how the parental level of education impacts con students
- Visualize score distributions across different subjects.
- Provide actionable insights for improving student outcomes.

---

## 🛠️ Tools & Technologies

- **Python**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Notebook**: Jupyter

---

## 🧪 Process

1. **Data Cleaning**
   - Checked for missing values and inconsistent entries.
2. **Exploratory Data Analysis**
   - Analyzed relationships between categorical variables and exam scores.
   - Visualized distributions and correlations.
3. **Insights & Recommendations**
   - Highlighted key findings with potential implications.

---

## 📈 Key Findings

- Since the population is not the same for all the groups the correlation between the entire populatio and the sample was different
- Parental education level doesnt correlates with student performance.

---

## 📌 How to Use

Clone the repository and run the Jupyter notebook:

```bash
git clone https://github.com/yourusername/student-performance-analysis.git
cd student-performance-analysis
jupyter notebook Student_Performance_Analysis.ipynb
