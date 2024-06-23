# 🍔 **Burgerking 💶 Sales 📖 Dataset and 📑 Report 🔀 Generator**

This project generates synthetic sales data for various burgers sold at Burgerking over a year, analyzing sales patterns and ingredient consumption. It includes functionalities to visualize sales reports by burger type, ingredient consumption, and specific time periods.

## 📚 **Necessary Library Imports**

- **pandas**: For data manipulation and analysis.
- **random**: To generate random numbers for sales multipliers.
- **plotly.express**: For creating interactive visualizations.
- **plotly.graph_objects**: Allows creation of customized plots.
- **datetime**: Provides classes for manipulating dates and times.

## 🍔 **Burger Names with their Ingredients**

Defines various burgers and their ingredients using Python dictionaries.

## 🍔 **Burger Names with their Prices 💶 per unit**

Lists prices for each burger type.

## ⏲ **Time Duration to Generate the Dataset**

Defines start and end dates for generating synthetic sales data over one year, with specific peak hours identified.

## 🔀 **Generate the Dataset**

Utilizes nested loops to generate synthetic sales data for each burger type at 15-minute intervals throughout the defined time range. Sales are influenced by seasonality, time of day, and burger characteristics.

## **The Generated Dataset**

Exports the generated sales data to a CSV file named `Burger sales data_one_year.csv`.

## **Total 💰 Turnover Report**

### `sales_report_by_burger_visualization(start_date, end_date, months, start_time=None, end_time=None)`

Generates a bar chart visualization depicting the turnover by burger type within specified date and time ranges. Allows filtering by months and optionally by time.

### **🛠 Filters to Adjust Desired Range**

Example usage demonstrates filtering options for the `sales_report_by_burger_visualization` function based on date and time.

## **🍔 Ingredients Consumption Report**

### `sales_report_by_ingredient_visualization(start_date, end_date, months, start_time=None, end_time=None)`

Creates a bar chart showing total ingredient consumption across all burgers within specified date and time ranges. Provides options to filter by months and time.

### **🛠 Filters to Adjust Desired Range**

Example usage illustrates how to filter the `sales_report_by_ingredient_visualization` function based on date and time.

## **⚒ Slicers Including BURGER NAME**

### `sales_report_by_burger_name_visualization(start_date, end_date, start_time=None, end_time=None, burger_name=None)`

Generates two visualizations:
1. Bar chart showing quantity sold by month and time category (peak hours vs. non-peak hours).
2. Bar chart illustrating ingredient consumption for a specific burger type. Also calculates key performance indicators (KPIs) such as total revenue, average revenue per burger, and more.

### **⚒ Slicers for the Desired Filters**

Example usage demonstrates filtering options for the `sales_report_by_burger_name_visualization` function based on date, time, and burger name.
