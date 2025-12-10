# PowerBI-Portfolio
# About this project
For the Maven Sales Challenge, I played the role of a BI Developer for MavenTech, a company that specializes in selling computer hardware to large businesses. They've been using a new CRM system to track their sales opportunities but have no visibility of the data outside of the platform.

I created an interactive Power BI dashboard to enable sales managers to track their team's quarterly performance.

The Dataset
The dataset contained records exported from MavenTech's CRM from October 2016 to December 2017. It held details of opportunities with associated information such as product, account, and whether the sale was won or lost.

Key Assumptions
When creating an interactive dashboard, I always like to chat with the users to make sure I truly understand the intended purpose and the questions they seek to answer with the dashboard. In the absence of being able to chat with the sales managers, I made the following key assumptions which I used to guide my dashboard design.

The main goal for sales managers is viewing the current state of play for their team, and obtaining actionable information. The key questions they want to answer are:
How is my team (as a whole and individual team members) tracking against our key KPIs?
Are there team members who require extra support in certain areas?
Where should I focus my efforts for the rest of the quarter to improve performance?
Is my team performing above average compared to the rest of the business?
Their main KPI is the dollar value of sales made, however related metrics such as number of sales, conversion %, and average sales value are also important and help to understand their total sales value.
They may also at times want to dive deeper and look at their team's performance over the year or in comparison to the other sales teams.
As the dashboard is intended for the sales managers, the most important view to them is to see their own team, rather than an Exec dashboard with higher level team comparisons. They may however like to look at other sales teams in more detail and there is no requirement for row level security to prevent them access to other team data.
It is assumed that the "Current quarter" is Q4 2017, which is the latest time period recorded in the dataset, however in reality this dashboard would continuously update over time as new data is added.
The Dashboard
As the dashboard is interactive, I also focused on making it user friendly for audiences who may not use Power BI every day. If the sales managers don't feel comfortable using the dashboard, there's no value to be gained. For this reason, I added a help page covering basic dashboard functionality and defining how the key metrics were calculated. This ensures sales managers canconfidently navigate the dashboard, and clearly interpret the information they are seeing and answer their key questions.
