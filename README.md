# Impact of Education on Annual Salary and Weekly Working Hours

## Problem / Research Question
Does a person's education level influence their annual salary and weekly working hours? This project analyzes a dataset from New York State to visualize these relationships and uncover patterns across different educational backgrounds.

## Dataset Source and Usage Permissions
The dataset (`age_salary_hours.csv`) is based on the American Community Survey (ACS) Public-Use Microdata Samples (PUMS) 2017 one-year estimates. It is publicly available for educational and research purposes.

## Methods and Tools Used
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Squarify
- **Methods:** Data filtering (excluded individuals over 65 to focus on the active workforce), Treemap for distribution analysis, and Violin Plots for statistical distribution analysis.

## Key Findings and Limitation
**Key Findings:** 
1. Higher education levels (Bachelor's degree or higher) correlate with significantly higher median annual salaries and a wider spread of income (greater variance).
2. Weekly working hours are relatively consistent across education levels, though slight variations exist.
**Limitation:** The dataset only covers New York State and does not account for specific occupations, years of experience, or cost of living variations, which are significant factors in salary determination.

## Instructions for Running the Analysis
1. Clone this repository.
2. Install the required dependencies: `pip install -r requirements.txt`
3. Ensure the `age_salary_hours.csv` dataset is in the same directory.
4. Open `MC642881_Activity7.06.ipynb` in Jupyter Notebook and run all cells.
