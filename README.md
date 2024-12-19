# Athletic Sales Analysis Project - Module 5 Challenge (assignment due 12-18-2024)

## Overview
This project analyzes athletic footwear and apparel sales data across multiple retailers, regions, and time periods. It provides insights into sales trends, regional performance, and product-specific analytics using Python and Pandas.

## Table of Contents
- [Requirements]
- [Installation]
- [Project Structure]
- [Usage]
- [Analysis Features]
- [Data Structure]
- [Repository Information]
- [Contributing & Contact]
- [License]

## Requirements
- Python 3.x
- pandas
- numpy
- Jupyter Notebook

## Installation
1. Clone the repository:
"""bash
git clone https://github.com/yourusername/athletic-sales-analysis.git
cd athletic-sales-analysis
"""

2. Install required packages:
"""bash
pip install pandas numpy jupyter
"""

## Project Structure
"""
athletic-sales-analysis/
│
├── Resources/
│   ├── athletic_sales_2020.csv
│   └── athletic_sales_2021.csv
│
├── athletic_sales_analysis.ipynb
├── README.md

"""

## Usage
1. Launch Jupyter Notebook:
"""
Jupyter notebook
"""

2. Open "athletic_sales_analysis.ipynb"

3. Run cells sequentially to perform the analysis

## Analysis Features
The notebook performs the following analyses:

1. **Data Preparation**
   - Combines 2020 and 2021 sales data
   - Cleans and standardizes data formats
   - Converts date fields to proper datetime format

2. **Regional Analysis**
   - Determines regions with highest product sales
   - Analyzes regional sales performance

3. **Retailer Performance**
   - Evaluates retailer sales metrics
   - Ranks retailers by total sales

4. **Product-Specific Analysis**
   - Focuses on Women's Athletic Footwear performance
   - Identifies peak sales periods by daily and weekly sales patterns

## Data Structure
The analysis uses sales data with the following key fields:
- "retailer": Store name
- "retailer_id": Unique identifier for each retailer
- "invoice_date": Date of sale
- "region": Geographical region
- "state": State location
- "city": City location
- "product": Product category
- "price_per_unit": Unit price
- "units_sold": Quantity sold
- "total_sales": Total revenue
- "operating_profit": Profit margin
- "sales_method": Sales channel (In-store/Online/Outlet)

## Repository Information
- Remote: https://github.com/Raymond-St/athletic_sales_analysis.git
- Local: C:\Users\resto\AI\Projects\Module_5\athletic_sales_analysis

## Contributions & Contact
If interested, or for questions / feedback, please contact: RStover@Gmail.com

## License
This project is not licensed for any public use. This project is for educational purposes and uses sample data. This body of work is for reference only and is Not for production use.