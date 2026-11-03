# Apex-internship-Assignment-2
Data Cleaning concepts

## Project
Data Cleaning & Preprocessing Using Python with the UCI Wine Quality dataset.

## Dataset
UCI Machine Learning Repository — Wine Quality:
https://archive.ics.uci.edu/dataset/186/wine+quality

The notebook combines red wine (1,599 rows) and white wine (4,898 rows), for 6,497 rows before cleaning. It has 11 numeric input attributes and a quality score; a `wine_type` column is added to distinguish red and white wine.

## Files
- `ApexLark_Day2_Data_Cleaning.ipynb` — complete notebook
- `ApexLark_Day2_Data_Cleaning.py` — Python script version
- `Data_Cleaning_Preprocessing_Report.pdf` — task report

## How to run
1. Install Python 3.
2. Install dependencies:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. Open the notebook:
   `jupyter notebook`
4. Run all cells from top to bottom. Internet access is needed for the first dataset download.
5. The cleaned CSV will be saved in `outputs/cleaned_wine_quality.csv`.

## Techniques covered
- Dataset inspection (`head`, `tail`, `shape`, `info`, `describe`)
- Missing-value inspection and imputation
- Duplicate removal and standardized column names/text
- Numeric type conversion
- Label encoding
- IQR outlier detection and capping
- Two derived features
- Data validation and five visualizations
- Business insights and model-training recommendations

## Submission reminder
Upload the notebook, PDF report, and this README to a **public GitHub repository**, then submit only the repository URL through the Google Form specified in the internship task sheet. Do not claim that the repository is uploaded until you have actually pushed the files.
