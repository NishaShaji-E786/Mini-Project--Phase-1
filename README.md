# Mini-Project--Phase-1
Project Title: Zomato Restaurant Market Analysis 
Tools Used: Microsoft Excel (Phase 1) & Power BI (Phase 2)
Business Objective: Analyse restaurant distribution, pricing tiers, cuisine popularity, and service availability (online delivery and table booking) across cities to identify key drivers of higher customer ratings.
Phase 1: Microsoft Excel
A) Data Cleaning & Preparation
Formatting & Standardization: Standardized column headers (applied text wrap, bold formatting, and header fill) and verified data types across numeric and text fields.
Duplicate & Null Handling:
Checked for duplicate records via Data → Remove Duplicates (0 duplicates found).
Identified blank values in the Cuisines column and replaced them with "Unknown" using Find & Replace (Ctrl + H).
Text & Currency Cleaning: Fixed corrupted encoding in the Currency column (e.g., replacing Pounds(??) with Pounds(£)) using Excel text functions (SUBSTITUTE, LEFT, and MID).
Data Enrichment (Country Mapping): Created a reference sheet mapping unique currency values to their respective countries, then used VLOOKUP to add a Country column to the main dataset.
B) Exploratory Analysis (PivotTables & PivotCharts)
Top 10 Cities by Restaurant Supply & Engagement: Built a PivotTable with City in Rows and Count of Restaurant ID / Sum of Votes in Values. Applied a Top 10 Value Filter and visualized the results using a Clustered Bar Chart.
Rating Distribution Across the Market: Built a PivotTable grouping Rating text against Count of Restaurant ID, visualized with a Bar/Pie Chart to show the overall spread of customer sentiment.
Average Rating Across Price Ranges: Analysed Price range (1–4) against Average of Aggregate rating using a Line Chart to evaluate whether higher-priced restaurants receive better ratings. (Note: Currency-specific cost averages were isolated by country to avoid multi-currency distortion).
Table Booking Impact: Compared Has Table booking (Yes/No) against Average of Aggregate rating and Count of Restaurant ID using a Clustered Column Chart.
Online Delivery Impact: Analysed the split of restaurants offering online delivery (Has Online delivery) and its correlation with average customer ratings using a Doughnut 
