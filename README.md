# Chocolate Sales Analysis
## Project Overview
This project analyzes chocolate sales data and provides insights using various Excel formulas and PivotTables. The analysis includes sales person,amount,and units for different products across regions.

## Features
- **Formulas Used**:
  - Average, Median, Min, Max, Range, First Quater, 3rd Quater
  - Conditional Formatting (Data Bars, Color Scales, Icon sets)
  - `VLOOKUP` to retrieve unit prices from a separate table.
  - `SUMIFS`,'AVERAGEIFS' to calculate amounts and units for each product.
  - `IF` statements to flag negative profit margins.
- **Pivot Tables**:
  - A pivot table is used to summarize sales by product and region.
  - Dynamic filtering allows easy analysis of sales and profit by different geographies.
  - Slicer to filter the data by different geographies.
- **Charts**:
   - Box & Whisker chart used to identify the anolomilies in the data
 
## File Information
- The file `ChocolateSales_Dataset.xlsx` contains all data and analysis.
- **Sheet 1**: Raw sales data including sales person names,geography,product names,amounts and units. and supporting table it contains product name and cost per unit.
- **Sheet 2**: Combined sales table data and support table data and basic statistics are calculated (Average, Median, Min, Max, Range, First Quater, 3rd Quater)
- **Sheet 3**: By using conditional formatting hihglited larger amounts using color scales and units with data bars.
- **Sheet 4**: Calculated Total amounts and units per geography by using SUMIFS formula
- **Sheet 5**: Calculated Total amounts and units per geography by using Pivot table
- **Sheet 6**: Identified top 5 products $ per unit using pivot table
- **Sheet 7**: Identified anolomy detection using Box and Wisker charts
- **Sheet 8**: Best sales person and least sales person by geography using pivot tables
- **Sheet 9**: Profits by product and added geography as a slicer.
- **Sheet 10**: Dynamic geography level sales report
- **Sheet 11**: Identify which products to discontinue

## How to Use
1. Open the `ChocolateSales_Dataset.xlsx` file in Excel.
2. Navigate to the PivotTable section to filter sales by region or product.
3. Use the filters to explore different geographies or products or sales persons.
