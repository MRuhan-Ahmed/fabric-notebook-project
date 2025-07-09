# Microsoft Fabric: Excel Data Normalization with Notebooks

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Portfolio-blue)](https://mruhan-ahmed.github.io/Portfolio/#projects)

This project leverages **Microsoft Fabric Notebooks** and **Pandas** to ingest, clean, and normalize raw Excel sales data into structured tables—ready for downstream analysis and reporting.

## 🧰 Tools Used

- **Microsoft Fabric Notebooks** (Notebook environment)  
- **Python** (Pandas) for data transformations  
- **Excel** (source data files)

## 📁 Project Overview

Three months of Excel order data (January–March) plus a sales summary sheet are:

1. Loaded into Fabric’s notebook  
2. Merged and cleaned (column renaming, null handling, type conversions)  
3. Split into four normalized tables:
   - `bookings`
   - `customers`
   - `items`
   - `sales`

These tables power interactive dashboards (e.g., Power BI) for business insights.

## 🧪 Workflow Summary

1. **Upload** raw Excel files to your Fabric workspace.  
2. **Load & merge** monthly orders using Pandas.  
3. **Clean & standardize** columns (rename, drop, fill nulls, convert types).  
4. **Normalize** into separate tables via joins and grouping.  
5. **Export** clean tables for visualization and reporting.

## 📸 Screenshots

Key notebook steps and outputs are in the `screenshots/` directory. You can also browse them on the live site under the **Projects** section:

🔗 [View the Fabric Gallery on my portfolio](https://mruhan-ahmed.github.io/Portfolio/#projects)

## 🚀 Next Steps

- Connect these normalized tables into a **Power BI** or **Tableau** dashboard  
- Extend the notebook to handle new monthly data feeds automatically  
- Add unit tests for data validation  

---

> **Tip:** If you haven’t already, check out my full portfolio for more data projects and interactive galleries:  
> 🔗 https://mruhan-ahmed.github.io/Portfolio/
