# customer_behavior_analysis

This data analytics project analyzes customer shopping behavior using 3,900 transaction records to uncover insights that support data-driven business decisions. The project covers the complete analytics lifecycle — from data loading and exploratory analysis in Python to SQL-based querying, interactive Power BI dashboard creation, and business reporting through presentations.

---

## 📊 Dataset
- **Total Transactions:** 3,900  
- **Total Columns:** 18  
- **Key Attributes:**  
  - Customer demographics (age, gender)  
  - Product categories and items  
  - Purchase amount and ratings  
  - Subscription status  
  - Discounts and shipping type  
- **Missing Values:**  
  - 37 missing values in the *Review Rating* column, handled during preprocessing  

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib  
- **Databases:** PostgreSQL / MySQL / SQL Server  
- **Visualization:** Power BI  
- **Reporting:** Gamma (PPT creation)  
- **Environment:** Jupyter Notebook  

---

## 🔍 Project Steps
1. **Data Loading**
   - Loaded the dataset using Pandas in Python
   - Performed initial inspection using `df.info()` and summary statistics  

2. **Exploratory Data Analysis (EDA)**
   - Analyzed purchase trends, ratings, demographics, and revenue distribution
   - Identified customer behavior patterns and outliers  

3. **Data Cleaning & Feature Engineering**
   - Handled missing review ratings using median imputation
   - Created new features such as age groups and purchase frequency  

4. **SQL Analysis**
   - Imported cleaned data into PostgreSQL / MySQL / SQL Server
   - Executed SQL queries for aggregation, filtering, and segmentation  

5. **Dashboard Development**
   - Built an interactive Power BI dashboard
   - Added filters for gender, subscription status, product category, and shipping type  

6. **Reporting & Presentation**
   - Created a detailed analysis report
   - Designed a professional presentation using Gamma  

---

## 📈 Dashboard
The Power BI dashboard enables interactive analysis with:
- Revenue by gender and age group
- Customer segmentation (New, Returning, Loyal)
- Subscription vs non-subscription insights
- Product and category performance
- Shipping type impact on purchase value  

---

## 📌 Key Results & Insights
- Loyal customers form the largest customer segment
- Young adults generate the highest overall revenue
- Subscribers spend more per transaction than non-subscribers
- Express shipping users show higher average purchase value
- Certain products show strong dependency on discounts

---

