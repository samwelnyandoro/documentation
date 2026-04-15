# AT2 – Data Analytics: University Students Performance & Study Habits 2026

## Project Overview

This project analyses the **University Students Performance & Study Habits 2026** dataset from Kaggle. The Jupyter Notebook (`AT2_Deliverable_A.ipynb`) performs a full data analytics pipeline including data loading, exploratory data analysis, correlation analysis, and group-based correlation analysis.

---

## Files Included

| File | Description |
|------|-------------|
| `AT2_Deliverable_A.ipynb` | Jupyter Notebook — Deliverable A (Python program) |
| `AT2_Deliverable_B.docx` | Word Report — Deliverable B (1200–1500 word report) |
| `README.md` | This file |

---

## Requirements

- Python 3.10 or higher
- pip (comes bundled with Python)

---

## Setup Instructions

### Step 1 — Install Python

Download and install Python from [https://www.python.org/downloads](https://www.python.org/downloads).

> **Important (Windows):** During installation, check the box **"Add Python to PATH"** before clicking Install.

---

### Step 2 — Download the Dataset

1. Go to the dataset page on Kaggle:  
   [https://www.kaggle.com/datasets/asifxzaman/university-students-performance-and-study-habits2026](https://www.kaggle.com/datasets/asifxzaman/university-students-performance-and-study-habits2026)
2. Create a free Kaggle account if you don't have one
3. Click **Download** and save the CSV file

---

### Step 3 — Set Up Your Project Folder

Create a folder (e.g. `AT2` on your Desktop) and place the following files inside it:

```
AT2/
├── AT2_Deliverable_A.ipynb
├── AT2_Deliverable_B.docx
├── README.md
└── university_students_performance_study_habits2026.csv
```

> **Important:** The CSV file must be named exactly:
> `university_students_performance_study_habits2026.csv`

---

### Step 4 — Install Required Libraries

Open your terminal (Mac/Linux) or Command Prompt (Windows), navigate to your project folder, and run:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

---

### Step 5 — Launch Jupyter Notebook

In the same terminal, run:

```bash
python -m jupyter notebook
```

This will open a browser window. Click on `AT2_Deliverable_A.ipynb` to open the notebook.

---

### Step 6 — Run the Notebook

In the menu bar click:

```
Kernel → Restart & Run All
```

This runs every cell from top to bottom and generates all outputs, charts, and correlation matrices.

---

## Notebook Structure

| Section | Description |
|---------|-------------|
| 1. Data Loading & Inspection | Loads the CSV, displays first/last 5 rows, checks data types and missing values |
| 2. Variable Selection | Removes irrelevant or high-missingness columns with justification |
| 3. Exploratory Data Analysis | Descriptive statistics, histograms, bar charts, and box plots |
| 4. Correlation Analysis | Pearson correlation matrix heatmap with ranked pair analysis |
| 5. Group-Based Correlation | Segmented correlation matrices by gender and field of study |
| 6. Summary of Findings | Written interpretation of all results |

---

## Troubleshooting

| Error | Fix |
|-------|-----|
| `ModuleNotFoundError: No module named 'pandas'` | Run `pip install pandas` in your terminal |
| `FileNotFoundError: university_students...csv` | Make sure the CSV is in the same folder as the notebook and the filename matches exactly |
| `jupyter: command not found` | Run `pip install --upgrade jupyter` and try again |
| Blank charts / no output | Go to **Kernel → Restart & Run All** to re-run all cells |

---

## Dataset Reference

> asifxzaman. (2026). *University Students Performance & Study Habits 2026*. Kaggle.  
> https://www.kaggle.com/datasets/asifxzaman/university-students-performance-and-study-habits2026
