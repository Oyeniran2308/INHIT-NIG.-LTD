# INHIT-NIG.-LTD
This Project contain sales analysis for Inhit nig Ltd, its shows the performance across state and insight for improvement.
## TABLE OF CONTENT
   - Introduction
   - Datasets
   - Tools Used
   - Method and steps
   - Result/ Business Insight
   - Recommendations and Conclusion
## INTRODUCTION
This project is set to analyse the sales performance for **Inhit. Nig Ltd** 🏢 across the state, region, and also to examine the organisation line of business performance with the highest unit sold and revenue generated.
## Datasets
The Dataset used is a secondary data given by my facilitator 👨 ***(Mr. David)*** to draw business insight for the company.
## Tools Used
**Excel** was used to carry out both cleaning and visualization of this project. The use of Pivot table are used to get the chart which interpret the data according to Pivot fields. 
## Method and Steps
The data in it raw form needs little cleaning and adjustment before analysis can be carried, and the following are the steps taken to achieve the insight carriedout for this project
  
  - Firstly, theirs is a condition to categories the unitsold into three categories *(Low, Medium, High)*. The Unit sold from 1-20 are categories Low, 21 -50 are categories Medium, while above 50 are categories High. This was achieved using the *"IFs Function"* in excel, the function state **"=IFS(N2<=20,"LOW",N2<=50,"Medium",N2>50,"High")"** after which the flashfill was apply to autofill the cells.
  - Secondly, the dataset was highlighted and a spell-check was conducted under Review on the menu bar, the wrong spellings was accepted while some unique spelling which applies to indigenous language (name of store) were not changed.
  - Thirdly, the date column was divided into day, month and year column for me to carry out my analysis on the month with the highest unit sold; so to achieve this, three column was inserted after the date, and they where splited using the TEXT FUNCTION **"=TEXT(D2, "DD")"**, flashfill was thereafter applied to automatically fill the cell.This metthod was repeated for both month with the date format "MM" and year "YYYY"
  - Finally the data is ready to be exported into visualizing charts using the pivot table.
  -  Pivot Table: the dataset was highlighted and then a pivot chat was created under Insert on the menu bar. The necessary field were selected in the pivot field and then transformed into chat. Bar chat, 3D stacked column chart, table, pie chart, slicers ... where used for visualization.
## Result/Business Insight
The following are the insight gotten from the analysis;

  - Total Sales Revenue: **73,031,990,280**
  - Sum of Unit Sold across all state: **786,678**
  - Total Sales: **307,98**
  - Revenue Generated across region: North East generated the highest revenue of **12,489,746,040** across all region while North Central generated the lowest revenue of **4,318,864,800**.
  - Unit Sold according to day category: There are four day category (Local holiday,Observance,Public holidays,Season, Workday) the major sales was carried out on Workdays with a total sales value of **491,391**.
  - Unit sold by each State: sales were carried out in twenty-two state accross the region with Ekiti state having the highest unit sold across the region and Osun having the lowest.
  -  Unit sold per sales category: sales categories under medium has the highest unit sold while the high has the lowest.
  -  Unit sold according base on line of business: Part line of business has the highest sales with a sum of 493,826 unit sold and 62% of the unit sold across the region; while the printer sales has the lovest with a sum of 12,795 and 2% unit sold across the region.
  -  Unit sold per month: June has the highest unit sold across the four line of business, while January has the lowest, also more unit were sold from the second quarter of the year and it flows till the last quarter of the year. 
## Recommendation and Conclusion
Below are some critical recommendation for the mangement overseeing Inhit Nig. Ltd;

  - It was observe that **North East** generated the highest revenue and **North central** generated the lowest but accross all region **Ekiti state** which happens to have the highest unit sold across the region even with seven outlet across the state. The management of the company should see to opening more outlet store in some strategic places across the southwest state, with this southwest has the possibility of generating high revenue across the region.
  - Unit sold according to line of business: The **part business** is doing fine followed by the **service plan** the copier sales and printer sales are really suffering, the management should look into applying different approach and custermer target.
  - Unit sold per month: the management should see to get large stock at the **first quarter** of the year with strong awarness as theirs always high demand starting from the **second quarter** of the year.
