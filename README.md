# E-Commerce Sales Analysis & Insights

## 📊 Project Overview
This project analyzes an **E-Commerce Sales Dataset** to uncover revenue trends, customer behavior, and the impact of **discounts, payment methods, and regional differences** on sales. Using **Python for data exploration, visualization, and predictive modeling**, the analysis provides key insights and business recommendations.

## 🔍 Key Objectives
- Clean and preprocess sales data
- Identify top-selling products and revenue trends
- Analyze how discounts and payment methods impact sales
- Use **Linear Regression** to predict sales trends
- Provide actionable recommendations for business improvement

## 📂 Dataset Overview
- **Total Records:** [Number of rows]
- **Columns Included:**
  - `Customer_ID` - Unique customer identifier
  - `Order_ID` - Order transaction ID
  - `Product` - Product name
  - `Sales_Amount` - Total sales in USD
  - `Order_Date` - Date of purchase
  - `Region` - Customer region
  - `Payment_Method` - Payment type (Credit Card, PayPal, etc.)
  - `Discount` - Applied discount percentage
  - `Customer_Segment` - B2B or B2C segmentation

## 🛠 Tools & Libraries Used
- **Pandas & NumPy** for data cleaning and transformation
- **Matplotlib & Seaborn** for data visualization
- **Scipy.stats** for correlation analysis
- **Scikit-learn (Linear Regression)** for predictive modeling

## 🚀 Steps Taken
### 1️⃣ Data Cleaning & Formatting
✔ Converted `Order_Date` to datetime format  
✔ Handled missing values (filled with 0 or median values)  
✔ Removed duplicates  
✔ Applied **One-Hot Encoding** for categorical variables (Region, Payment Method)

### 2️⃣ Exploratory Data Analysis (EDA)
✔ **Total Revenue by Region** (Pie chart visualization)  
✔ **Top 10 Best-Selling Products** (Bar chart visualization)  
✔ **Discount vs. Sales Analysis** (Correlation & Regression)

### 3️⃣ Advanced Insights & Predictive Modeling
✔ **Correlation Analysis:**
   - Found a **slight negative correlation (-0.0559)** between discounts and sales
✔ **Linear Regression Model:**
   - Sales Prediction Equation: `Sales_Amount = 816.00 - 270.60 * Discount`
   - **Model Performance:**
     - **R² Score:** 0.0031
     - **RMSE:** 418.36
✔ **Impact of Payment Method & Region:**
   - Credit Card users spend **$11.09 less**, while PayPal users spend **$0.92 less** than the baseline category
   - **North Region customers spend $48.75 less**, while West Region spends **$19.99 more** than South Region

## 📈 Key Findings & Recommendations
✔ **Discounting strategies should be optimized** since excessive discounts slightly reduce revenue.  
✔ **High-performing products should be prioritized** for inventory & marketing focus.  
✔ **Regional spending habits should be considered** for targeted marketing.  
✔ **More advanced ML models (e.g., XGBoost) can improve sales predictions.**

## 📌 Next Steps
- Introduce **time-series forecasting** to identify seasonal sales trends.
- Apply **customer segmentation analysis** to refine marketing strategies.
- Use **advanced machine learning models** for better prediction accuracy.

## 🔗 Project Files
📂 **E-Commerce Analysis Code** - `ecommerce_analysis.py` or `.ipynb`
📂 **PowerPoint Presentation** - `E-commerce_kp.pdf`
📂 **Dataset** - `ecommerce_data.csv`

---

**📢 Connect with Me:** [[https://n9.cl/n6a8r]]

🚀 Hope you enjoy this project! Feel free to explore, comment, and share insights. Happy coding! 😊

