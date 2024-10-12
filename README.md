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


