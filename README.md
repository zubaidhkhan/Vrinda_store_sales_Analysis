# 🛍️ Vrinda Store Data Analysis

Excel-based sales analytics project on 31,047 order records from Vrinda Store, an Indian apparel retailer selling through Amazon, Myntra, Flipkart and other marketplaces. The data is turned into an interactive dashboard that shows who buys, what sells, where, and through which channel.

## 📌 Objectives
- Understand customer demographics (gender and age group)
- Identify top channels, categories and states by revenue
- Track monthly sales performance
- Measure losses from returns, cancellations and refunds

## 📂 Dataset
| Detail | Value |
|---|---|
| Records | 31,047 order lines |
| Columns | 21 |
| Unique orders | 28,471 |
| Currency | INR |
| Key fields | Order ID, Gender, Age Group, Month, Status, Channel, Category, Size, Qty, Amount, Ship State, B2B |

## 🛠️ Tools & Techniques
- Microsoft Excel
- Data cleaning and validation
- Pivot Tables and Pivot Charts
- Slicers and dashboard design

## 📊 Key Insights
- **Total revenue:** about ₹2.12 crore
- **Customers:** women generate about 64% of revenue, and adults about 50%
- **Channels:** Amazon, Myntra and Flipkart together account for about 80% of sales
- **Products:** Sets lead at about 50% of revenue, followed by Kurtas and Western Dresses
- **Geography:** Maharashtra, Karnataka and Uttar Pradesh are the top states
- **Fulfilment:** about 8% of order lines end in return, cancellation or refund

## 💡 Recommendations
1. Focus inventory and promotions on Amazon, Myntra and Flipkart
2. Expand the Set and Kurta ranges
3. Run targeted campaigns for men and senior customers
4. Reduce returns and cancellations by studying their causes by category and size
5. Stock deeper in sizes M, L and XL

## 🔍 Data Quality Notes
- The `Date` column contains invalid years (1969–2068), so the `Month` column was used for trend analysis
- Category names were standardised (for example `kurta` and `Kurta`)
- Distinct Order IDs were used to count orders, since multi-item orders repeat IDs



## 🚀 How to Use
1. Open the Excel workbook and go to the **Dashboard** sheet
2. Use the slicers to filter by month, channel, category or gender
3. Go to Data → Refresh All if the source data changes


