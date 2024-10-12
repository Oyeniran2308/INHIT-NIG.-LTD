# INHIT-NIG.-LTD
This Project contain sales analysis for Inhit nig Ltd, its shows the performance across state and insight for improvement.
## TABLE OF CONTENT
### [Introduction](introduction)
### [Datasets](datasets)
### [Tools Used](tools-used)
### [Method and steps](method-and-steps)
### [Result](result)
### [Business Insight](business-insight)
### [Conclusion](conclusion)
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
## Result
The following are the insight gotten from the analysis;

  - Total Sales Revenue: **73,031,990,280**
  - Sum of Unit Sold across all state: **786,678**
  - Total Sales: **307,98**
  - **Revenue Generated across region:** The data reveals significant regional differences in revenue generation. Notably, the North East emerged as the top-performing region, generating a remarkable ₦12,489,746,040, surpassing all other regions. In contrast, the North Central region recorded the lowest revenue at ₦4,318,864,800, which is approximately 65% less than the North East's revenue.
  - **Unit Sold according to day category:** Analyzing the data across different day categories (Local Holiday, Observance, Public Holidays, Season, and Workday), it's evident that Workdays play a critical role in driving sales. A total sales value of ₦491,391 was generated on Workdays, significantly outperforming other day categories.
  - Unit sold by each State: sales were carried out in twenty-two state accross the region with Ekiti state having the highest unit sold across the region and Osun having the lowest.
  -   Analyzing unit sales across different categories reveals that the Medium sales category recorded the highest volume of units sold, indicating robust demand in this segment. On the other hand, the High sales category reported the lowest number of units sold.
  -   The contrast between medium and high on sales category, suggests potential differences in customer preferences this may be influenced as many client has choosed Part and Service plan business line decided to go 
  -  The sales performance across different lines of business reveals significant trends and areas of focus for future growth.
**Parts Line of Business** stands out as the top performer, generating 493,826 units sold, which accounts for a remarkable 62% of total units sold across all regions. This dominance suggests that the demand for parts is a major driver of the company’s overall sales, indicating a strong market presence and customer reliance on parts for maintenance or upgrades.
On the other hand, **Printers Line of Business** trails behind with only 12,795 units sold, representing a mere 2% of total units sold. This indicates a potential area for further investigation—whether it's due to lower demand, market saturation, or possibly an untapped opportunity for growth.
  -  **Monthly Sales Trend Analysis:** The data reveals a notable seasonal variation in units sold across the four lines of business. June stands out with the highest sales volume, indicating strong mid-year demand. In contrast, January records the lowest sales, which may be influenced by post-holiday slowdowns or a cyclical dip in consumer activity. A significant uptick in units sold begins in the second quarter, with consistent growth through to the end of the year, suggesting that demand builds as the year progresses, potentially driven by factors like new product launches, marketing campaigns, or seasonal buying patterns. This trend could present opportunities for targeted sales strategies during peak months to maximize revenue.

![INHIT NIG  LTD](https://github.com/user-attachments/assets/e87968dd-9123-45b2-9c03-45559d586510)

## Business Insights
- considering North central having the lovwest revenue generated across all region,the data shows that sales occured in two state only (Federal Capital territory and Kogi) compared to other region, this has a strong negative influence on the outcome of the revenue generated  for that region, hence, management should see to establishing strong industrial presence, better infrastructure, and effective market strategies at this region.
- The Lines chart containing Unit sold according to day category suggests that businesses should focus on maximizing their efforts during these peak days to capture the largest share of the market. Additionally, exploring strategies to boost sales during non-workdays, such as public holidays or seasonal events, could present opportunities to tap into untapped revenue potential and smooth out revenue fluctuations across different day types.
- Parts are the backbone of the business, driving a significant portion of sales, suggesting that focusing on this line may continue to yield high returns. Exploring ways to optimize or expand this product offering could solidify its market position.
- Printer sales, however, are significantly lagging, prompting a need to investigate the root causes. Whether it's market competitiveness, product positioning, or customer perception, this segment presents an opportunity for innovation, marketing strategy adjustments, or product diversification.
- The disparity between the highest and lowest-selling lines emphasizes the importance of understanding customer behavior and adjusting strategies to optimize underperforming areas while continuing to support the strong performers.
- **June has the highest units sold across all four lines of business:** If June consistently shows higher sales, it's an opportunity to plan targeted marketing campaigns or promotions leading up to this month to maximize profits. Ensure sufficient stock is available in June to meet increased demand, preventing stockouts and lost sales.
- **January has the lowest units sold:** January may suffer from post-holiday consumer spending fatigue, or it could coincide with economic slowdowns after the festive season. Encourage purchasing through special New Year sales, discounts, or bundles, especially for leftover inventory from the holiday season.

## Conclusion
Inhit Nig. Ltd will be strong on it four line of business when they pay attention to somethings understanding their market, understanding the client and the peculiarity of each state and region; the line business should be introduce to the peculiarity of the customers environment.
