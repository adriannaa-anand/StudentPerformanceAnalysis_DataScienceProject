# 📊 Student Performance Analysis

A data science project built using **Tableau Public** to analyze and visualize student academic performance across multiple dimensions including demographics, socioeconomic background, study habits, and school-level trends.

🔗 **Live Dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/adriannaa.anand/viz/StudentPerformanceAnalysis_17761033167850/Dashboard1)

---

## 📁 Project Structure

```
StudentPerformanceAnalysis/
├── Student_Performance_Dataset.xlsx   # Dataset used for analysis (500 student records)
├── README.md                          # Project documentation
```

---

## 📋 Dataset Overview

The dataset contains **500 student records** with **25 fields** covering academic scores, demographics, and lifestyle factors.

| Category | Fields |
|---|---|
| **Student Info** | Student_ID, Gender, Age, Grade_Level, Department |
| **School Info** | School, Location, Semester, Academic_Year |
| **Background** | Parent_Education, Family_Income, Internet_Access |
| **Habits** | Study_Hours_Per_Day, Sleep_Hours, Extracurricular_Activities, Tutoring_Support |
| **Attendance** | Attendance_Percentage |
| **Scores** | Math_Score, Science_Score, English_Score, Social_Studies_Score |
| **Performance** | Total_Score, Average_Score, Grade_Letter, Pass_Fail |

---

## 📊 Dashboard Sheets

The Tableau dashboard consists of **7 interactive sheets**:

### 1. Overall Performance Overview
- Grade distribution (A+, A, B, C, D, F) with Pass/Fail breakdown
- Chart type: Bar chart

### 2. Subject Score Comparison
- Average scores across Math, Science, English, and Social Studies
- Grouped by Department and Grade Level
- Chart type: Grouped bar chart

### 3. Attendance vs Average Score
- Scatter plot showing correlation between attendance and performance
- Color: Pass/Fail status | Size: Study hours per day

### 4. Performance by Gender & Location
- Heat map comparing average scores across Gender × Location (Rural / Suburban / Urban)
- Highlights demographic performance differences

### 5. Study Hours Impact
- Effect of daily study hours on average scores
- Split by Tutoring Support (Yes/No)
- Chart type: Line chart

### 6. School-wise Trend
- Performance trends across 3 academic years (2022–23, 2023–24, 2024–25)
- One line per school (School A, B, C, D)
- Chart type: Line chart

### 7. Socioeconomic Influence
- Heat map of Family Income × Parent Education vs Average Score
- Reveals how background factors influence academic outcomes

---

## 🛠️ Tools Used

- **Tableau Public** — Dashboard creation and visualization
- **Python (pandas, openpyxl, numpy)** — Dataset generation
- **Microsoft Excel / CSV** — Data storage format

---

## 🔍 Key Insights

- Students with higher attendance percentages consistently score higher on average
- Tutoring support shows a positive impact on scores across all study hour ranges
- Urban students tend to perform slightly better than rural students on average
- Family income and parent education level are positively correlated with academic performance
- School performance trends vary year-over-year, indicating institutional differences

---

## 🚀 How to Use

1. Download the `Student_Performance_Dataset.xlsx` file
2. Open [Tableau Public](https://public.tableau.com/) (free)
3. Connect to the Excel file as a data source
4. Recreate or explore the dashboard using the sheet configurations above

Or simply view the published dashboard directly:
🔗 [Student Performance Analysis on Tableau Public](https://public.tableau.com/app/profile/adriannaa.anand/viz/StudentPerformanceAnalysis_17761033167850/Dashboard1)

---

## 👤 Author

**Adriannaa Anand**  
Data Science Project — Student Performance Analysis  
[Tableau Public Profile](https://public.tableau.com/app/profile/adriannaa.anand)
