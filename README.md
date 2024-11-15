# Power BI Project: Unicorn Startup Companies Dashboard

### Dashboard Link: https://app.powerbi.com/groups/8caac2ac-f47d-439e-9627-beaef37655ed/reports/e3753e84-b644-43e0-a312-6ae391be4a88/5383e0a346fb06868ae1?experience=power-bi

## Overview
This project analyzes a dataset of unicorn startup companies, sourced from Kaggle. The dashboard provides insights into the valuation, distribution, and growth trends of unicorn startups worldwide. The project includes data cleaning, transformation, modeling, and the creation of a dynamic and interactive Power BI report.

## Problem Statement
This dashboard provides valuable insights into the distribution, valuation, and growth trends of unicorn startup companies globally. It helps stakeholders identify key industries, regions, and trends in startup ecosystems. By analyzing the data, decision-makers can recognize top-performing sectors, geographical hotspots for unicorns, and the overall growth trajectory of the startup landscape.

## Steps Followed
- Step 1: The dataset was sourced from Kaggle: https://www.kaggle.com/datasets/rajkumarpandey02/list-of-unicorn-startup-companies

- Step 2: Data cleaning was performed in Excel:
    - Functions and filters were applied to eliminate inconsistencies.
    - Null values were identified and replaced with "Not Available."
    - Split, extract, and find-replace functions were utilized for better structuring.

- Step 3: The cleaned dataset was imported into Power BI using the Get Data function.

- Step 4: Data transformation steps in Power BI:
    - Changed data types to appropriate formats.
    - Filled null values with "Not Available."
    - Applied advanced transformation techniques like split and extract to refine data.

- Step 5: A calculated column was created using DAX to calculate the age of each unicorn:
    - DAX
    - Copy code
    - Unicorn Age = YEAR(TODAY()) - [Year Founded]

- Step 6: Measures were created to summarize key metrics:
    - Global Valuation: Total valuation of all unicorns.
    - Total Companies: Count of unicorn companies.

- Step 7: Visualization creation:
    - A Card to display the Global Valuation.
    - A Map visual to highlight countries with unicorn presence.
    - A Bar Chart to rank countries by the number of unicorns.
    - A Pie Chart to show industry-wise valuation distribution.
    - A Line & Clustered Column Chart to display unicorn growth trends over the years.
    - A Matrix Table summarizing unicorn count and valuation by startup age bins (0–12  years, bin size of 2).

- Step 8: Slicers and interactivity:
    - Slicers for Country and Industry were added to filter data dynamically.
    - A "Clear All Slicers" button was created to reset slicer selections.

- Step 9: Bookmarks:
    - Education Industry in India and Finance Related Startups in North America bookmarks were created for quick navigation.

## Key Insights

### Global Insights
(1) **Global Valuation**: Total valuation of unicorn companies.

(2) **Top Industries**: Industries with the highest number of unicorns and valuation.

(3) **Country Trends**: Top countries in terms of unicorn count and their respective valuations.
### Growth Analysis
- Unicorn growth trends over the years, showcasing the startup ecosystem's expansion globally.
### Industry Insights
- Industry-wise breakdown of unicorn valuation, helping to identify leading sectors.
### Startup Age Analysis
- The matrix table provided insights into the number of unicorns in different age bins, showcasing the maturity of companies in the ecosystem.

**Report Snapshots**
#### Dashboard Overview (Power BI Desktop)

#### Published Dashboard (Power BI Service)

### Technical Details
- **Software Used**: Excel, Power BI.
- **Techniques Applied**:
    - Advanced Excel functions for data cleaning.
    - Power BI transformations for data preparation.
    - DAX calculations for creating metrics and measures.
    - Interactive visuals for better storytelling and insights.
