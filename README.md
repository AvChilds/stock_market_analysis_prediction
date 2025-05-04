![alt text](https://codefirstgirls.com/wp-content/uploads/2022/04/CFGDegree-Logo-2.png "CFG Logo")


# CFG Group 5 Project
## Stock Performance Prediction Algorithm

## Group Members 🌟 

1. Laura Davies (GitHub Coordordinator)
2. Avril Childs (Project Lead)
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

There are 2 additional pdf documents:
6. Project Documentation -  cfgDSGroup5_Project_Documentation-Stock_Analysis_Prediction.pdf
7. Key Financial Terms.pdf

 
### 1. Raw_Data ###
This contains 2 files:
- Stock_Screening V2: This is the initial dataset that was used for ALL feature analysis.
- Stock_Screening Live: This is used later in the project during the machine learning piece. It is used in the Stock_Screening_Project file.

### 2. Financial_Feature_Analysis ###
This folder contains 8 different .ipynb (Jupyter Notebook) files where all the data cleaning and analysis was completed for 8 different financial features.

### 3. Cleaned_Data ###
This folder contains all of the cleaned data (in .csv format) sets that were exported for the machine learning aspect of this project.

### 4. Macroeconomics_Factor Analysis ###
This folder contains 2 .ipynb files where data sourcing, cleaning and analysis of 2 macroeconomic factors - Consumer Price Index and Federal Reserve Interest Rate

### 5. ML_Predictive_Modelling ###
This folder contains the Stock_Screening_Project ML & Predictive modelling file along with an exported .csv  results file which occurs during the execution of the Stock_Screening_Project code. The file contains "The Top 10 stocks which are likely to outperform the market".

### 6. cfgDSGroup5_Project_Documentation-Stock_Analysis_Prediction ###
This .pdf project specification document details:
 - The objectives and background of the project
 - Roadmap and methology
 - Project requirements 
 - Results and Recommendation

### 7. Key Financial Terms
This .pdf document provides further detail and explanations on key finicial terminology used within the project. 


## Getting Started 

All of our coding was done in **Jupyter Notebooks**. You may wish to read the project documentation "cfgDSGroup5_Project_Documentation-Stock_Analysis_Prediction.pdf" to gain an overview of the project prior exploring and running the source code. 

### 1. Install and required Python modules  
* Make sure you have Python 3.7+ installed, then in your terminal run, install the require python modules and libraries by using the following sample code:  
```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn 

```
*Ensure that you import the relevant libraries that are required. The libraries are stated at the start of each .ipynb file and should be run each time. The libraries used the project are 
- Statistical Libraries (Python):  numpy, pandas, scipy, Sci-kit Learn, Joblib.
- Data visualisation libraries (Python): Matplotlib, Seaborn, Plotly.


### 2. Financial Feature Analysis

We used the Excel file **Stock_Screening_CFG v2.xlsx** as our raw data (found in the "Raw_Data" folder).

1. Pull down this file from the online repository or download the file directly from the repository, taking note of the file path.
2. Open up each feature analysis file from the folder "Financial_Feature_Analysis" using Jupyter Notebooks (Excluding the "Stocks_Screening_Project" file, this is used later in the project).
3. Update the file path at the top of the code, within the pd.read_excel(), with the file path of your local copy of **Stock_Screening_CFG v2.xlsx**, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. Execute all cells to load the raw Excel data and perform data cleaning and analysis
5. 6. The cleaned data will be saved in your local folder as CSV files (e.g. cleaned_roe.csv, cleaned_CFO.csv).
6. Continue to run the code to view the analysis of the individual features including analysing:
- Means & Medians
- Correlations
- Distributions
- Significance
- Results/Conclusions


### 3. Macroeconomics Factor Analysis

This section utilises online data sources which we're able to obtain using APIs.

1. Pull down the files from the online repository or download the file directly from the repository (Found in the folder "Macroeconomic_Analysis").
2. Open up each analysis file using Jupyter Notebooks.
3. Update the file path at the top of the code to point to your local copy of the raw data source, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
4. Execute all cells to pull the data via the API and have the code run through the analysis.

### 5. Machine Learning (ML)

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
