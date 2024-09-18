

# Dynamic Retail Dashboard

## Objective

This repository contains a dynamic retail dashboard created using Microsoft Excel. The dashboard is designed to provide insightful analyses of retail data, specifically using a dataset from Walmart. The primary objective is to deliver a comprehensive tool that allows users to interactively analyze key performance indicators (KPIs) and gain insights into various aspects of retail operations.

## Dataset

The dashboard is built using the following datasets:

1. **Orders**: Contains detailed information about retail orders, including Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, City, State, Country, Postal Code, Market, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost, and Order Priority.

2. **People**: Lists information about individuals and their associated regions.

3. **Returns**: Includes information about returned orders and their respective markets.

The datasets are provided in the repository for reference and can be found in the `/datasets` folder.

## Sample Dataset

Here is a snapshot of the dataset used in the dashboard:

### Orders Data

| Order ID       | Order Date  | Ship Date  | Ship Mode   | Customer Name    | Country        | Sales   | Profit   | Quantity | Category   |
|----------------|-------------|------------|-------------|------------------|----------------|---------|----------|----------|------------|
| CA-2012-124891 | 31-07-2020  | 31-07-2020 | Same Day    | Rick Hansen      | United States  | 2309.65 | 762.18   | 7        | Technology |
| IN-2013-77878  | 05-02-2021  | 07-02-2021 | Second Class| Justin Ritter    | Australia      | 3709.39 | -288.76  | 9        | Furniture  |
| IN-2013-71249  | 17-10-2021  | 18-10-2021 | First Class | Craig Reiter     | Australia      | 5175.17 | 919.97   | 9        | Technology |
| ES-2013-1579342| 28-01-2021  | 30-01-2021 | First Class | Katherine Murray | Germany        | 2892.51 | -96.54   | 5        | Technology |
| SG-2013-4320   | 05-11-2021  | 06-11-2021 | Same Day    | Rick Hansen      | Senegal        | 2832.96 | 311.52   | 8        | Technology |

### Returns Data

| Returned | Order ID       | Market        |
|----------|----------------|---------------|
| Yes      | MX-2013-168137  | LATAM         |
| Yes      | US-2011-165316  | LATAM         |
| Yes      | ES-2013-1525878 | EU            |
| Yes      | CA-2013-118311  | United States |
| Yes      | ES-2011-1276768 | EU            |

### People Data

| Person           | Region   |
|------------------|----------|
| Anna Andreadi    | Central  |
| Chuck Magee      | South    |
| Kelly Williams   | East     |
| Matt Collister   | West     |
| Deborah Brumfield| Africa   |

## KPIs and Analysis

The dashboard includes several KPIs and analyses, including:

- **KPIs:**
  - **Total Sales**: Sum of Sales (🔍)
  - **Total Profit**: Sum of Profit (💰)
  - **Total Quantity**: Sum of Quantity (📦)
  - **Avg Discount**: Average of Discount (💹)
  - **Total Orders**: Count of Order ID (🛒)
  - **Profitability**: Sum of Profitability (📈)

- **Analyses:**
  - Total Sales, Total Profit, Quantity, Number of Orders, and Profit Margin
  - Sales and Profit Analysis
  - Category Wise Profit
  - Category Wise Sales Share %
  - Sales by Country
  - Top 5 Subcategories
  - Bottom 5 Subcategories
  - Yearly Sales Trend
  - Return Analysis
  - Top Customers
  - Bottom Customers

## Conclusion

The dynamic retail dashboard provides a comprehensive view of retail performance, enabling users to easily interact with and analyze data. The use of Excel for this dashboard makes it accessible to a wide range of users, including those without specialized data analysis software. By using slicers and pivot tables, users can filter and explore various aspects of the dataset to gain valuable insights into sales performance, profitability, and customer behavior.

## Significance

This dashboard is a valuable tool for retail analysts, managers, and decision-makers who need to monitor and evaluate business performance. It provides a user-friendly interface for exploring key metrics and trends, helping stakeholders make informed decisions based on real-time data. The ability to analyze sales, profit, and customer data in an interactive format allows for better strategic planning and operational improvements.

Feel free to explore the dashboard, analyze the data, and adapt it to your specific needs. Contributions and improvements are welcome!

## How to Use

1. **Download the Dataset**: Access the datasets provided in the `/datasets` folder.
2. **Open the Dashboard**: Open the Excel file included in the repository.
3. **Interact with the Dashboard**: Use the slicers to filter data and explore different KPIs and analyses.
4. **Analyze the Results**: Review the generated charts and tables to gain insights.

###Screenshot
<img width="767" alt="final" src="https://github.com/user-attachments/assets/87010990-4725-44bc-85b9-85b1ddab82e8">




