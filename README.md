# 📊 Strategic Pricing & Sales Performance Analysis

This project presents a comprehensive analysis of pricing, revenue, discounts, and sales performance across four major regions and five product categories: **Clothing, Electronics, Furniture, Groceries, and Toys**.

## 🧠 Project Goal

Evaluate pricing strategies, benchmark against competitors, identify revenue opportunities, and optimize sales through dynamic pricing models.

---

## 📍 Key Findings

### ✅ Sales vs. Orders (Regional Performance)
![Units Sold vs Orders by Region](images/units_vs_orders.png)
> All regions sold more units than ordered – suggesting strong demand, backorders, or real-time sales fulfillment.

- **South**: Highest surplus – indicates high demand or aggressive strategy
- **West**: Smallest surplus – may reflect tight inventory or low demand

---

## 💡 Dashboard Insights

### 🔍 Price Difference Panel
![Price Comparison Chart](images/price_difference.png)

- **Normal Price**: ₹4,030,376.41  
- **Competitor Price**: ₹4,031,178.26  
- Both prices are decreasing – suggesting a market-wide trend or competitive pricing.

---

### 💰 Revenue Performance Panel
![Revenue Performance Gauge](images/revenue_performance.png)

- **Actual**: ₹494.97M  
- **Target**: ₹500M  
- Shortfall of ₹5M due to price cuts, demand softness, or promotional gaps

---

## 📈 Regional & Category Insights

![Revenue by Region and Category](images/revenue_region_category.png)

- **Clothing**: Dominates in South & East
- **North**: Underperforms – requires strategy reevaluation
- **West**: Balanced performance

---

## 📊 Trend Analysis

### 🔄 Price and Price Difference Over Time
![Price Trends](images/price_trend.png)

- Notable **dip in Jan 2024**
- Dynamic changes suggest active pricing strategies
- Close tracking between actual and competitor prices

---

## 📌 Correlation Matrix
![Correlation Heatmap](images/correlation_matrix.png)

- **Units Sold ↔ Forecast Demand**: 0.997  
- **Price ↔ Competitor Pricing**: 0.994  
- **Revenue ↔ Units Sold**: 0.794

> Strong relationships confirm the value of forecasting and competitor benchmarking.

---

## 📉 Linear Regression: Price vs. Units Sold

![Linear Regression Plot](images/linear_regression.png)

- Positive slope implies **pricing power** in some categories
- Moderate variability due to external factors

---

## 🤖 Multiple Regression Output

![Regression Model Summary](images/multiple_regression.png)

- Predicts price using:
  - Units Sold
  - Forecast Demand
  - Competitor Pricing
- **R² ≈ 0.99** – Excellent model fit
- **Competitor Price** = Most influential factor

---

## 💸 Discounts vs. Sales Volume

![Discount vs Sales Scatterplot](images/discounts_vs_sales.png)

- Discounts are not always linked to higher sales
- **Clothing & Furniture** show strong performance without deep discounts
- Suggests value and brand strength

---

## 🧭 Strategic Recommendations

- 🧩 Use **dynamic pricing** based on region and season
- 📈 Raise prices in inelastic categories like **Furniture and Clothing**
- 🎯 Reduce discounts when unnecessary
- 📊 Focus marketing in **North**, expand in **South & East**
- 🔍 Regularly benchmark against competitors using regression-based pricing models

---

## 📂 Dataset

- 73,000+ records across:
  - Prices
  - Units Sold
  - Discounts
  - Forecast Demand
  - Competitor Prices
  - Revenue

---

## 🛠 Tools Used

- **Excel** – Forecast Sheet, Pivot Charts, Slicers  
- **Power BI** – Dashboards, Drilldowns  
- **Python** – Regression, Correlation (statsmodels, seaborn, pandas)

---

## 🚀 Impact

This project helps retailers and analysts:
- Identify **underpriced** and **overpriced** products
- Use data science to guide **revenue-maximizing pricing**
- Align strategies across regions with evidence-based models

---

## 📬 Contact

**Analyst:** [Your Name]  
**Email:** [your.email@example.com]  
**LinkedIn:** [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

