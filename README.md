
# 🍔 Burgerking 💶 Sales 📖 Dataset and 📑 Report 🔀 Generator

## Overview

This repository contains code to simulate and analyze sales data for a variety of burgers offered by Burgerking. It includes functions to generate synthetic sales data over a specified time period, visualize sales reports, and analyze ingredient consumption. Below is an overview of the key functionalities and methods provided in the code.

## Key Functionalities

### 1. Burger and Ingredient Definitions

The code defines different types of burgers offered by Burgerking along with their respective ingredients and prices. This information is crucial for simulating sales and calculating ingredient consumption.

### 2. Dataset Generation

The script generates synthetic sales data for each burger type at regular intervals throughout a specified time range (typically one year). Sales are influenced by factors such as time of day, month of the year, and specific characteristics of each burger type (e.g., size, meat type).

### 3. Total Turnover Report

#### Function: `sales_report_by_burger_visualization`

- Generates a bar chart showing the turnover (total sales revenue) for each burger type over a specified date range and optional time range.
- Allows filtering by specific months and times of day to analyze sales trends.

### 4. Ingredients Consumption Report

#### Function: `sales_report_by_ingredient_visualization`

- Produces a bar chart depicting the total consumption of each ingredient across all burger types over a specified date range and optional time range.
- Useful for inventory management and understanding ingredient usage patterns.

### 5. Slicers and Custom Reports

#### Function: `sales_report_by_burger_name_visualization`

- Provides customizable reports based on specific burger names, allowing detailed analysis including:
  - Quantity sold by month and time category (peak hours vs. non-peak hours).
  - Ingredient consumption breakdown for the selected burger.
  - Key Performance Indicators (KPIs) such as total revenue, average revenue per burger, peak hour sales, and more.

## Usage

### Generating Sales and Reports

1. **Total Turnover Report Example:**
   - Adjust date and time filters (`start_date`, `end_date`, `months`, `start_time`, `end_time`) as needed.
   - Use `sales_report_by_burger_visualization` function to visualize turnover by burger type.

2. **Ingredients Consumption Report Example:**
   - Modify date and time filters (`start_date`, `end_date`, `months`, `start_time`, `end_time`) based on requirements.
   - Utilize `sales_report_by_ingredient_visualization` function to visualize ingredient consumption trends.

3. **Custom Reports with Slicers:**
   - Define specific parameters (`start_date`, `end_date`, `start_time`, `end_time`, `burger_name`) to create detailed reports using `sales_report_by_burger_name_visualization`.
   - This function provides insights into sales patterns, ingredient usage, and KPIs tailored to a chosen burger type.

## Additional Information

- The code utilizes Python libraries such as Pandas for data manipulation, Plotly for interactive visualizations, and datetime for handling date-time operations.
- It includes provisions for adjusting sales multipliers based on seasonal variations, burger characteristics, and peak hours to simulate realistic sales data.
- Outputs generated include CSV files of sales data and interactive visualizations depicting turnover, ingredient consumption, and customized reports.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE.txt) file for details.

## Acknowledgments

- The code template and dataset structure were inspired by the requirements of Burgerking sales analysis.

## **Note:** The data presented in this repository, including names, sales figures, ingredients, etc., is completely fictional and is used solely for educational purposes. It has no relation to any real Burgerking company or entity.
