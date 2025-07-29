# eda_online_retails_analytics_project
## Online Retail Analytics: EDA, Customer Segmentation & Sales Modeling
This project analyzes real-world transactional data from a UK-based online retail store. It includes exploratory data analysis, feature engineering, customer segmentation, and predictive modeling to derive business insights and support marketing strategies.
## Project Structure
 Online-Retail-Analysis/
├──  online_retails.ipynb         # Jupyter notebook with full analysis
├── data/
│   └── Online Retail.xlsx          # Raw dataset
##Key Objectives
•	• Perform exploratory data analysis (EDA) to uncover sales trends and customer behavior
•	• Identify top-performing countries and products
•	• Engineer features like InvoiceHour and MonthYear for time-based analysis
•	• Segment customers using RFM analysis (Recency, Frequency, Monetary)
•	• Build classification models to predict customer segments
##Dataset Overview
• Source: UCI Machine Learning Repository
• Size: 500,000+ records from a UK-based online retailer
• Features: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
## Key Insights
•	• Peak Sales Hours: Most purchases happen between 9 AM – 12 PM
•	• Top Countries: UK dominates transactions, followed by the Netherlands and Germany
•	• Product Trends: Certain gift items and holiday-themed products were consistently top-selling
•	• Customer Segments: RFM analysis helped group customers into four tiers for targeted marketing
•	• Modeling: Classification models achieved high accuracy in predicting customer loyalty segments
## Techniques Used
•	• Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
•	• Data cleaning & handling missing values
•	• Feature engineering (hour, day, country flags)
•	• RFM segmentation using quantiles
•	• Classification (Logistic Regression, Decision Tree, Random Forest)
## Deliverables
•	• 📓 Jupyter Notebook with step-by-step EDA and modeling
•	• 📌 PDF version of notebook (for non-technical reviewers)
•	• 📁 Clean, organized dataset and outputs
## How to Run
1. Clone this repository
2. Open `online_retails.ipynb` in Jupyter Notebook or VS Code
3. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn
4. Run all cells to reproduce the full analysis
## Future Work 
•	• Deploy a Streamlit app for interactive visualizations
•	• Add Power BI dashboard for business-facing report
•	• Automate reporting for monthly trends
##Author
Rakhi Chahar
Final Year Student | Data Analyst
##License
This project is for educational purposes only.
