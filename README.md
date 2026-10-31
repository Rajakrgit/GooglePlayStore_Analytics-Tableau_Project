# GooglePlayStore_Analytics-Tableau_Project
# 1. Project Overview

The Google Play Store Analytics project explores mobile application performance using app-level information and customer reviews. The Tableau workbook brings together three dashboard views:

• Google Play Store Overview – overall app-market KPIs, app categories, installs, ratings and free-versus-paid distribution.

• App Performance Dashboard – relationships between app size, ratings, reviews, installs and content ratings.

• Review Sentiment Dashboard – review sentiment distribution, sentiment polarity and apps receiving negative reviews.

The goal is to turn app-market and customer-review data into useful information for product managers, app developers and marketing teams. The project brief describes a technology company that wants to improve app development strategies, user experience, downloads and revenue opportunities.

# 2. Business Requirements
• Measure average rating, total installs and review volume.

• Identify popular app categories and high-install categories.

• Compare free and paid apps.

• Explore app size, price, ratings and installs.

• Analyse positive, negative and neutral review sentiment.

• Present findings and recommendations in interactive dashboards.

# 3. Tools and technologies
• Tableau Desktop: data visualisation and dashboard development.

• Tableau Calculated Fields: convert installs, price and app size into numeric measures; create rating and install groups.

• Google Play Store app dataset: app category, rating, reviews, installs, size, type and price.

• User reviews dataset: review text, sentiment and polarity.

• TWBX: packaged Tableau workbook.

# 4. Challenges faced
• Missing sentiment: Null and nan values need investigation.

• Data conversion: installs, price and size contain text, symbols or units and must be converted into numeric values.

• Invalid rating result: the content-rating chart shows 19.00 for Null, although app ratings should be on a 0–5 scale. Validate the source rows and aggregation.

• Different data granularity: one app may have many review rows. Avoid duplicating app-level installs or app counts when combining tables.

• Review volume bias: compare negative-review counts with total reviews or negative-review percentage.

# 5. Key insights from the dashboard
• Total apps:	9,660

• Total installs:	167,634,334,487

• Average rating:	4.19

• Free / Paid apps:	8,904 / 756

• Largest app category by count: FAMILY – 1,909

• Leading install categories shown:	GAME and COMMUNICATION

# 6. Review sentiment findings
• Null:	9,309

• nan: 1,405

• Negative:	1,131

• Neutral: 1,041

• Positive:	1,216

# 7. Business recommendations
• Investigate recurring negative-review themes and prioritise fixes.

• Compare app counts and install volumes to identify high-demand categories.

• Compare free and paid apps by category, ratings and review volume.

• Optimise app size where it affects performance or download experience; do not assume size alone determines ratings.

• Add negative-review percentage and total review volume to the sentiment dashboard.

• Add time trends, clear filters, full-name tooltips and a data-quality page.

• Validate missing sentiment values and the invalid Null rating before publishing.
