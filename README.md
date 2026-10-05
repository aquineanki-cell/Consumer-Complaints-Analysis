# Consumer Complaints Analytics Dashboard

📌 Project Overview

This project is an end-to-end data analytics dashboard built in Power BI to analyze and track consumer complaints across various financial products. The goal of this analysis is to provide actionable visibility into a dataset of over 62,000 customer disputes, identifying product friction points, geographical hotspots, and operational bottlenecks in the dispute resolution process.

This was developed as my first comprehensive data analytics portfolio project, focusing on data cleaning, DAX measure creation, interactive visualization, and professional UI/UX dashboard design.

📊 Dashboard Pages & Features

The dashboard is structured into four interactive pages, navigating through a custom-built carousel menu:

Complaints Overview: High-level KPIs tracking total volume (62.5K), average resolution time (1.22 days), and timely response rates (93.77%). Features seasonal trend analysis and product breakdowns.

Geographical Analysis: A custom dark-themed interactive map highlighting complaint volumes and operational efficiency across the United States. Identifies California, Florida, and Texas as peak volume states.

Resolution & Root Cause Analysis: Deep dive into how complaints are resolved (e.g., Closed with explanation vs. Closed with monetary relief) and the primary issues driving customer dissatisfaction (e.g., "Managing an account").

Complaint Details & Drill-Down: A granular, row-by-row matrix for operational teams to export data, featuring hierarchical slicers and a Power BI AI Key Influencers visual to dynamically identify exactly what factors cause a delayed response.

🛠️ Tools & Technologies Used

Microsoft Power BI: Data visualization, data modeling, and interactive dashboarding.

DAX (Data Analysis Expressions): Created custom measures, including an Average Processing Lag metric to calculate the exact day difference between submission and receipt.

Power Query: Data cleaning, type formatting, and handling missing/null values.

Custom UI/UX Design: Designed premium 16:9 dark-theme backgrounds, custom glowing network graphics, and adapted horizontal tile slicers to mimic web application navigation.

💡 Key Business Insights

Product Friction: The Checking or savings account product drives the highest volume of complaints (~25K) and results in the highest rate of monetary relief payouts.

Efficiency Bottlenecks: Despite a low volume, Student Loans and Debt Collection complaints trigger the highest processing lags (up to 2.13 days).

Channel Performance: Web submissions dominate the pipeline (72.6% of all complaints) and boast a highly efficient 0.68-day processing lag.

📂 Repository Contents

Consumer_Complaints_Analytics.pbix - The interactive Power BI dashboard file.

Consumer_Complaints.xlsx - The raw dataset used for this analysis.

Consumer_Complaints_Insights.pdf - A generated executive summary of the findings.

Background_Assets/ - Folder containing the custom 1920x1080 HD background graphics used in the dashboard UI.

🚀 How to Run

Download the .pbix file from this repository.

Open the file using Power BI Desktop.

Use the green navigation carousel on the left side of the screen to click through the different analytical views.
