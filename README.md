# Mobile-Sales-Power-BI-Dashboard
Interactive Power BI dashboard analyzing mobile sales, quantity, transactions, brands, payment methods, customer ratings, and monthly sales trends.
# 📱 Mobile Sales Dashboard – Power BI

## 📌 Project Overview

This Power BI project provides an interactive analysis of mobile phone sales across different **brands, mobile models, months, payment methods, customer ratings, and days of the week**.

The main objective of the dashboard is to turn transaction-level sales data into a simple business view that can answer questions such as:

- How much revenue was generated?
- How many units were sold?
- Which brands and mobile models generated the most sales?
- How does sales activity change throughout the year?
- Which payment methods are most commonly used?
- Which days generate stronger sales?
- How are customer ratings distributed?
- Which brands contribute the most to overall sales and quantity?

The dashboard also includes interactive filters for **Month, Mobile Model, Payment Method, Brand, and Day Name**, allowing users to explore specific parts of the data.

---

## 📊 KPI Summary

The dashboard highlights four main KPIs:

- **Total Sales:** approximately **79.67M**
- **Total Quantity Sold:** **1,959 units**
- **Transactions:** **386**
- **Average:** approximately **41K**

The Total Sales card is displayed as approximately **80M** because the dashboard uses abbreviated display units.

These KPIs provide a quick overview of overall sales activity before moving into more detailed analysis.

---

# 🔍 Dashboard Analysis

## 1. 📱 Sales by Mobile Model and Customer Rating

The stacked column chart analyzes **Total Sales by Mobile Model**, while customer ratings are used to break down the sales contribution within each model.

This visual helps identify:

- Which mobile models generate the most revenue
- How customer ratings are distributed across different models
- Whether high-selling products also receive stronger customer ratings

The chart shows that sales are distributed across several models rather than being completely dependent on one product.

This is useful for product managers because a company should not only identify its highest-selling model, but also understand whether customers are satisfied with those products.

---

## 2. 📅 Total Quantity Sold by Month

The monthly line chart shows how the number of units sold changes throughout the year.

The overall pattern is not completely stable.

Sales quantity increases strongly around **July and August**, declines afterward, falls significantly around **October**, and then increases sharply again in **November**.

November appears to be one of the strongest months for unit sales, while October and December are among the weaker periods shown on the chart.

### Business interpretation

This type of pattern can help a business investigate possible:

- Seasonal demand
- Promotional periods
- Festival or holiday effects
- Product launches
- Discounts
- Inventory availability

A business could use this information to prepare additional inventory before historically strong months.

---

## 3. 💳 Transactions by Payment Method

The payment-method analysis shows a relatively balanced customer preference.

The dashboard displays approximately:

| Payment Method | Records | Share |
|---|---:|---:|
| Credit Card | 398 | 26.29% |
| UPI | 386 | 25.50% |
| Debit Card | 367 | 24.24% |
| Cash | 363 | 23.98% |

No single payment method dominates the dataset.

Credit Card has the highest share, but the difference between all four methods is relatively small.

### Business interpretation

Customers appear comfortable using both digital and traditional payment methods.

This suggests that the business should continue supporting multiple payment options rather than focusing on only one payment channel.

Maintaining payment flexibility can help reduce friction during the purchasing process.

---

## 4. 🏷️ Brand Performance

The brand-level table provides a direct comparison of revenue, quantity sold, and transactions.

| Brand | Total Sales | Quantity | Transactions |
|---|---:|---:|---:|
| Apple | 15,173,371 | 372 | 70 |
| OnePlus | 15,805,080 | 386 | 79 |
| Samsung | 14,423,514 | 332 | 73 |
| Vivo | 17,517,726 | 430 | 83 |
| Xiaomi | 16,753,926 | 439 | 81 |
| **Total** | **79,673,617** | **1,959** | **386** |

### Key observations

**Vivo generated the highest sales revenue**, with approximately **17.52M**.

**Xiaomi sold the highest number of units**, with **439 units**, slightly higher than Vivo's 430 units.

Vivo also recorded the highest number of transactions among the brands shown.

Samsung generated the lowest total revenue and quantity among these five brands.

### Business interpretation

The results show an important difference between **sales revenue and sales volume**.

Xiaomi leads in quantity sold, while Vivo leads in revenue.

This may indicate differences in:

- Average selling price
- Product mix
- Customer purchasing behavior
- Premium vs lower-priced models

Management should therefore evaluate both **revenue and units sold** rather than using only one metric to judge brand performance.

---

## 5. ⭐ Customer Rating Analysis

The customer-rating visual compares sales activity across ratings from **1 to 5**.

Higher ratings appear to represent a stronger portion of the visual, with Rating 5 showing the largest level.

The dashboard can therefore be used to investigate whether products with stronger customer satisfaction also contribute more strongly to sales.

### Business interpretation

Customer ratings are useful beyond simply measuring satisfaction.

They can help management identify:

