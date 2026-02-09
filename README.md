# Customer-Segmentation-and-churn-analysis
## 1. Problem Statement
Businesses often struggle to identify high-value customers and detect churn early. This project segments customers based on purchasing behavior and analyzes churn trends to support retention strategies.
## 2. Tech Stack
Python | Pandas | Scikit-learn | Power BI | SQL
## 3. Methodology
* Data cleaning and preprocessing of retail transaction data
* RFM feature engineering (Recency, Frequency, Monetary)
* K-Means clustering for customer segmentation
* Churn definition based on customer inactivity (>90 days of inactivity)
* Interactive Power BI dashboards for business insights
## 4. Dashboard Preview
![Overview](Executive_Overview.png)
![Customer Segments](Customer_Segments.png)
![Churn Analysis](Churned.png)
![Revenue vs Churn](Revenue_vs_churn.png)
![Outliers](Outliers.png)
## 5. Key Insights
* An inverse relationship is observed between churn rate and revenue—periods of lower churn consistently align with higher revenue, highlighting the significant financial impact of customer attrition.
* Inactive and low-frequency customer segments exhibit significantly higher churn rates compared to regular customers, indicating clear targets for retention efforts.
* A small number of exceptional customers contribute disproportionately to total revenue, necessitating separate analysis to prevent distortion of overall performance metrics.
* Churn rates vary significantly across countries, suggesting that region-specific factors influence customer retention and should be addressed with localized strategies.
* Customers with higher purchase frequency demonstrate lower churn likelihood than those with similar recency but fewer transactions, emphasizing the importance of engagement over one-time purchases.
* Rising churn percentages often precede revenue slowdowns, indicating that churn can serve as an early warning indicator for future revenue performance.
## 6. How to Run
* Open notebook
* Open PBIX locally

