📦 Superstore Returns Deep Dive — Root Cause Analysis
Tool: Tableau | Program: TripleTen Business Analyst Program (Sprint 5)
🔗 [View Live Dashboard on Tableau Public](https://public.tableau.com/views/MargaritaBegazoSprint5Project/FinalInsights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

📌 Business Problem
A retail superstore was experiencing a persistently high return rate across multiple regions and product categories. Rather than accepting returns as a cost of business, the goal of this analysis was to identify the root causes — examining returns by customer behavior, product category, time of year, geographic location, and shipping method — and recommend actionable operational changes.

📁 Dashboard Views
This project contains six analytical views presented as a cohesive Tableau story:

Summary of Analysis — key takeaways and final recommendations
Total Sales vs. Total Return — correlation between sales volume and return volume
Return Rate by Category — average return rates across Furniture, Office Supplies, and Technology
Return Rate by Customer — identifying high-frequency returners (customers with 2+ orders)
Return Rate by Month/Year — seasonal and year-over-year return trends
Return Rate by Location — geographic breakdown by state, region, and shipping method


🔍 Key Findings
Sales & Returns Correlation

As sales volume increased, return volume increased proportionally
This confirmed that returns were not isolated incidents but a systemic issue requiring operational investigation

Category Analysis

Return rates across Furniture (25%), Office Supplies (25%), and Technology (27%) were nearly equal
The similarity across categories indicated that product type was not the primary driver of returns — pointing instead toward fulfillment and delivery factors

Customer Behavior

Identified a segment of high-frequency returners with average return rates above 80–100%
Analysis filtered to customers with at least two orders to ensure meaningful return rate calculations

Seasonal Trends

Returns spiked in August (back-to-school season) and again in December (holiday season)
A notable increase in 2021 was attributed to schools shifting online, reducing demand for physical supplies — resulting in higher return rates on previously ordered items

Geographic & Shipping Analysis

The West Coast had the highest return rate, with some states reaching 45–57%
Same Day delivery in the West region had the highest return rate of any shipping method and region combination
Hypothesis: Same Day delivery on the West Coast may result in items being shipped before quality checks or customer confirmations are complete


💡 Recommendations

Contact warehouse and delivery partners to investigate whether fulfillment or handling issues are contributing to the high West Coast return rate
Suspend or limit Same Day delivery on the West Coast as an immediate cost-saving measure while the root cause is investigated
Monitor high-frequency returners and consider implementing account-level return thresholds
Prepare for seasonal return spikes in August and December with adjusted inventory and staffing plans


🛠️ Skills Demonstrated

Multi-view Tableau story design
Root cause analysis across multiple dimensions (category, customer, time, location)
Geographic mapping and regional comparison
Trend analysis over time (monthly and yearly)
Translating data findings into specific, actionable business recommendations


📂 Data Source
Superstore dataset (provided by TripleTen) — a fictional retail dataset commonly used for business analytics training.
