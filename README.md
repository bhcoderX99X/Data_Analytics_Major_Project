# 🛒 Retail Store Analytics System Dashboard

An end-to-end interactive Excel Analytics Dashboard designed to analyze sales performance, customer distribution, inventory pull, product profit margins, and regional store performance for retail operations.


## 📌 Executive Summary Key Performance Indicators (KPIs)
- Total Revenue: ₹3,01,401
- Total Quantity Sold: 1,691 units
- Total Profit: ₹1,31,086
- Average Profit Margin: 55.40%
     
##  📊 Core Features & Analysis Breakdown
### 1. 📈 Sales & Monthly Revenue Analytics
- Track monthly trends comparing Sum of Revenue vs. Sum of Profit.
- Highlight peak revenue months (e.g., July generating ₹32,671 in revenue and ₹13,266        in profit).
### 2. 🏪 Store & Regional Performance
 Evaluate overall sales and revenue distribution across multiple physical locations:
- Atlanta Downtown (Highest performer at ₹46,604 revenue)
- LA Center (₹42,515 revenue)
- NY Flagship (₹40,063 revenue)
- Miami Beach (₹39,696 revenue)
- Seattle Wharf (₹38,705 revenue)
- Boston Common (₹27,552 revenue)
- Interactive slicer support for East, North, South, and West regions.
# 3. 👥 Customer Segmentation Distribution
- Categorize customer purchasing volume across three core tiers:
- Regular Customers: 843 units (50%)
- Value Customers: 496 units (29%)
- Premier Customers: 352 units (21%)
# 4. 📦 Inventory Pull Analytics
 Monitor quantity sold by product category to optimize stock levels:
- Beauty: 443 units
- Home & Kitchen: 433 units
- Apparel: 410 units
- Electronics: 405 units

# 5. 🏆 Product Winners & Profitability Analysis
 Track individual product profitability to identify top drivers:
- Laptop Pro: Top profit generator at ₹49,600
- Smart Watch v2: ₹15,200
- Air Fryer XL & Fragrance Luxe: ₹8,760 each
- Running Shoes: ₹7,930

# 🗂️ Data Schema & Transactional Features
The underlying data model processes row-level retail transactions with the following fields:
| Column Name | Description | Example Value |
|---|---|---|
| Transaction_ID    |     Unique identifier for each order |   TXN-10000               |
| Date & Month      |     Order execution timestamp        |   2025-04-13 /April       |
| Store_Location    |      Store location branch           |   NY Flagship             |
| Region            |      Regional classification         |   East                    |
| Customer_ID       |      Customer unique identifier      |   CUST-1161               |
| Segment           |      Customer membership tier        |   Regular, Premier, Value |
| Product_Category  |      High-level category             |   Electronics             |   
| Product_Name      |      Specific item title             |   Wireless Buds           |
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
---

### Microsoft Excel:
- Pivot Tables, Pivot Charts, Slicers, Custom KPI Cards, Data Modeling, Dynamic Formulas (SUM, CALCULATED FIELDS).

### Power BI:
- Data Source & Requirements, Transform Data, DAX Measures & KPI Calculation, Visual Layout & Slicers, Formatting & Theme Styling  and Publish & Automate.

### Python 3:
- Python Libraries Used :- Pandas, MatplotLib, & Seaborn <br>
- Data cleaning, Data Visualization by chart, Formatting & Styling


## 🛠️ Tech Stack & Tools

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook (`IIOT_Project.ipynb`)
* **Libraries:** `pandas`, `matplotlib`, `seaborn`
* **Data Format:** Microsoft Excel (`IIOT_Dataset.xlsx`)



## 📈 Visualizations & Key Features

1. **Monthly Profit Trends:** Line plot tracking overall profitability across time (`Total Monthly Profit (2025)`).
2. **Category Performance:** Bar charts analyzing total `Quantity Sold` and regional breakdown of profit across `Electronics`, `Home & Kitchen`, `Beauty`, and `Apparel`.
3. **Revenue by Store Location:** Horizontal bar charts displaying sales top-performers (e.g., Atlanta Downtown, Seattle Wharf).
4. **Customer Segment Breakdown:** Distribution of sales revenue by customer segments (`Value`, `Regular`, `Premier`).
5. **Statistical Distribution Analysis:** Histograms and Kernel Density Estimation (KDE) plots illustrating revenue spread and sales volume distribution.
6. **Executive Dashboard:** Integrated dashboard summary showcasing key metrics including total profit, quantity sold, total cost, and strategic store highlights.


## 🚀 Getting Started

### Prerequisites for Python , MySQL Connector:

Ensure you have My SQL along with mysql server, mysql workbench 8.0, mysql shell and required packages.
Ensure you have Python installed along with the required libraries:

```bash
pip install pandas matplotlib seaborn openpyxl notebook
