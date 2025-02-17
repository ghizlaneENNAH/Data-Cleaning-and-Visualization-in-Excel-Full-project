# Data Cleaning and Visualization in Excel

## Project Overview
This project focuses on cleaning and analyzing a dataset of bike buyers using Excel. The process includes data cleaning, creating pivot tables, and designing a dashboard for visualization.

## Dashboard Preview
Here is a preview of the final dashboard:

![Dashboard Screenshot](dashbord.png)

## Files in the Project
- **Excel Project Dataset.xlsx**: Contains the original bike buyers dataset.
- **Excel Project Dataset_WorkingSheet.xlsx**: Includes the cleaned dataset, pivot tables, and dashboard.

## Steps

### Data Cleaning (WorkingSheet)
1. Create three sheets: **WorkingSheet**, **Pivot Table Sheet**, and **Dashboard Sheet**.
2. Copy the `Bike Buyers` sheet into **WorkingSheet**.
3. Apply filters to all columns and check values.
4. Remove duplicates using the **Remove Duplicates** button.
5. Standardize values:
   - Replace `M` with `Married` and `S` with `Single` in the `Marital Status` column.
   - Replace `M` with `Male` and `F` with `Female` in the `Gender` column.
6. Convert `Income` to currency format and remove extra zeros.
7. Create an **Age Brackets** column:
   - `<31`: **Invalid**
   - `31-55`: **Middle Age**
   - `>55`: **Old**

### Pivot Table Sheet
8. Create a pivot table with:
   - `Gender` in rows
   - `Purchased Bike` in columns
   - `Income` in values (set to **Average** instead of Sum)
9. Add a **Clustered Column Chart** with titles and a data table.
10. Create another pivot table:
    - `Commute Distance` in rows
    - `Purchased Bike` in values and columns
11. Generate a **Line Chart** and adjust `10+ Miles` to appear at the end (rename as `10 Miles +`).
12. Add a pivot table:
    - `Age Brackets` in rows
    - `Purchased Bike` in columns and values
13. Add a **Line Chart**.
14. Copy the last pivot table and change `Age Brackets` to `Age` in rows, then add another **Line Chart**.

### Dashboard Sheet
15. Copy all charts to the **Dashboard Sheet** and adjust the layout.
16. Insert a **Slicer** for `Marital Status` and connect it to all pivot tables.
17. Add **Slicers** for `Region` and `Education`, then link them to all pivot tables.

## Summary
This project applies essential data cleaning techniques and Excel visualization tools to analyze bike buyers' data efficiently.

