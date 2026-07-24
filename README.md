# SUPERSTORE-ANALYSIS
## SALES PERFROMANCE
### Table of content
- Project Overview
- Data Source
- Tools
- Data Cleaning/ Preparation
- Exploratory Data Analysis 
- Data Analysis
- Results\findings
- Recommendations
- Limitation

### Project Overview
This data analysis project aims to provide the sales performance of a superstore company over the past years. By analyzing various aspect of the sales data, we seek to identify trends, make data driven recommendations and gain deeper understanding of the company performance

<img width="1266" height="678" alt="Screenshot 2026-07-13 101151" src="https://github.com/user-attachments/assets/1c9dca6e-ee35-43c4-8bb5-cec77366f9fb" />


### Data Source
Sales data is the primary dataset used for this analysis , containing detailed information about each sales made by the company

### Tools
- EXCEL
    - Data cleaning
- MySQL
    - Data Analysis 
- Power BI
    - Data Visualization
 
### Data Cleaning/ Preparation
In the initial data preparation phase we performed the following task:
 1.Data loading and inspection
 2.Handling missing and duplicate values
 3.Date cleaning and formatting

### Exploratory Data Analysis 
EDA involved exploring the sales data to get key questions, such as:
- What is the overall sales trend?
- Which is the overall profit ?
- What are the peak sales period?

### Data Analysis 
includes some interesting codes/ features worked with
```sql SELECT * FROM superstore WHERE sales > 2000```

### Results\findings
  The analysis results are summarized as follow:
1. The company sales have been steadily decreasing overtime over the past years , with noticeable peak during the holiday season.
2. Phones are the best performing item in the sub-category in terms of sales and revenue 
3. The West region happens to be the highest performing region in respect to sales.

### Recommendations
 Based on the analysis, we recommend the following:
- Invest in marketing and promotions during peaks sales season to maximize revenue.
- Focus on expanding and promoting products in sub-category,
- Customer segment with high lifetime values should be targeted for maximizing effort.

### Limitation
 I had to remove all zero values from sales and profit columns because they would have affected the accuracy of my conclusions from the analysis.


