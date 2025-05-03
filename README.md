![alt text](https://codefirstgirls.com/wp-content/uploads/2022/04/CFGDegree-Logo-2.png "CFG Logo")


# CFG Group 5 Project
## Stock Performance Prediction Algorithm

## Group Members 🌟 

1. Laura Davies (GitHub Coordordinator)
2. Avril Childs (Organisational Lead)
3. Wei Shi (Technical Lead)
4. Bushra Abodher (Task Coordinator)
5. Laura Lloyd (Submission Lead)
6. Esther Nunsubuga (Presentation Lead)

## Project Aims & Objectives

The primary objective of this project is to analyse and predict the stock performance of S&P 500 companies by leveraging key financial indicators and macroeconomic data. 

We aim to:
- Identify the financial metrics most strongly correlated with stock outperformance
- Analyse macroeconomic indicators, namely Consumer Price Index (CPI) and Federal Reserve Interest Rates to assess their effect on the S&P 500 index performance.
- Develop a Machine learning model to select 10 stocks each month that are likely to outperform the market based on historical data.

## Key Dates

1. Project Proposal Submission 📋: **11th April**
2. Discussion with Instructor: **w/c 14th April**
3. Project Submission 📚: **4th May**
4. Project Presentation 📢 : **9th May**

   ---

## Exploring The Repository

There are 5 folders:
1. Raw_Data: This contains the initial stock screening raw data file used for the initial feature analysis
2. Financial_Feature_Analysis
3. Cleaned_Data
4. Macroeconomics_Analysis
5. ML_Predictive_Modelling

### 1. Raw_Data ###
This contains 2 files:
- Stock_Screening V2: This is the initial dataset that was used for ALL feature analysis.
- Stock_Screening Live: This is used later in the project during the machine learning piece. It is used in the Stock_Screening_Project file.

### 2. Financial_Feature_Analysis ###
This folder contains 8 different files where all the data cleaning and analysis was completed.

### 3. Cleaned_Data ###
This folder contains all of the cleaned data sets that were exported for the machine learning aspect of this project.

### 4. Macroeconomics_Analysis ###
This folder contains all of the cleaned data sets that were exported for the machine learning aspect of this project.

### 5. ML_Predictive_Modelling ###
This folder contains the Stock_Screening_Project ML & Predictive modelling file along with an exported csv file which occurs during the execution of the Stock_Screening_Project code. The file contains "The Top 10 stocks which are likely to outperform the market".


## Getting Started

All of our coding was done in **Jupyter Notebooks** or **VS Code**.

### 1. Install required Python modules  
Make sure you have Python 3.7+ installed, then in your terminal run:  
```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn

```

### 2. Data source

We used the Excel file **CFG_Stock_Screening_V2.xlsx** as our raw data (found in the "Raw_Data" folder.

1. Pull down the file from the online repository or download the file directly from the repository.
2. Open up each analysis file using VS Code or Jupyter Notebook (Excluding the "Stocks_Screening_Project" file, this is used later in the project).
3. Update the file path at the top of the code to point to your local copy of the raw data source, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. Execute all cells to load the raw Excel data and drop any columns or dates with zeros, NaNs and extreme outliers.
5. Export the cleaned tables as CSV files (e.g. cleaned_roe.csv, cleaned_CFO.csv).

### 3. Data Analysis

Continue to run the code to view the analysis of the individual features including analysing:
- Means & Medians
- Correlations
- Distributions
- Significance
- Conclusions

### 4. Macroeconomics Analysis

This section utilises online data sources which we're able to obtain using APIs.

1. Pull down the file from the online repository or download the file directly from the repository (Found in the folder "Macroeconomic_Analysis").
2. Open up each analysis file using VS Code or Jupyter Notebook.
3. Update the file path at the top of the code to point to your local copy of the raw data source, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. Execute all cells to pull the data via the API and have the code run through the analysis.

### 5. Machine Learning (ML)

The cleaned data csv exports were used for the machine learning aspect of this project.

1. All cleaned data sets are available in the "Cleaned_Data" folder - Download to your local repository.
2. Download the file to run for this aspect of the project: "Stock_Screening_Project" (Found in the "Financial_Feature_Analysis" folder).
3. Update the file path at the top of the code to point to your local copy of the cleaned data sources along with the original stocks_screening_v2.xlsx file, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. At the section "For Live Monthly Workflow", you will need to update the file path for the "Stock_Screening_Live.xlsx" file.
5. Execute all cells to load the data and run the code.
6. The Top 10 stocks which are likely to outperform the market are then saved to a csv file (Example file found in the "Results" folder).
