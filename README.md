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

## Getting Started

All of our coding was done in **Jupyter Notebooks** or **VS Code**.

### 1. Install required Python modules  
Make sure you have Python 3.7+ installed, then in your terminal run:  
```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn

```

### 2. Data source
We used the Excel file CFG_Stock_Screening_V2.xlsx as our raw data.

1. Pull down the file from the online repository or download the file directly from the repository..
2. Open up each analysis file using VS Code or Jupyter Notebook.
3. Update the file path at the top of the code to point to your local copy of the raw data source, for example: 'C:/Users/Desktop/Data"
4. Execute all cells to load the raw Excel data and drop any columns or dates with zeros, NaNs and extreme outliers.
5. Export the cleaned tables as CSV files (e.g. cleaned_roe.csv, cleaned_CFO.csv).

Once that’s done, you’ll have cleaned CSV files ready for the Machine Learning portion of the project.

### 3. Data Analysis
1. Continue to run the code to view the analysis of the individual features including analysing:
    - Means & Medians
    - Correlations
    - Distributions
    - Significance
    - Conclusions

### 4. Machine Learning
Once your data is cleaned and you’ve explored the key relationships, you’re ready to train and evaluate your ML model
