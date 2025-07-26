# E-commerce Sales Dashboard - Retail Sales Analysis (Task 1)

## Project Overview
This repository contains the solution for **Future Interns Data Science & Analytics Task 1: Business Sales Dashboard from E-commerce Data**. The primary objective of this project was to clean and analyze raw e-commerce sales data to build a professional, interactive dashboard. This dashboard aims to provide key business insights to decision-makers, helping them understand:

* What are the best-selling products?
* When do sales peak during the year?
* Which categories or regions bring the most revenue?
* Insights into customer behavior.

## Key Deliverables
* Cleaned E-commerce Sales Data (CSV format)
* Detailed Data Analysis and Insights
* Interactive Sales Dashboard (Power BI .pbix file)
* Presentation of Key Findings and Recommendations

## Data Source
The analysis was performed on the **Year 2009-2010 E-commerce Sales Data** which contains over 500K online sales transactions from a UK-based retailer.

## Data Cleaning and Preparation
The raw dataset required several cleaning and transformation steps to ensure data quality and usability for analysis. These steps were performed using Python (Pandas library):
* **Handling Missing Values:** Rows with missing `Customer ID` were removed to ensure accurate customer behavior analysis.
* **Data Type Correction:** `InvoiceDate` was converted to datetime format, and `Customer ID` was converted to integer type.
* **Outlier/Invalid Data Removal:** Transactions with non-positive `Quantity` (indicating returns/invalid entries) and non-positive `Price` (invalid pricing) were filtered out.
* **Duplicate Removal:** Exact duplicate rows were identified and removed.

The cleaned dataset, `cleaned_e-commerce_sales_2009-2010.csv`, is available in this repository.

## Analysis Performed & Key Insights

After data cleaning, the following analytical questions were addressed:

1.  **Best-Selling Products:**
    * **By Revenue:** Identified products generating the highest total sales revenue. The "WHITE HANGING HEART T-LIGHT HOLDER" and "REGENCY CAKESTAND 3 TIER" emerged as top performers.
    * **By Quantity:** Determined products with the highest units sold. "WHITE HANGING HEART T-LIGHT HOLDER" also ranked highest in quantity sold.

2.  **Monthly Sales Trends (Sales Peaks):**
    * Analysis of monthly total revenue revealed a significant sales peak in **October and November 2010**, strongly suggesting a surge during the holiday shopping season.

3.  **Regional Performance (Country-wise Revenue):**
    * The **United Kingdom** was the dominant country in terms of total sales revenue, as expected for a UK-based retailer.
    * **EIRE** and the **Netherlands** were identified as the next leading revenue contributors.

4.  **Customer Behavior (Top Customers by Revenue):**
    * Identified high-value customers based on their total spending. Customer IDs `18102`, `14646`, and `14156` were found to be among the top contributors.

## Tools Used

* **Python:** For data cleaning and preliminary analysis (Pandas, Matplotlib, Seaborn).
* **Microsoft Excel:** For basic data exploration and formatting (if used during your process).
* **Power BI Desktop:** For building the interactive sales dashboard and visualizing insights.

## How to Access and Use the Dashboard

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/praneethsaiD/FUTURE_DS_01/blob/main/TASK%201.pbix
    ```
    (Replace with your actual repository URL)

2.  **Open Power BI Dashboard:**
    * Ensure you have Power BI Desktop installed (download from [Power BI website](https://powerbi.microsoft.com/en-us/downloads/)).
    * Open the `Task 1.pbix` (or similar name) file located in this repository using Power BI Desktop.

3.  **Explore the Data:**
    * The dashboard includes interactive filters (slicers) for Year, Month, and Country, allowing you to slice and dice the data.
    * Hover over visuals for detailed tooltips.

## Future Enhancements

* Implementing customer segmentation based on purchasing behavior.
* Forecasting future sales trends using more advanced time-series models.
* Analyzing product categories if such data becomes available.
* Integrating additional datasets (e.g., marketing spend, website traffic) for a more holistic view.

## Contact
Feel free to reach out if you have any questions or feedback!

**Name:Donthireddy Praneeth Sai Durga Reddy**
LinkedIn: (www.linkedin.com/in/donthireddy-praneeth-sai-durga-reddy)
Email: praneethsaidurgareddy@gmail.com

---
