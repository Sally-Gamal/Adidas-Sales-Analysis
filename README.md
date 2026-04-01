# 👟 Adidas Sales Analysis Project

## 1. 📊 Dashboard
![Adidas Sales Dashboard](Adidas_Sales_Dashboard.jpg)

---

## 2. 📝 About the Dataset
An Adidas sales dataset is a collection of information on products sales. It includes details such as:
* Number of units sold.
* Total sales revenue.
* Location of the sales.
* Type of product sold.

This data is essential for analyzing sales trends, identifying successful products, and developing strategies for future growth or comparing performance against competitors.

---

## 3. 📑 Data Description
| Column | Description |
| :--- | :--- |
| **Retailer** | Business or individual selling Adidas products directly to consumers. |
| **Retailer ID** | A unique identifier assigned to each retailer. |
| **Invoice Date** | The date when the sales transaction took place. |
| **Region / State / City** | Specific geographical area where the operations occur. |
| **Product** | Classification of Adidas products. |
| **Price per Unit** | The cost associated with a single unit of a product. |
| **Units Sold** | Quantity of units sold during a transaction. |
| **Total Sales** | Overall revenue generated. |
| **Operating Profit** | Profit earned from normal business operations. |
| **Sales Method** | The channel used (In-store, Online, Outlet). |

---

## 🔍 4. Questions & Analysis
### General Data Cleaning Questions:
* Are there **missing values** or **wrong datatypes**?
* Are there **duplicates** or **outliers** in numerical columns?

### Business Questions:
* What is the breakdown of sales by retailers?
* What is the total sales and Operating Profit by **Region, Product, and Season**?
* What is the distribution of sales by the **top 20 states**?

---

## 💡 5. Conclusion (Key Insights)
* **Top Retailers:** **West Gear** (27%) and **Foot Locker** (24%) emerge as leaders.
* **Top Regions:** **West** (30%) and **Northeast** (21%) are the strongest regions.
* **Top Products:** **Men’s Street Footwear**, **Women’s Apparel**, and **Men’s Athletic Footwear** account for 60% of total sales.
* **Seasonality:** Sales peak in **Summer** (29%) and **Winter** (24%), likely due to school seasons and holidays.
* **Growth:** 2021 saw significantly higher sales than 2020 (Post-Covid recovery).
* **Top Sales Method:** **Online** sales ranked first (37%), followed by **Outlet** (33%).
* **Locations:** New York and California have the highest sales volume.

---

## 🛠️ 6. Data Cleaning Summary (The Professional Touch)
I performed several steps to ensure the data was ready for analysis:
* **Missing Values:** Dropped rows with missing values in the `Price per Unit` column.
* **Date Transformation:** Extracted `Year`, `Month`, and `Day` from `Invoice Date` and created a `Season` column.
* **Categorical Fixes:** Fixed spelling errors and duplicates in the `Product` column.
* **Formatting:** Removed dollar signs ($) and commas from `Price per Unit`, `Units Sold`, and `Total Sales`.
* **Accuracy Checks:** * Identified zero-value sales (likely refunds) and removed them.
    * Found and fixed incorrect calculations in `Total Sales` and `Operating Profit` columns using verified formulas.
