# House Sales Dashboard

King County house sales analytics dashboard built with Power BI — analyzing 21,000+ residential property transactions to identify key price drivers.

## Overview
This project analyzes residential real estate transactions in King County, USA (2014–2015) to understand what drives home prices — property grade, condition, square footage, waterfront access, and seasonal timing.

## Business Questions
- How does property grade relate to price?
- Does square footage predict price reliably?
- What premium do waterfront properties command?
- Are there seasonal patterns in home prices?

## Tools & Skills
- **Power BI**: DAX measures, interactive filtering (Condition, Year/Quarter slicers)
- **Power Query**: Data cleaning and transformation
- **Data Visualization**: Scatter plot analysis, distribution charts, trend analysis

## Dashboard Preview
![House Sales Dashboard](House%20Sales%20dashboard.png)

## Key Insights
- Sqft Living and Price show a strong positive correlation, though the relationship flattens above 6K sqft, suggesting diminishing returns on size alone
- Median price rises sharply with grade — from near $0 at grade 1 to ~$3M at grade 13 — making grade the strongest valuation proxy in this dataset
- Waterfront properties carry a significant price premium, accounting for 75.68% of combined median price value despite being the minority segment
- 200K–600K dominates transaction volume, with the market concentrated in the mid-tier segment
- Price shows a seasonal dip from September 2014 to January 2015, recovering toward a peak in March 2015

## Data Dictionary Notes
- **Condition**: an index from 1 to 5 rating the overall condition of the property
- **Grade**: an index from 1 to 13, where 1–3 indicates below-average construction/design, 7 is average, and 11–13 reflects high-quality construction and design
- **Waterfront**: binary indicator (0/1) for whether the property overlooks the waterfront

## Files
- `House Sales Dashboard.pbix` — Power BI dashboard file
- `House Sales Dashboard.pdf` — Full dashboard export
