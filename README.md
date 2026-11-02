# E-commerce Sales Dashboard (Power BI)
Power BI dashboard on e-commerce sales data: Power Query cleaning, calendar table, DAX measures
An interactive Power BI report built on a Kaggle e-commerce dataset of 5,000 orders.

![Dashboard]([images/dashboard.png](https://github.com/deependragupta25/ecommerce-sales-powerbi-dashboard/blob/main/E-commerec_Sales_Data.png)

## What's in the report
- 7 KPI cards and 8 visuals
- Year and month slicers
- Time intelligence: year-over-year comparison and YTD

## Data
Source: [[Kaggle dataset name and link](https://www.kaggle.com/datasets/abbas829/ecommerce-sales-dataset)]. Practice data, so the findings are not business conclusions.

## What I did
1. **Cleaned the data in Power Query.** Fixed mixed date formats where day and month were swapped.
2. **Built a custom calendar table** and related it to the sales table.
3. **Wrote DAX measures** (see `https://github.com/deependragupta25/ecommerce-sales-powerbi-dashboard/blob/main/docsdax_measures.md`): CALCULATE, ALL, SAMEPERIODLASTYEAR, TOTALYTD.
4. **Designed the report** on a single 16:9 page.

## Key insights
- Electronics generated the most revenue (about 36%), followed by Clothing (about 30%).
- Orders were evenly spread across the four regions.
- Average order value about $1,022; average rating 2.97.

## Lessons learned
- Relationship cardinality and filter direction in the data model.
- Why a YTD measure needs a single year in context.

## How to open
Download `https://github.com/deependragupta25/ecommerce-sales-powerbi-dashboard/blob/main/power%20bi%20sales%20project%203.pbix` and open it in Power BI Desktop.
