# Supply-Chain-Management-Project
Interactive Power BI dashboard showing inventory, sales, supplier, and shipping metrics.Dashboard analyzing supply chain performance with Excel data. Includes KPIs for sales, inventory, supplier lead time, and shipping reliability. Built end-to-end with data cleaning, modeling, and interactive visuals. Demonstrates skills in Power Query, DAX, and dashboard design for business decision-making and portfolio showcase.

## Quick links
- View dashboard PDF: [Open PDF](https://github.com/asadkarim1/Supply-Chain-Management-Project/blob/main/Supply%20Chain%20Management%20Dashboard.pdf)
- Download dataset: [supply_chain_dataset_clean.xlsx](https://github.com/asadkarim1/Supply-Chain-Management-Project/blob/main/Supply%20Chain%20Mgt%20Dataset.xlsx)

## What I delivered
- Built the data model from the provided Excel file.
- Created measures and calculated columns.
- Designed report pages and visuals that match the supplied dashboard PDF.
- Exported screenshots for quick review.

## Files in this repo
- `Supply Chain Management Dashboard.pdf`  
- `supply_chain_dataset_clean.xlsx`

## Data source
- Primary dataset: `supply_chain_dataset_clean.xlsx`  
- Visual spec and export: `Supply Chain Management Dashboard.pdf`

## How to view the PDF
1. Click **Open PDF** above. GitHub will show a built-in preview.  
2. To download, click the Download button on the GitHub PDF viewer.  

## How to reproduce locally
1. Download `supply_chain_dataset_clean.xlsx` from this repo.  
2. Open Power BI Desktop.  
3. Get data > Excel, then load the dataset.  
4. Use visuals in `dashboard_screenshots.pdf` to rebuild pages.  
5. Example measures used:
   - `Total Sales = SUM(Sales[SalesAmount])`
   - `Total Units Sold = SUM(Sales[UnitsSold])`
   - `Inventory Turnover Ratio = DIVIDE(SUM(Sales[COGS]), [AverageInventory])`
   - `Days Inventory On Hand = DIVIDE(365, [Inventory Turnover Ratio])`


## Contact
- Name: ASAD KARIM  
- Email: asadkarim474@gmail.com  
- GitHub: https://github.com/<asadkarim1>

