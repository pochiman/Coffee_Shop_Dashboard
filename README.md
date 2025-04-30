# Coffee Shop Dashboard

## The Situation
You've recently become a franchise owner at Maven Roasters, a coffee shop chain with three locations in New York City.

## The Assignment
To better understand purchase behavior and streamline operations, you've collected transactional data from Jan-Jun 2023.
Your goal is to transform the data into a dynamic dashboard that franchise owners can use to identify patterns, trends and opportunities for the business.

## The Objectives
1. Profile and prepare the raw data for analysis
2. Explore the data with Excel PivotTables
3. Build a dynamic dashboard to visualize patterns and trends

## The Data Set

#### Coffee Shop Sales
Transaction records for Maven Roasters, a fictitious coffee shop operating out of three NYC locations. Dataset includes the transaction date, timestamp and location, along with product-level details.

#### Recommended Analysis
1. How have Maven Roasters sales trended over time?
2. Which days of the week tend to be busiest, and why do you think that's the case?
3. Which products are sold most and least often? Which drive the most revenue for the business?

#### Objective 1: Prepare the data for analysis
Your first objective is to explore the coffee shop dataset, conduct some basic data QA and profiling, and add calculated date and time fields to prepare the data for analysis.

* Take a moment to familiarize yourself with the data. How many transactions were recorded, over what period of time? What products and product categories were sold?
* Add a new column to calculate Revenue (price * quantity)
* Add new columns to calculate Month and Day of Week based on the transaction date (BONUS: display them as text (ie “Jan”, “Feb”, “Sun”, “Mon”), instead of numerical values)
* Add a new column to extract Hour from the transaction time

#### Objective 2: Explore the data with Pivot Tables
Your second objective is to slice and dice the coffee shop data with Excel PivotTables, and create views to analyze time series and product-level trends.

* Insert a PivotTable on a new tab to show revenue by month
* Add two more PivotTables (on the same sheet) to show the number of transactions by day of week and by hour of day
* Add a PivotTable (on the same sheet) to show the number of transactions by product category, sorted descending by transactions
* Add a PivotTable (on the same sheet) to show the number of transactions and revenue by product type, sorted descending and filtered to the Top 15 (by transactions)

#### Objective 3: Build a dynamic dashboard
Your final objective is to visualize the data with Pivot Charts, design an interactive dashboard, and identify insights and recommendations for the coffee shop.

* Add Pivot Charts to show revenue by month as a line chart, transactions by day of week and hour of day as column charts, and transactions by product category as a bar chart
* Assemble the charts into a rough dashboard layout, and include space for the PivotTable showing Top 15 product types
* Add a slicer for store location, and connect it to all of the PivotTables on the sheet
* Adjust formatting, alignment and polish to finalize the dashboard (TIP: hide the raw PivotTables and remove the worksheet gridlines)
* Do you notice any interesting patterns or trends? What recommendations might you offer to improve Maven Roasters operations?

#### [Project Link]()