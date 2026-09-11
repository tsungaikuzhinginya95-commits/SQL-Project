# SQL-Project
Sales Performance, Customer Value &amp; Product Profitability
Here is a clean README summary from your `SQL_report.pdf`:

### AdventureWorksLT2025 Sales Analysis - README

**Overview**
Comprehensive SQL analysis of AdventureWorksLT2025 SalesLT database to evaluate revenue performance, product profitability, and customer value. Dataset: 32 orders / 32 customers / 142 products / 26 categories / $956,303.59 revenue - single snapshot June 2008.

**5 Key Analyses**

**1. Monthly Sales Trend:** Only 1 period [June 2008, $956,303.59] exists. MoM growth = NULL. No trend can be calculated - requires multi-month history.

**2. Customer LTV Segmentation:** 32 customers split into 4 quartiles via `NTILE(4)`. Q1 = 8 VIPs $63,686 - $119,960, led by Terry Eminhizer $119,960.82. All LTV = first order value due to single-order behavior. $17k drop Q1 to Q2.

**3. Product Category Profitability:** Revenue >80% from 3 bike categories - Touring Bikes $220,655 [252 units], Road Bikes $183,130 [222 units], Mountain Bikes $170,825 [209 units]. Negative margin on top drivers: Road Bikes -10.17% [-$18,616], Touring Bikes -4.15% [-$9,147]. Profit from accessories: Shorts 36.54%, Helmets 35.71%, Vests 33.32%. Jerseys high volume [230 units] but low value $30/unit vs Bikes $875/unit.

**4. Top Products & Cumulative Revenue:** Top 1 product Touring-1000 Blue 60 = $37,191.49 [5.25%], Top 5 = 24.0%, Top 11 = 40.97%. 25-30% SKUs drive 80% revenue - Pareto on premium bikes.

**5. Customer Retention:** 100% One-Time Buyers = 100% revenue. 0% Repeat = $0 revenue. Critical retention risk.

**Conclusion:** High-value single-purchase business with concentration risk on 11 products and 8 customers, selling top bikes below StandardCost while low-volume accessories sustain margin.

**Copy for README.md:**
> This repo contains SQL analysis of AdventureWorksLT2025 covering monthly trends, LTV segmentation, category profitability, product concentration, and retention. Key finding: 32 customers, 100% one-time, $956k revenue in 1 month, with top 3 bike categories driving 80% revenue at negative margin.
