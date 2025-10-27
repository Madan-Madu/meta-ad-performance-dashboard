# meta-ad-performance-dashboard

📌 Project Overview
This project analyzes paid advertising performance across Meta platforms (Facebook & Instagram). The dashboard helps the marketing team track campaign reach, user engagement, conversions, and budget utilization to improve audience targeting and maximize the return on ad spend.

🎯 Business Goal

✔ Identify top-performing platforms and ad types
✔ Understand user demographics and engagement behavior
✔ Optimize campaign budget allocation
✔ Improve click-through and conversion performance

🧩 Data Source & Modeling

The dataset contains four relational tables, modeled in a Star Schema:

Table	Description

ad_events	Fact table containing impressions, clicks, purchases
ads	Ad details – type, platform, targeting
campaigns	Budget & strategy details
users	Demographics & interests

🔗 Relationships:

ad_events → ads → campaigns
ad_events → users

📌 Data transformations:

Data type corrections
Created Calendar Table for time intelligence
Built DAX measures & dynamic parameters

📈 Key Metrics & Calculations

Impressions: 10.3K+
Clicks: 1.2K
Engagements: 1.4K
CTR: 11.54%
Engagement Rate: 13.53%
Conversion Rate: 5.98%
Total Budget: $2.5M
Avg Budget / Campaign: $50.7K
➡ Measures created using DAX (CTR, Engagement Rate, Purchase Rate, Conversion Rate)

📊 Dashboard Features

✔ KPI summary cards
✔ Dynamic metric selection
✔ Platform & campaign filters
✔ Audience insights (gender, age, country)
✔ Weekly & hourly performance trends
✔ Creative-type comparison via matrix
✔ Calendar heatmap for monthly engagement

🔍 Insights & Business Impact

✅ Age group 25–34 drives highest engagement
✅ 13.5% engagement rate — strong user interaction
✅ 5.9% conversion shows purchase funnel is effective
✅ Country-wise performance highlights expansion opportunities
✅ Certain ad types outperform others → budget shift recommended

🛠 Tools & Skills Used

Power BI
DAX & Data Modeling
Data Visualization
Marketing & Funnel Analytics
Business Requirement Alignment

✅ Conclusion

This dashboard enables data-driven decisions by identifying the most impactful campaigns, audience groups, and ad formats — helping marketers improve ROI through smarter budget allocation and targeted optimization.
