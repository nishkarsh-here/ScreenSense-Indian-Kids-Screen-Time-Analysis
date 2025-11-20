🧩 ScreenSense: Kids’ Screentime Visualization
📘 Overview

This repository contains the work completed during my 3-month Infosys Springboard Internship (2025).
The project, titled ScreenSense: Kids’ Screentime Visualization, analyzes children's screen usage patterns to derive actionable insights for parents, educators, and policymakers. The study uses data analytics and visualization to explore behavioral trends across age, gender, device type, activity, and geography.

🎯 Objective

To uncover meaningful patterns and behavioral insights from kids’ screentime data using data visualization and statistical analysis, thereby promoting awareness of digital health and supporting informed decision-making.

📊 Problem Statement

The increasing exposure of children to digital screens has led to growing concerns about physical and mental health.
This project aims to:

Understand how screen time varies across demographics and devices.

Identify cohorts exceeding safe screen-time limits (as per WHO/APA guidelines).

Highlight health and awareness gaps using visual analytics and dashboards.

🧠 Key Insights

Teenagers using TVs/tablets and late teens using laptops/smartphones exhibit the highest screen time (often 4.5+ hrs/day).

Most “Need Attention” and “Moderate Concern” segments cluster among urban preteens and teens.

Mental health impacts are more common than physical issues, and awareness doesn’t always reduce screen use.

Rural-urban gaps mainly influence device access rather than screen duration.

Outliers with >12 hrs/day usage indicate critical risk groups requiring intervention.

🧩 Dataset

Source: Kaggle – Indian Kids Screentime 2025

Type: CSV
Attributes: Age, Gender, Location (Urban/Rural), Device Type, Activity Category, Duration, Health/Awareness Indicators, etc.

⚙️ Project Workflow
Milestone 1: Data Foundation and Cleaning

Loaded and explored dataset schema, datatypes, and null values.

Handled missing and inconsistent entries.

Created derived columns (Age Bands, Weekday/Weekend flag, Device & Activity shares).

Output: Cleaned Dataset + Preprocessing Summary

Milestone 2: Visual Exploration and Topic Trends

Performed univariate and bivariate analysis using Matplotlib, Seaborn, and Plotly.

Compared screentime across age, gender, and location.

Visualized device mix, activity share, and weekday vs weekend trends.

Milestone 3: Segment & Insight Deep Dives

Identified top risk cohorts and habit clusters via heatmaps and stacked comparisons.

Explored seasonal or term-time variations (where applicable).

Summarized insights for each segment.

Milestone 4: Dashboard & Reporting

Built an interactive Tableau dashboard with tabs for:

Overview

User Segments

Device Patterns

Awareness & Health

Demographics

Time Trends

Policy Recommendations

Integrated interactivity (filters by age, gender, location, and device type).

Compiled findings into a visual report and presentation.

📈 KPIs & Metrics
Category	Metric	Description
Usage	Average Daily Screen Time	Mean daily hours per user
Risk	% Exceeding WHO/APA Limits	Proportion of users above healthy thresholds
Devices	Device Mix Share	Split of screen time by smartphone, laptop, TV, tablet
Time Patterns	Weekday vs Weekend	Comparative usage patterns
Health	Health Impact Ratio	Users reporting mental/physical effects
Awareness	Awareness Distribution	Category split: “Need Attention,” “Moderate Concern,” etc.
Demographics	Urban vs Rural	Device access and usage gaps
Activities	Educational vs Recreational Ratio	Time spent on learning vs entertainment
Outliers	High-Risk Segments	Teens with 11+ hrs/day usage
🧰 Tech Stack

Languages: Python
Libraries: pandas, numpy, matplotlib, seaborn
Dashboard Tools: Tableau, Power BI
Environment: Jupyter Notebook
Documentation: Markdown, PDF Reports, GitHub Repository

🧩 Deliverables

✅ Cleaned and Preprocessed Dataset
✅ Data Analysis Notebooks (Weeks 1–6)
✅ Tableau Dashboard with interactive filters
✅ Final Report and Presentation Slides

🏁 Outcome

The project successfully:

Demonstrated data analytics and visualization skills in a real world context.

Provided insightful trends into kids’ digital habits.

Produced an interactive, stakeholder friendly dashboard summarizing complex behavioral data into actionable takeaways.

Completed under the 2 month Infosys Springboard Internship Program, focusing on practical, industry aligned analytics application.

💭 Internship Experience Reflection

During my 2 month Infosys Springboard Internship, I gained hands on exposure to the end to end analytics pipeline from data preprocessing and visualization to dashboard storytelling.
The experience strengthened my understanding of data driven insights, Python analytics workflows, and the importance of clear visual communication for real world decision making.

📚 References

Infosys Springboard Learning Resources

Kaggle Dataset: Indian Kids Screentime 2025

WHO & APA Screen Time Guidelines

Matplotlib and Seaborn

👤 Author

Nishkarsh Khandelwal
📧 khandelwalnishkarsh302@gmail.com

💻 GitHub- nishkarsh-here
