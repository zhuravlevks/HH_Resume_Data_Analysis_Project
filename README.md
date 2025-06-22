# HeadHunter Resume Analysis Project

## Project Overview
This project focuses on preprocessing and analyzing resume data from HeadHunter (hh.ru) to build a salary prediction model. Many job seekers don't specify their desired salary when creating resumes, so we need to transform and clean the data to enable automated salary estimation.

## Project Structure
The project consists of 4 main stages:

### 1. Basic Data Structure Analysis
- Initial data exploration
- Data types and missing values analysis

### 2. Data Transformation
- Categorical feature processing (One-Hot Encoding)
- Feature extraction (work experience, education, city, etc.)
- Salary conversion to RUB using currency rates

### 3. Exploratory Data Analysis
- Key feature distribution visualization
- Feature relationship analysis
- Anomaly and outlier detection

### 4. Data Cleaning
- Missing value handling
- Duplicate removal
- Outlier filtering

## Technical Stack
- Python 3
- Pandas
- NumPy
- Plotly (for visualization)
- Scikit-learn (for preprocessing)

## Requirements
Install dependencies with:
```bash
pip install pandas numpy plotly scikit-learn
