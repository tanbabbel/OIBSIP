# OIBSIP


Task submissions for the Oasis Infobyte Internship Program (OIBSIP).

## Tasks

| # | Task | Folder |
|---|------|--------|
| 1 | Exploratory Data Analysis on Retail Sales Data | [Task 1 Retail_sales_dataset] |

## Task 1: Retail Sales EDA

- Tech stack: Python, pandas, matplotlib, seaborn, scipy, Jupyter Notebook
- Dataset:[Retail Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset), 1,000 transactions from 2023
- Key findings:
  - Items priced at 300 or 500 are about 40% of transactions but about 88% of revenue.
  - Average ticket rises from about 177 for one item to about 707 for four items.
  - Revenue is split almost equally across Electronics, Clothing and Beauty.
  - Gender, age group and monthly differences are not statistically significant.
- Note: the dataset has no product names, so a "product proxy" (category + unit price) is used for the top 10 products analysis.
