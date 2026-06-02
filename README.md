# Target-Retail-Retention-Analytics
An interactive Power BI Dashboard simulating Target Corporation's customer retention analytics. Features an optimized Star Schema and DAX calculations to analyze churn, evaluate loyalty programs, and optimize retail formats.
Target Retail Customer Retention Analytics Dashboard 🎯📊

The Target Customer Retention Analytics Workspace! This end-to-end Business Intelligence project was completed as the final capstone for my "Data Visualization with Power BI".

This repository contains the interactive data model, DAX calculation schema, and business strategy assets built to help Target Corporation analyze customer attrition, evaluate loyalty programs, and optimize retail formats.

Project Overview & Objectives

In a highly competitive retail space, retaining high-value customers is critical. While Target collects extensive transactional and demographic data, this project was designed to address three key corporate objectives:

Consolidate Data: Map fragments of customer demographics, loyalty metrics, and e-commerce/brick-and-mortar ledger data into a unified, high-performance data model.

Diagnose Churn Factors: Pinpoint exactly where, who, and why customers are churning across regions, socioeconomic groups, and transactional channels.

Formulate Actionable Strategies: Translate data-driven insights into corporate interventions to reduce attrition and maximize Customer Lifetime Value (CLV).
📈 Dashboard Page Walkthrough

The report is divided into four distinct pages, linked together by dynamic, synchronized slicers (Region, Channel, Income Level, and Loyalty Tier):

Page 1: Overview KPIs
Page1.png


Core Baseline: Establishes Target’s baseline Customer Retention Rate (75.50%) and Churn Rate ($24.50%) out of 200 distinct active IDs.

Geographic Drilldown: Highlights that churn peaks in the North region ($29.0\%$) and remains lowest in the Central region (15.\%).

Funnel Flow: Traces the customer journey from baseline acquisition to stable repeat business.

Page 2: Loyalty & Promotion Impact

The Promo Paradox: Reveals that orders without promotions average a higher basket size than orders with promotions (average spend of $411 vs. $398), exposing promotional value leakage.

Points Activity: Analyzes points accumulation vs. redemptions, revealing a major redemption lag in the Elite loyalty tier (73textK earned vs. 56K redeemed) that directly correlates with their high churn.

Page 3: Store/Channel Performance

Format Spend: Tracks format strengths—Supercenters lead order value ($423), while Neighborhood Markets suffer from high format churn (25.7%).

Layout Age Regression: Visualizes a strong positive correlation (r = +0.84) between store opening year and customer retention. Legacy layouts opened pre-2012 average 68%text to  73% retention, while modern smart-layouts built post-2018 reach up to 94%.

Page 4: Segmentation & Customer Lifetime Value (CLV)

High-Value Hotspots: Exposes the Elite North ($638 average CLV) and Premium North ($590 average CLV) segments as Target's most critical customer cohorts.

Recency vs. Value Matrix: Plots CLV against Days Since Last Purchase to flag high-value customers at immediate risk of churning.

🎯Top 3 Strategic Recommendations for Target

Based directly on the analytical findings of the data model, three key strategic actions were formulated for Target's leadership:

Targeted VIP Win-Back Campaigns: Deploy experiential perks (such as free same-day drive-up shipping, white-glove delivery, and early access to seasonal brand collaborations) specifically targeting High-CLV North region Elite/Premium members who haven't shopped in 60+ days.

Modernize Legacy Store Layouts: Reallocate capital expenditure away from building new physical locations and instead remodel underperforming pre-2012 legacy layouts to replicate modern high-retention formats (adding dedicated order pickup areas and drive-up bays).

Incentivize Loyalty Point Redemption: Lower point-redemption friction for high-tier members by introducing checkout cash-back point conversions, points-to-charity donations, or lifestyle partner rewards (e.g., streaming memberships) to combat reward fatigue.
