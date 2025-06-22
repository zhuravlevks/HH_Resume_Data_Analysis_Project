# 📊 HeadHunter Resume Analysis Project

## 🔍 Project Overview
This project focuses on preprocessing and analyzing resume data from HeadHunter (hh.ru) to prepare for salary prediction modeling. The dataset contains information about job seekers who didn't specify their desired salary.

## 📂 Dataset Access
The original dataset is available for download:  
🔗 [Download Resume Dataset](https://drive.google.com/file/d/1ardsAFX6n9_GP9VxOD-uoeqUvA4oBaU7/view?usp=sharing)  
*(Please ensure you have access to the Google Drive file)*

## 🏗️ Project Structure
The project consists of 4 main stages:

### 1. 🔎 Basic Data Analysis
- 🧹 Initial data exploration with pandas
- 🔎 Data types and missing values analysis
- 📈 Statistical overview of features

### 2. ⚙️ Data Transformation
- 💰 Salary amount and currency extraction
- 🔄 Currency conversion to RUB using exchange rates
- 🏷️ One-Hot Encoding for categorical features
- 🎂 Age and work experience extraction

### 3. 📊 Exploratory Data Analysis
- 📊 Interactive visualizations with Plotly
- 📉 Distribution analysis (histograms, boxplots)
- 🔗 Correlation analysis

### 4. 🧼 Data Cleaning
- 🧩 Handling missing values
- 🎯 Outlier detection and treatment
- ✔️ Data consistency checks

## 💻 Technical Stack
- 🐍 **Python 3**
- 🐼 **Pandas** - Data manipulation and analysis
- 🔢 **NumPy** - Numerical operations
- 📉 **Matplotlib/Seaborn** - Basic visualizations
- ✨ **Plotly** - Interactive visualizations

## ⚙️ Requirements
```bash
pip install pandas numpy matplotlib seaborn plotly
