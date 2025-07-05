# Microsoft Fabric: Excel Data Normalization with Notebooks

This project uses Microsoft Fabric's built-in notebooks to transform and normalize raw Excel sales data into structured tables for analysis and reporting.

## 🧰 Tools Used

- Microsoft Fabric Notebooks
- Python (Pandas)
- Excel (raw input files)

## 📁 Project Overview

The notebook combines and cleans three monthly Excel order files (Jan–Mar) and a separate sales summary sheet. The result is a set of normalized tables:

- `bookings`
- `customers`
- `items`
- `sales`

All transformations were done using Pandas inside Fabric's notebook environment.

## 🧪 Workflow Summary

1. Uploaded Excel files to Fabric workspace
2. Used Fabric Notebook to:
   - Load and merge monthly orders
   - Clean and standardize columns
   - Normalize tables using joins and groupings
3. Output results for downstream Power BI analysis (not included here)

## 📸 Screenshots
