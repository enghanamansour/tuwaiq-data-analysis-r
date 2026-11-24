# Tuwaiq Data Analysis with R

A collection of R notebooks and assignments completed during the
Data Analysis with R program at Tuwaiq Academy, covering data frames,
statistics, data cleaning, and visualization.
Notebooks were written in Google Colab using the R kernel.

## Notebooks

| # | Notebook | Topics |
|---|----------|--------|
| 1 | `01_r_statistics_mtcars.ipynb` | Built-in `mtcars` dataset, `summary()`, min/max, mean/median/mode, percentiles, quartiles, outliers |
| 2 | `02_iris_exercise.ipynb` | `iris` dataset, `head()`, `which.max()`, `aggregate()`, colored scatter plot by species |
| 3 | `03_r_basics_charts_and_dataframes.ipynb` | Bar chart and pie chart, building and filtering a data frame, adding columns, sorting, `ifelse()` |
| 4 | `04_employee_salary_analysis.ipynb` | End-to-end salary analysis (see below) |

## Featured project: Employee Salary Analysis

Analysis of an employee salary dataset (30 employees, 13 columns: department,
occupational level, HR salary, payroll salary, compa-ratio, performance rating, etc.).

**Steps covered:**
- Importing data and creating a data frame
- Exploration (`dim`, `names`, `str`)
- Cleaning (missing values, type conversion, duplicate removal)
- Descriptive statistics (mean, median, min, max, SD, quartiles)
- Grouping by department and occupational level
- Filtering and sorting (top salaries, salary threshold)
- Visualization: histogram, bar chart, boxplot, scatter plot, compa-ratio histogram
- Correlation between HR salary and payroll salary

**Key findings:**
- HR salary and payroll salary are almost identical (correlation ≈ 0.9997).
- Senior employees earn much more than Mid and Junior employees
  (average ≈ 92.7K vs 74.9K vs 52.3K).
- The Markets department has the highest average salary (≈ 73.6K) and HR has the lowest (≈ 64.5K).

> Note: the original assignment template mentions overtime pay and job title,
> but this dataset does not include those columns, so the analysis uses
> `HR_Salary`, `Payroll_Salary`, and `Occupational_Level` instead.

## Project structure

```
tuwaiq-d