Bellabeat Case Study 

How Can a Wellness Company Play It Smart?

A data analytics case study exploring Fitbit smart-device activity and sleep data to identify consumer behavior trends and develop data-driven marketing recommendations for Bellabeat.

Business Objective

The objective of this project is to analyze smart-device usage data to understand consumer activity and sleep behavior and determine how these insights could help Bellabeat improve its marketing strategy and user engagement.

Business Questions

1. What are some trends in smart-device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat's marketing strategy?

Tools Used

- Python (Pandas) — Data cleaning, transformation, merging, and analysis
- Kaggle Notebook — Python analysis environment
- Microsoft Excel — Data visualization
- GitHub — Project documentation and portfolio presentation

Dataset

The analysis uses Fitbit Fitness Tracker Data provided through Kaggle.

After cleaning:

- 1,373 daily activity records
- 35 activity users
- 410 sleep records
- 24 users with sleep data
- Analysis period: March 12, 2016 – May 12, 2016

Data Cleaning

Key data preparation steps included:

- Combined two daily activity datasets
- Identified and resolved overlapping records from April 12, 2016
- Removed duplicate sleep records
- Standardized date formats
- Retained and flagged zero-step records rather than automatically removing them
- Created weekday variables for weekly pattern analysis
- Merged activity and sleep data using user ID and date

Key Findings

- Users averaged approximately "7,377 steps per day".
- "Saturday" recorded the highest average daily steps at "7,752", while "Sunday" recorded the lowest at "6,607".
- "80% of users" were classified within the low or moderate activity groups using the project-defined thresholds.
- Light activity dominated recorded active time at approximately "188.1 minutes per day".
- Daily steps showed a "moderate positive correlation with calories burned (r = 0.58)".
- Among users with available sleep data, average sleep duration was approximately "6.99 hours per night".

Business Recommendations

1. Personalized Movement Goals
Provide achievable movement goals based on individual activity levels, emphasizing walking, movement breaks, and gradual improvement.

2. Day-Specific Engagement
Use personalized reminders and challenges based on users' activity patterns throughout the week.

3. Activity and Sleep Integration
Combine activity and sleep insights to provide personalized weekly wellness summaries and help users better understand their overall behavior.

Limitations

The dataset represents a relatively small sample of Fitbit users and contains data collected in 2016. It does not represent Bellabeat's actual customer base. Sleep data was also available for only 24 of the 35 activity users.

Therefore, the findings should be treated as exploratory and validated using larger, more recent Bellabeat customer data before major marketing decisions are made.

Project Files

- `Bellabeat_Case_Study.ipynb` — Complete Python analysis
- `Bellabeat_Case_Study_Report.pdf` — Final case study report

 Author

Mohamed Rifkhan

B.Tech Computer Science & Engineering  
Data Analyst
