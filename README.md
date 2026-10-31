# 🛒 Retail Store Analytics System Dashboard
An end-to-end interactive Excel Analytics Dashboard designed to analyze sales              performance, customer distribution, inventory pull, product profit margins, and            regional store performance for retail operations.
## 📌 Executive Summary Key Performance Indicators (KPIs)
- Total Revenue: ₹3,01,401[cite: 3]
- Total Quantity Sold: 1,691 units[cite: 3, 5, 6]
- Total Profit: ₹1,31,086[cite: 3]
- Average Profit Margin: 55.40%[cite: 3]
     
##  📊 Core Features & Analysis Breakdown
### 1. 📈 Sales & Monthly Revenue Analytics
- Track monthly trends comparing Sum of Revenue vs. Sum of Profit[cite: 4].
- Highlight peak revenue months (e.g., July generating ₹32,671 in revenue and ₹13,266        in profit)[cite: 4].
### 2. 🏪 Store & Regional Performance
 Evaluate overall sales and revenue distribution across multiple physical locations:
- Atlanta Downtown (Highest performer at ₹46,604 revenue)[cite: 1]
- LA Center (₹42,515 revenue)[cite: 1]
- NY Flagship (₹40,063 revenue)[cite: 1]
- Miami Beach (₹39,696 revenue)[cite: 1]
- Seattle Wharf (₹38,705 revenue)[cite: 1]
- Boston Common (₹27,552 revenue)[cite: 1]
- Interactive slicer support for East, North, South, and West regions[cite: 1].
# 3. 👥 Customer Segmentation Distribution
- Categorize customer purchasing volume across three core tiers[cite: 5]:
- Regular Customers: 843 units (50%)[cite: 3, 5]
- Value Customers: 496 units (29%)[cite: 3, 5]
- Premier Customers: 352 units (21%)[cite: 3, 5]
# 4. 📦 Inventory Pull Analytics
 Monitor quantity sold by product category to optimize stock levels[cite: 6]:
- Beauty: 443 units[cite: 6]
- Home & Kitchen: 433 units[cite: 6]
- Apparel: 410 units[cite: 6]
- Electronics: 405 units[cite: 6]

# 5. 🏆 Product Winners & Profitability Analysis
 Track individual product profitability to identify top drivers[cite: 7]:
- Laptop Pro: Top profit generator at ₹49,600[cite: 7]
- Smart Watch v2: ₹15,200[cite: 7]
- Air Fryer XL & Fragrance Luxe: ₹8,760 each[cite: 7]
- Running Shoes: ₹7,930[cite: 7]

# 🗂️ Data Schema & Transactional Features
The underlying data model processes row-level retail transactions with the following fields[cite: 2]:
| Column Name | Description | Example Value |
|---|---|---|
| Transaction_ID    |     Unique identifier for each order |   TXN-10000               |
| Date & Month      |     Order execution timestamp        |   2025-04-13 /April       |
| Store_Location    |      Store location branch           |   NY Flagship             |
| Region            |      Regional classification         |   East                    |
| Customer_ID       |      Customer unique identifier      |   CUST-1161               |
| Segment           |      Customer membership tier        |   Regular, Premier, Value |
| Product_Category  |      High-level category             |   Electronics             |   | Product_Name      |      Specific item title             |   Wireless Buds           |
| Quantity_Sold     |      Units purchased in order        |    1                      |
| Unit_Cost         |      Wholesale cost per item         |    50                     |
| Unit_Price        |      Retail selling price            |    99                     |
| Revenue           |      Calculated as                   |                           |
|                   |      Quantity_Sold * Unit_Price      |    99                     |
| Total_Cost        |      Calculated as                   |                           |
|                   |      Quantity_Sold * Unit_Cost       |   50                      |
| Profit            |      Calculated as                   |                           |
|                   |      Revenue - Total_Cost            |   49                      |
| Profit %          |      Calculated margin percentage    |   49.49%                  |
  
# ⚙️ Built With
#### -Microsoft Excel:
Pivot Tables, Pivot Charts, Slicers, Custom KPI Cards, Data Modeling, Dynamic Formulas (SUM, CALCULATED FIELDS).  
