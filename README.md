# Student Well-Being and Academic Performance Analysis

This repository contains a Python script and dataset for analyzing the relationship between student well-being factors and academic performance (CGPA). The analysis includes data exploration, preprocessing, exploratory data analysis (EDA), and key insights supported by visualizations.

---

## Project Overview

- **Dataset**: `student_wellbeing_analysis.csv` — Contains student data with columns such as Student_ID, Hours_Study, Sleep_Hours, Screen_Time, Attendance, Extracurricular (Yes/No), Stress_Level (Low/Medium/High), and CGPA.
- **Script**: `student_analysis.py` — Loads and cleans the data, performs EDA, generates insights, and creates visualizations.
- **Outputs**:
  - `cleaned_student_data.csv` — Cleaned dataset with missing values handled and renamed columns.
  - Visualization PNG files (e.g., `insight1_study_corr.png`) showing relationships and group comparisons.

---

## How to Run the Analysis

1. Install required Python packages (if not already installed):

   ```bash
   pip install pandas matplotlib

2. Place the dataset (student_wellbeing_dataset.csv) in the same folder as the Python script.

3. Run the script:

```bash
python Student_Analysis.py
```

4. Outputs generated:

Console prints with data exploration, preprocessing info, EDA results, and insights.
PNG files with visualizations saved in the same folder.
Cleaned dataset saved as cleaned_student_data.csv. 

---

## Key Insights from the Analysis

Higher study hours correlate positively with CGPA.
Optimal sleep (6-8 hours) is associated with better academic performance.
Increased screen time tends to lower CGPA.
Regular attendance strongly correlates with higher CGPA.
Lower stress levels correspond to better academic outcomes.
Participation in extracurricular activities is linked to higher CGPA.

---

## Notes

Missing values in numerical columns are filled with median values; categorical missing values remain as-is.
The script is designed to handle large datasets (10,000+ rows) efficiently.
Visualizations are created using matplotlib and saved as PNG files.
