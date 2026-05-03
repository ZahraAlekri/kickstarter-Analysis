Kickstarter Project Analysis
Problem Statement
Many creators have great ideas but struggle to get their projects funded on Kickstarter. Without data‑driven insight, it’s hard to know if a goal is too high, a category is too competitive, or the timing is off. This project analyzes Kickstarter campaign data to uncover the factors that most influence success and to help future creators plan smarter, more effective campaigns.

Executive Summary
Kickstarter is one of the largest crowdfunding platforms, connecting creators with backers who want to support innovative ideas. In this analysis, we explored a dataset of campaigns to understand what separates successful projects from those that fail.

We began by cleaning and formatting the data (removing unrealistic goals and incomplete records) and engineering new variables such as campaign duration, success ratio, and launch timing. Exploratory Data Analysis was then used to identify key success drivers.

Key Findings

Smaller, more realistic funding goals greatly improve success rates.
The number of backers strongly correlates with pledged amount — success depends on building a large community, not a few high‑value donors.
Campaigns lasting around 30 days perform best; longer campaigns tend to lose momentum.
Launch timing matters: March, April, and October, especially Tuesday afternoons, show the highest success rates.
Creative categories (Dance, Theater, Comics) consistently outperform technical ones (Technology, Journalism).
Projects based in the US and UK have higher odds of success due to larger active backer communities.
These insights show that crowdfunding success is far from random — it depends on goal setting, timing, community engagement, and smart category choices.


Data and Source
The Kickstarter dataset used in this project was provided through the course dataset repository. It consists of public campaign information including project goals, pledged amounts, backers, categories, and time‑related records.
All monetary values are standardized in USD for consistency.

The cleaned dataset excludes incomplete or open campaigns and retains only finalized projects labeled “Successful” or “Failed.”

Data Dictionary
The table below lists the columns included in the cleaned dataset used for analysis.

Field	Description
Category	Main project category (e.g., Technology, Art, Film)
Subcategory	More specific classification of the project within a main category
Country	Country where the project was launched
Launched	Date and time the project was launched
Deadline	Date and time the project ended
Goal	Funding goal set by the creator (USD)
Pledged	Total amount pledged by backers (USD)
Backers	Total number of individuals who backed the project
State	Outcome of the campaign — “Successful” or “Failed”
Launch_Year	Year the project was launched
Launch_Month	Month the project was launched (1–12)
Launch_Day	Day of the month the project was launched
Launch_Hour	Hour of launch (0–23)
Project_Duration	Campaign length in days (Deadline − Launched)
Pledged_Ratio	Pledged ÷ Goal — shows how close a project came to its target
Summary of Analysis
Funding Goals: Projects with smaller goals have a much higher success rate.
Community Impact: More backers mean more funding; community size is the strongest success driver.
Campaign Length: 30‑day campaigns outperform shorter or longer ones.
Timing: March, April, and October are the best months to launch; Tuesday afternoons see the highest engagement.
Category Insights: Creative and niche categories perform best; Technology and Journalism underperform.
Geography: Projects from the US and UK lead both in volume and success rate.
Recommendations
Set achievable goals: Break larger projects into smaller funding phases to increase success odds.
Build your audience early: Community engagement before launch has a direct impact on pledge amounts.
Launch smart: Start campaigns on a Tuesday afternoon in March, April, or October when backer activity peaks.
Keep campaigns short: Stick to about 30 days to maintain excitement and urgency.
Choose your category wisely: If your idea fits multiple themes, lean toward a creative or niche classification.
Track early traction: Strong first‑week momentum predicts overall success — if growth is slow, reconsider the strategy rather than extending the campaign.
Conclusion
Success on Kickstarter is driven by preparation, not luck. By analyzing thousands of campaigns, we found that well‑timed, community‑backed projects with realistic goals consistently outperform the rest. Applying these data‑based strategies can help creators design campaigns that stand out and achieve their funding targets.

Areas for Further Research
Examine text features like project descriptions or titles to see how language impacts success.
Explore the effect of location beyond country (e.g., city or region).
Analyze changes in success factors over time as Kickstarter evolves.
Sources
Kickstarter dataset provided by course materials

kickstarter.com

hatchwise.com