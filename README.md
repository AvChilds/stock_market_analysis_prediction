![alt text](https://codefirstgirls.com/wp-content/uploads/2022/04/CFGDegree-Logo-2.png "CFG Logo")


# CFG Group 5 Project
## Stock Prediction Algorithm

## Group Members 🌟 

1. Laura Davies (GitHub Coordordinator)
2. Avril Childs (Organisational Lead)
3. Wei Shi (Technical Lead)
4. Bushra Abodher (Task Coordinator)
5. Laura Lloyd (Submission Lead)
6. Esther Nunsubuga (Presentation Lead)

## Project Question

> Can we develop a Machine Learning model that reliably predicts the 
> likelihood of a selection of stocks in the next year that can outperform 
> the market/generate capital gains based on historical financial and 
> pricing data?

## Project Objective

> The objective of this project is to develop a Machine Learning (ML) 
> model to assist investment professionals in selecting stocks from the S&P
> 500 index that have the potential to generate capital gains over the next 
> year.

## Key Dates

1. Project Proposal Submission 📋: **11th April**
2. Discussion with Instructor: **w/c 14th April**
3. Project Submission 📚: **4th May**
4. Project Presentation 📢 : **9th May**

   ---

## Exploring The Repository

There are 4 folders:
1. Raw_Data: This contains the initial stock screening raw data file used for the initial feature analysis
3. CFG_Data_Analysis_Files
4. Cleaned_Data
5. Results

### Raw_Data ###
This contains 2 files:
- Stock_Screening V2: This is the initial dataset that was used for ALL feature analysis.
- Stock_Screening Live: This is used later in the project during the machine learning piece. It is used in the Stock_Screening_Project file.

### CFG_Data_Analysis_Files ###
This folder contains 9 different files where all the data cleaning and analysis was completed.

### Cleaned_Data ###
This folder contains all of the cleaned data sets that were exported for the machine learning aspect of this project.

### Results ###
This folder contains an exported csv file which occurs during the execution of the Stock_Screening_Project code. The file contains "The Top 10 stocks which are likely to outperform the market".


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

### 4. Machine Learning (ML)

The cleaned data csv exports were used for the machine learning aspect of this project.

1. All cleaned data sets are available in the "Cleaned_Data" folder - Download to your local repository.
2. Download the file to run for this aspect of the project: "Stock_Screening_Project" (Found in the "CFG_Data_Analysis_Files" folder).
3. Update the file path at the top of the code to point to your local copy of the cleaned data sources, for example:
```
 pd.read_excel('C:/Users/Desktop/Data/....')
```
Please note: You will still need to utilise the initial "Stock_Screening_V2.xlsx" file at this point too.
4. At code line [ ], you will need to update the file path for the "Stock_Screening_Live.xlsx" file.
5. Execute all cells to load the cleaned data and run the code.
6. The Top 10 stocks which are likely to outperform the market are then saved to a csv file (Example file found in the "Results" folder).