- Products with strong customer acceptance
- Products that generate sales despite weaker ratings
- Models that may need quality improvements
- Opportunities for customer-feedback analysis

A useful future extension would be to compare:

**Average Rating vs Total Sales by Mobile Model**

to investigate whether higher customer satisfaction is associated with stronger sales.

---

## 6. 🏆 Top Mobile Models by Sales

The bar chart identifies the highest-revenue mobile models.

The leading models shown are:

1. **iPhone SE** – approximately **24.63M**
2. **Galaxy S21** – approximately **23.81M**
3. **OnePlus Nord** – approximately **22.73M**

These three products are major contributors to overall revenue.

### Business interpretation

High-performing models deserve special attention in:

- Inventory planning
- Promotions
- Product availability
- Advertising campaigns
- Supplier planning

However, management should also check profitability before deciding which products deserve additional investment. High revenue does not automatically mean high profit.

---

## 7. 📦 Total Quantity by Brand

The treemap provides a visual comparison of unit sales across brands.

Xiaomi and Vivo appear to be among the strongest brands by quantity, which is consistent with the detailed brand table.

The treemap is useful because it allows users to quickly understand each brand's relative contribution to total units sold.

### Business interpretation

Brands with high unit volume may require:

- Larger inventory allocation
- Better supplier coordination
- Faster stock replenishment
- Stronger after-sales support

---

## 8. 📆 Total Sales by Day of Week

The day-level sales analysis shows that sales performance differs across the week.

**Friday appears to generate the highest sales**, followed closely by Wednesday and Sunday.

Monday appears to generate the lowest sales among the days shown.

### Business interpretation

This information can help management decide when to:

- Run promotions
- Increase digital advertising
- Schedule sales campaigns
- Prepare additional staff
- Manage inventory availability

For example, marketing activity could be increased before historically strong days such as Friday.

At the same time, management could investigate why Monday performs more weakly and test targeted promotions.

---

# 💡 Key Findings

The dashboard highlights several important business patterns:

### 1. Vivo leads revenue

Vivo generated approximately **17.52M**, making it the highest-revenue brand in the current dataset.

### 2. Xiaomi leads unit sales

Xiaomi sold **439 units**, the highest quantity among the five brands.

This demonstrates that the brand generating the highest revenue is not necessarily the brand selling the largest quantity.

### 3. Sales demand changes by month

July, August, and November show relatively strong unit-sales activity, while October is noticeably weaker.

This suggests possible seasonality in mobile-phone demand.

### 4. Payment preferences are highly balanced

Credit Card, UPI, Debit Card, and Cash each represent approximately one-quarter of the payment activity.

There is no extreme dependence on one payment method.

### 5. A small group of models generates significant revenue

iPhone SE, Galaxy S21, and OnePlus Nord are among the strongest models by total sales.

### 6. Sales performance changes by day

Friday is the strongest sales day in the dashboard, while Monday shows considerably lower revenue.

---

# 🎯 Business Recommendations

Based on the dashboard analysis, several actions could be considered.

### Inventory Planning

Increase inventory preparation before months with historically stronger demand, particularly around the periods showing higher unit sales.

### Product Strategy

Give additional attention to strong-performing models such as **iPhone SE, Galaxy S21, and OnePlus Nord**, while continuing to monitor customer ratings and profitability.

### Brand Strategy

Vivo and Xiaomi should receive particular attention because Vivo leads revenue while Xiaomi leads quantity.

Understanding why these brands perform differently could help improve pricing and product-mix decisions.

### Payment Experience

Continue providing multiple payment methods because customer usage is evenly distributed across Credit Card, UPI, Debit Card, and Cash.

### Weekly Marketing Strategy

Consider concentrating promotional campaigns around stronger sales periods such as Friday, while testing targeted promotions on weaker days such as Monday.

### Customer Satisfaction

Compare customer ratings with sales and product models to identify whether high-selling products also provide strong customer experiences.

---

# 🎛️ Interactive Filters

The dashboard includes filters for:

- **Month**
- **Mobile Model**
- **Payment Method**
- **Brand**
- **Day Name**

These filters allow users to move from an overall business view to more focused questions.

For example:

> How much revenue did Vivo generate in July?

or:

> Which mobile models performed best when customers paid using UPI?

or:

> What were total sales on Fridays for Apple products?

This makes the dashboard useful not only for reporting but also for interactive business analysis.

---

# 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Transformation**
- **Data Visualization**
- **Interactive Slicers**
- **Business Analysis**

---

# 🎯 Project Objective

The purpose of this project was to practice the complete Power BI workflow:

**Raw Data → Data Cleaning → Data Transformation → DAX Measures → Visualization → Dashboard → Business Insights**

Through this project, I practiced how to turn transaction-level sales data into an interactive dashboard and how to move beyond simply creating charts by interpreting what those charts mean for a business.

---


**Power BI | DAX | Power Query | Data Analytics | Business Intelligence | Data Visualization**
