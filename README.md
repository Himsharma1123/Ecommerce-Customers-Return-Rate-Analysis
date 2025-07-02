# E-Commerce Return Rate Reduction Analysis

## Objective
The aim of this project is to identify key factors contributing to product returns in an e-commerce setting and reduce return rates by understanding trends across product categories, user demographics, and payment behavior. This analysis also predicts return probability using logistic regression.

## Dataset
- **Source**: Synthetic e-commerce dataset (10,000 orders)
- **Features include**: 
  - Order_ID, Order_Date, Product_Category, User_Location, User_Age, Gender
  - Payment_Method, Discount_Applied, Days_to_Return, Return_Status, Return_Reason

## Tools & Technologies Used
- **Python (Pandas, Scikit-learn, Matplotlib, Seaborn)** – Data processing & modeling  
- **Power BI** – Dashboard creation and data storytelling  
- **SQL** – Exploratory data analysis and high-risk product extraction
- **Excel** - For Data Cleaning

## Steps Performed

### 1. Data Cleaning
- Removed null and duplicate values
- Converted return date to datetime format
- Created binary label `Return_Binary` for modeling

### 2. Exploratory Data Analysis (EDA)
- Identified top-returned product categories
- Analyzed return trends across cities, gender, payment methods, and reasons
- Visualized monthly return trends and return rates

### 3. Modeling (Logistic Regression)
- Trained model on 80% of data
- Predicted return status for all orders (100%)
- Achieved **97% accuracy**  
- Evaluated with confusion matrix, precision, recall, and f1-score

## 4. High-Risk Product Identification
- Used SQL and Python to extract top 10 product categories with high predicted returns

## Power BI Dashboard
**Visuals Included:**
- KPI Cards: Total Orders, Actual Returned Orders, Predicted Returns, Return Rate, Model Accuracy
- Bar chart: Returns by Product Category
- Donut chart: Return Reasons distribution
- Pie chart: Return Rate by Payment Method
- Line chart: Monthly Return Trend
- Table: Top 5 Cities with Most Returns
- Filters: Payment Method, Gender, Product Category, Order Date Range

## Deliverables
- Interactive Power BI dashboard with drill-through filters  
 - Python codebase for return prediction (`.ipynb`)  
- predicted_returns_full.csv` with all predicted return results  
- high_risk_products.csv` containing top 10 risk-prone product categories  
- Final project report (PDF)  

## Author  
Himanshi Sharma  
B.Tech CSE | Rajasthan Technical University  
Internship by Elevate Labs
