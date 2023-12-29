# Sales-Dashboard-PowerBi

## Data and Tools Used

**Data** - Section Six Data Extract.xlsx (contains 1 fact table - fact_InternetSales and 4 dimension tables - dim_Product, dim_SalesTerritory, dim_Currency, dim_Customer)

**Data Cleaning & Visualization** - Microsoft Power Query and PowerBI

## Tasks:

1. Import all five tables from the Excel File called “Section Six Data Extract” into Power Query Mode
2. Create “Username” column inside dim_Customer table from the email address column
3. Scan the dim_Customer table and look out for columns with lots of Null values and remove them from the table
4. Import the tables into the model and check the connections between tables, make sure that every table is connected
5. Create #Measures table using DAX
6. Create dim_Date table using “fact_InternetSales[ShipDate]” column and create the following columns “Year”, “Month”, “Month Name”, “Day of Week”, “Quarter”, “Year/Quarter”
7. Dynamic measure for selected currency, based on the selected currency the measure should return the sales amount in the selected currency, if no currency has been selected the measure 
   should say “No currency selected”
8. Dynamic measure for title that should say “Sales Amount in [Selected Currency] vs All Currencies“, alternatively it should say “Please Select Currency from the Dropdown Menu”
9. Create a few basic measures which can be used in calculations such as percentages
10. Create measures for Previous One Month, Previous Three Months and Previous Six Months
11. Measure that will tell us the time the report was last opened, text should say “Executed: Date and Time”
12. Insert a Header and Logo
13. Create buttons for “Clear Filters”, “Users”, “Currency”, “Sales Territory”.
14. Create dropdown menus using bookmarks for Users, Currency and Sales Territory. Create a bookmark that clears all the filters and apply it to “Clear Filters” button
15. Import Timeline Slicer into the visualisations panel. The slicer should be positioned below the header
16. Create three boxes – first one to show Sales Amount in Selected Currency, second one to show Sales Amount for All Currencies in Previous Month, Sales Amount for All Time for All 
    Currencies. Sales Amount for Last Month and Sales Amount for All Time should not be filtered when choosing currency or region from the Header menu
17. Increase Canvas Size to 1720h x 1280w
18. Using Line and stacked column chart create a visual that shows all Sales Amount in All Currencies, split by month name.
19. Additional Dynamic Title Measure to be created. This title should tell us Total Products sold in the selected country or alternatively Total Products Sold Worldwide. This should be 
    triggered by the Sales Territory Dropdown button from the Header
20. Number of Products Sold by Country to be shown inside a map visual
21. Create a table that shows the SalesTerritory along with the Sales Amount as %, Total Sales Amount, Sales for Previous One Month, Previous Three Months, Previous Six Months.

## Summary:

All the tasks have been performed. All the measures are stored in a separate table (#Measures). Below is a snap of the final dashboard:

![image](https://github.com/mayur-789917/Sales-Dashboard-PowerBi/assets/154932494/a58e4e90-ebe7-454c-a149-3464d3df0500)
