
# SWYNEX – Exploratory Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

## Objectives
- Explore and understand the dataset.
- Calculate descriptive statistics.
- Analyze passenger survival patterns.
- Create visualizations.
- Identify meaningful insights.

## Dataset
- Dataset: Titanic
- Records analyzed: 784
- Columns: 15
- Missing values: 0

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
SWYNEX-Exploratory-Data-Analysis/
├── data/
│   └── titanic_cleaned.csv
├── charts/
│   ├── survival_by_gender.png
│   ├── survival_by_class.png
│   ├── survival_by_age.png
│   └── survival_by_embarkation.png
├── reports/
│   └── EDA_Report.md
├── eda_analysis.py
├── requirements.txt
└── README.md
```

## Key Findings
1. Overall survival rate: 41.20%.
2. Female survival rate: 74.06%.
3. Male survival rate: 21.59%.
4. First-class survival rate: 63.08%.
5. Children had a 57.35% survival rate.

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the analysis:

```bash
python eda_analysis.py
```

## Output
Four visualizations are saved in the charts folder, and the analysis report is available in the reports folder.

## Conclusion
The analysis highlights differences in survival rates across gender, passenger class, age groups and embarkation towns.

---
Completed as part of SWYNEX Technologies Internship – Task 2.
