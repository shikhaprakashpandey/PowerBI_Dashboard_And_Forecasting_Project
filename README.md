# PowerBI_Dashboard_And_Forecasting_Project



![Dashboard Preview](Dashboard.png)

# Store Sales Forecasting

## Project Overview
This project aims to forecast store sales using data analysis and visualization techniques in Excel, SQL, and Power BI. The dataset contains sales transactions, customer details, product categories, and other key attributes essential for sales trend analysis.

## Tools Used
- **Excel**: Data cleaning, preprocessing, and exploratory analysis
- **SQL**: Data transformation, querying, and aggregation
- **Power BI**: Data visualization and forecasting dashboard

## Dataset
The dataset includes:
- **Order Details**: Order ID, Order Date, Ship Date, Ship Mode
- **Customer Information**: Customer ID, Customer Name, Segment, Country, City, State, Region
- **Product Details**: Product ID, Category, Sub-Category, Product Name
- **Sales Metrics**: Sales, Quantity, Profit, Returns, Payment Mode

## Project Workflow
1. **Data Cleaning**: 
   - Handle missing values (e.g., Returns column)
   - Correct date formats
   - Remove unnecessary columns (e.g., `ind1`, `ind2` with all null values)
   
2. **SQL Processing**:
   - Import data into SQL database
   - Aggregate sales by region, product category, and customer segment
   - Compute profit margins and return rates
   
3. **Excel Analysis**:
   - Identify sales trends using pivot tables
   - Calculate moving averages for forecasting
   
4. **Power BI Dashboard**:
   - Create interactive sales visualizations
   - Forecast future sales trends using Power BI forecasting tools
   - Display key metrics such as total revenue, profit, and high-return products

## Installation & Usage
1. Load the dataset into SQL for querying and transformation.
2. Use Excel for initial exploration and trend identification.
3. Import cleaned data into Power BI for visualization and forecasting.

## Future Improvements
- Implement machine learning models for advanced forecasting.
- Automate data pipeline updates using Python.
