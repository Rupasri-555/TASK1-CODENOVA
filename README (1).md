# Bank Marketing Campaign Analysis Using EDA

## 1. Project Overview
This project uses Exploratory Data Analysis (EDA) to analyze customer information and bank marketing campaign outcomes.

## 2. Dataset
- Dataset: UCI Bank Marketing Dataset
- File: `bank-full.csv`
- Rows: 45,211
- Columns: 17

## 3. Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 4. Analysis Performed
- Dataset overview and statistical summary
- Missing-value and duplicate checks
- Identification of unknown categorical values
- Outlier detection using the IQR method
- Feature distribution histograms
- Numerical feature boxplots
- Correlation heatmap
- Pairwise scatter plots
- Subscription analysis by job, contact method, month, and marital status

## 5. Data Quality
Initial checks found no missing values or duplicate rows. Unknown categorical values were retained, and potential outliers were investigated rather than automatically removed.

## 6. Analytical Insights
The notebook visualizes customer characteristics and compares subscription rates across customer groups and campaign months. The exact percentages and patterns can be found in the notebook outputs.

## 7. Deliverables
- `Bank_Marketing_EDA.ipynb`
- `README.md`
- `cleaned_bank_marketing.csv`
- `visualizations/` folder containing exported charts

## 8. Conclusion
EDA helps identify patterns in customer data and marketing outcomes. These findings are descriptive and do not establish causal relationships.