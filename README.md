# Internet_Sales_Analysis
This project is about internet sales of a hardware, eqiupments and accesories store . It includes creation of multiple  interactive dashboards .This project is mostly done as a practise project.

## ABOUT THE DATASET
This dataset consists of 4 tables:
- CALENDER: This table contains all the data related to dates.
- CUSTOMER: This table contains all the data related to customers.
- PRODUCT ID: This table contains all the data related to products.
- INTERNET SALES:This table contains all the data related to the online sales.

There are multiple columns from the tables .Few exampples:
- ProductModelName: Name of the product models.
- ProductCategory: Categories of the products.
- ProductColour: Colour of the products.
- ProductSize: Size of the products.
-  FirstName: First name of the customers.
- LastName: Last name of the customers.
- FullName: Full name of the customers.
- OrderDateKey: Order date of the products.
- ShipDateKey: Shipping date of the orders.

## QUERIES
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/Customer.png)
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/Product.png)
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/calender.png)
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/internet_sales.png)

## Steps for Cleaning and Data and END 
### 1. Removing unnecessary columns.<br>
Removing EmailAddress,YearlyIncome,TotalChildren,NumberChildrenAtHome, EnglishEducation,SpanishEducation,FrenchEducation,EnglishOccupation,SpanishOccupation,FrenchOccupation,HouseOwnerFlag,NumberCarsOwned,AddressLine1,AddressLine2,Phone,etc

These columns are of no use right now hence they are removed by declaring them as comments through SQL sever query.

### 2. Removing NULL values from column.
NULL values from industry column are removed in the industry column through value selection option in POWER BI.

## Insights:
- Total Sales-22194469
- Mountain-200-Black_42,Mountain-200-Silver_38,Mountain-200-Black_38,Mountain-200-Black_46,Mountain-200-Silver_46 are top 5 products thats been sold while the sales peaked twice in the month od june and dec in 2020
- Jordan Turner-Nov,Maurise Shan-Jan,Janet Mulonoz-Jan,Usa Cal-Aug,Lancy Zheng-Nov are the top 5 customers with the month of max sales.

## Dashboards
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/dashboard%201.png)
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/dashboard%202.png)
![](https://github.com/praveenmandal/Internet_Sales_Analysis/blob/main/sales_analysis/insights/dashboard%203.png)
