# Marketing Spend Effectiveness Analysis Using Statistical Technqiues

## Overview

This project analyzes marketing campaign performance using two key metrics:

- **Click-Through Rate (CTR)**
- **Cost Per Acquisition (CPA)**

By applying statistical techniques such as **log transformation**, **empirical rule**, **outlier detection using z-scores**, **confidence intervals**, and **hypothesis testing**, the project uncovers important patterns and validates assumptions that can aid marketing optimization.

---

## Objective

- Explore the distribution of CTR and CPA.
- Apply log transformation to reduce skewness.
- Identify outliers using z-score and the empirical rule.
- Estimate confidence intervals for the mean of CTR and CPA.
- Conduct hypothesis testing to validate assumptions.

---

## Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, numpy, scipy, seaborn, matplotlib  
- **Environment**: Jupyter Notebook / Google Colab

---

## 📂 Project Deliverables

- Jupyter notebook
- Scope of Work
- PACE strategy document
- Executive Summary
- Cleaned Datasets

## 📂 Data Source

You can download the cleaned dataset from [Google Drive](https://drive.google.com/drive/folders/1jZkYwku03x1G7ZJc_qyE4zvsLFKxpQEV?usp=drive_link)

## Running the Notebook

- This project was built using Jupyter Notebook and is compatible with Google Colab.

## To Run on Google Colab:
1. Open this notebook in Colab:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/shijin/MarketingSpendAnalysis-StatisticalTechniques/blob/main/MarketingPerformance_StatisticalAnalysis.ipynb)

2. Upload the dataset manually:  
   - Click the file icon (left sidebar in Colab)
   - Click **Upload**, then select `marketing_campaign.csv`  
   *(or run the cell `from google.colab import files` to upload interactively)*

3. Alternatively, replace the `read_csv()` line with a GitHub raw link:
```python
df = pd.read_csv('https://github.com/shijin/BlackFridaySalesDataAnalysis-Python_R/blob/main/marketing_campaign.csv')
```
## Author

* Shijin Ramesh | Data Analyst 

