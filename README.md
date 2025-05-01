# Marketing_Campaign
Exploratory Data Analysis of a 200K-entry marketing campaign dataset, uncovering trends in ROI, CTR, CPC, and conversion rates across channels, cities, and demographics. Includes data cleaning, metric engineering, visual insights, and actionable marketing recommendations using Python.
 Objectives
Clean and structure raw marketing data for analysis

Engineer key performance metrics: CTR, CPC, ROI

Visualize campaign effectiveness across channels, cities, and demographics

Extract insights to improve ROI, conversion rates, and customer targeting

 Dataset Overview
Records: 200,005

Fields include:

Campaign Type (Email, Display, Influencer)

Channel Used (YouTube, Google Ads, Instagram)

Target Demographics (age, gender)

City (e.g., NY, LA, Miami)

KPIs: Clicks, Impressions, ROI, Conversion Rate

 Data Processing
Converted dates to datetime objects for time-series analysis

Removed missing/infinite values from derived metrics

Created new fields:

CTR = Clicks / Impressions

CPC = Cost / Clicks

Detected and flagged outliers in performance indicators

 Key Results & Visualizations
 ROI by Channel: YouTube outperforms others in average ROI

 CTR vs. Conversion Rate: Moderate correlation, highlighting content quality gaps

 Monthly Click Trends: Q2 shows peak user engagement

 Heatmap by City & Campaign Type: Influencer marketing excels in lifestyle-driven cities like LA & Miami

 Strategic Insights
Video content (YouTube) drives superior ROI

Influencer campaigns thrive in urban, lifestyle-centric regions

Q2 is ideal for major campaign deployment

High CTR must be backed by conversion-optimized landing pages

 Recommendations
Boost investment in YouTube and Influencer strategies

Align the campaign calendar with Q2 behavioral trends

Improve UX and messaging for high-CTR but low-conversion campaigns

Refine targeting for Men 25–34 and Women 35–44 segments

Deliverables
File	Description

Marketing_Campaign_EDA_Report.pdf:	Full analytical report with visuals

Eda_campaign_analysis.ipynb:	Jupyter Notebook with complete code
