# AI-Powered Global Trade & Business Intelligence

## 1. Project Overview

An end-to-end AI-powered business intelligence platform for a fictional international trading company operating across retail, wholesale, e-commerce, import, and export markets.

The system will use Python, SQL, Machine Learning, Power BI, Streamlit, and Generative AI to convert business data into actionable insights.

## 2. Business Model

The company operates through five business segments:

1. Retail Sales – Direct sales to individual customers.
2. Wholesale Sales – Bulk sales to retailers and distributors.
3. Import Business – Purchasing products from international suppliers.
4. Export Business – Selling domestic products to international customers.
5. Online Business – E-commerce orders through a website or application.

## 3. Product Categories

- Food and Agricultural Products
- Electronics and Accessories
- Clothing and Textiles
- Household Products

## 4. Dataset Plan

| Dataset | Target Records |
|---|---:|
| Customers | 500 |
| Products | 100 |
| Suppliers | 30 |
| Sales Orders | 3,000 |
| Sales Order Items | 6,000+ |
| Purchase Orders | 500 |
| Inventory Movements | 5,000+ |
| Import Orders | 200 |
| Export Orders | 200 |
| Shipments | 500 |
| Exchange Rates | 700+ |
| Countries | 20 |

## 5. Dataset Date Range

2025-01-01 to 2026-10-31

## 6. Currency

- Base Currency: INR
- Foreign Currencies: USD, EUR, GBP, AED, JPY
- Exchange rates will be represented as synthetic historical data.

## 7. Main Business Metrics

- Gross Sales Revenue
- Net Sales Revenue
- Cost of Goods Sold
- Gross Profit and Profit Margin
- Import Cost
- Export Revenue
- Shipping and Logistics Cost
- Customs and Other Trade Costs
- Landed Cost
- Inventory Turnover
- Customer Lifetime Value
- Order Fulfilment Rate

## 8. Analytics and Machine Learning Features

1. Sales and Profit Analytics
2. Customer RFM Segmentation
3. Product Performance Analysis
4. Dead Stock Detection
5. Sales Forecasting (7, 15 and 30 days)
6. Inventory Demand Prediction
7. Country-wise Import and Export Analysis
8. Currency Impact Analysis
9. Import Landed Cost Analysis
10. Shipment and Delivery Performance

## 9. Technology Stack

- Python
- Pandas and NumPy
- MySQL
- SQL
- Matplotlib, Seaborn and Plotly
- Scikit-learn
- Power BI
- Streamlit
- Generative AI API
- Git and GitHub

## 10. Data Format

CSV for source datasets, SQL tables for database storage, and processed datasets for analytics and machine learning.

## 11. Data Quality Rules

- Every customer, product, supplier and order must have a unique ID.
- Foreign keys must reference valid records.
- Quantities and prices must be non-negative.
- Order totals must reconcile with their line items.
- Currency conversion must use the corresponding exchange rate.
- Import landed cost must account for applicable purchase, freight, insurance, customs and other included costs.
- Inventory movements must reconcile with stock balances.
- Synthetic records must be clearly documented.

## 12. Project Objectives

Build a complete business intelligence system that helps management understand sales, profitability, customers, inventory, international trade, logistics and future business demand.

## 13. Team Responsibilities

### Manthan
- Python and Pandas
- Dataset generation
- Data cleaning and validation
- Exploratory Data Analysis
- Machine Learning and forecasting
- AI assistant integration

### Rajan
- Database design
- MySQL and SQL queries
- Data relationships
- Power BI dashboards
- Database testing and optimization

### Joint Responsibilities
- Architecture review
- Integration and testing
- Streamlit application
- GitHub documentation
- Final deployment