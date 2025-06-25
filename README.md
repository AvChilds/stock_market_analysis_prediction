# Data Science Project: Stock Analysis & Performance Prediction of S&P 500 Companies

---

## 🙏 Introduction

Thank you for checking out our repository! This is a **group project** completed as our first Data Science assignment, in which we achieved **near full marks**. I served as **Project Lead**, overseeing the **PEG & ROA analyses**, authoring the **project document** and **presentation**, and contributing to the **machine learning** component.

---

## 🌟 Team Members

| Name                    | Role                            |
|-------------------------|---------------------------------|
| **Avril Childs**        | Project Lead                    |
| Laura Davies            | GitHub Coordinator              |
| Wei Shi                 | Technical Lead                  |
| Bushra Abodher          | Task Coordinator                |
| Laura Lloyd             | Submission Lead                 |
| Esther Nunsubuga        | Presentation Lead               |

---

## 🎯 Project Aims & Objectives

We set out to analyse and predict S&P 500 stock performance by combining **financial indicators** with **macroeconomic data**. Specifically, we aim to:

1. **Identify** financial metrics most strongly correlated with outperformance  
2. **Assess** the impact of CPI & Federal Reserve interest rates on overall market trends  
3. **Build** a machine-learning model to select **10 top stocks** each month likely to outperform

---

## 📅 Key Dates

| Milestone                         | Date           |
|-----------------------------------|----------------|
| Proposal Submission 📋            | 11 April 2025  |
| Discussion with Instructor        | w/c 14 April   |
| Final Submission 📚               | 4 May 2025     |
| Project Presentation 📢           | 9 May 2025     |

---

## 📂 Repository Structure


### 📁 Raw_Data
- `Stock_Screening_V2.xlsx` – initial dataset for all feature analyses  
- `Stock_Screening_Live.xlsx` – live data used in the ML phase

### 📁 Financial_Feature_Analysis
Contains **8 Jupyter Notebooks** (`.ipynb`), each cleaning and analysing one financial feature.

### 📁 Cleaned_Data
Exported **CSV** files from feature analyses, ready for modelling:
- `cleaned_ROA.csv`  
- `cleaned_PEG.csv`  
- …and others

### 📁 Macroeconomic_Analysis
**2 Notebooks** covering:
- Consumer Price Index (CPI)  
- Federal Reserve Interest Rate

### 📁 ML_Predictive_Modelling
- `Stock_Screening_Project.ipynb` – end-to-end ML workflow  
- `Top10_Stock_Predictions.csv` – model outputs

### 📄 Project_Documentation-Stock_Analysis_Prediction.pdf
Full project spec: objectives, methodology, requirements, results & recommendations.

### 📄 Key_Financial_Terms.pdf
Glossary of financial terminology used across analyses.

---

## 🚀 Getting Started

All analyses are in **Jupyter Notebooks**. We recommend reading the PDF documentation first for context.

### Prerequisites

- Python 3.7+  
- Jupyter Notebook or JupyterLab  

### Install Dependencies

In your local environment, run:

```bash
pip install \
  pandas \
  numpy \
  scipy \
  matplotlib \
  seaborn \
  plotly \
  scikit-learn \
  joblib
```


### Financial Feature Analysis

We used the Excel file **Stock_Screening_CFG v2.xlsx** as our raw data (found in the "Raw_Data" folder).

1. Pull down this file from the online repository or download the file directly from the repository, taking note of the file path.
2. Open up each feature analysis file from the folder "Financial_Feature_Analysis" using Jupyter Notebooks.
3. Update the file path at the top of the code, within the pd.read_excel(), with the file path of your local copy of **Stock_Screening_CFG v2.xlsx**, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. Execute all cells to load the raw Excel data and perform data cleaning and analysis
5. The cleaned data will be saved in your local folder as CSV files (e.g. cleaned_roe.csv, cleaned_CFO.csv).
6. Continue to run the code to view the analysis of the individual features including analysing:
- Means & Medians
- Correlations
- Distributions
- Significance
- Results/Conclusions


### Macroeconomic Factor Analysis

This section utilises online data sources which we're able to obtain using APIs.

1. Pull down the files from the online repository or download the file directly from the repository (Found in the folder "Macroeconomic_Analysis").
2. Open up each analysis file using Jupyter Notebooks.
3. Update the file path at the top of the code to point to your local copy of the raw data source, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```

Execute all cells to pull the data via the API and have the code run through the analysis.

### Machine Learning (ML)

The cleaned data .csv exports were used for the machine learning aspect of this project.

1. All cleaned data sets are available in the "Cleaned_Data" folder - Download to your local repository.
2. Download the file to run for this aspect of the project: "Stock_Screening_Project.ipynb" (Found in the "ML_Predictive_Modelling" folder).
3. Update the file path at the top of the code to point to your local copy of the cleaned data sources along with the original stocks_screening_v2.xlsx file, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. At the section "For Live Monthly Workflow", you will need to update the file path for the "Stock_Screening_Live.xlsx" file.
5. Execute all cells to load the data and run the code.
6. The Top 10 stocks which are likely to outperform the market are then saved to a .csv file (Example file found in the "Results" folder).
