# Optimizing Ad Placement Through Viewer Behavior Analysis on 17LIVE

This project analyzes live stream data from the 17LIVE a live streaming platform to uncover insights about viewer engagement and determine the best time to display ads for maximum visibility and impact.

## Business Problem:
17LIVE aims to place ads during live streams to generate revenue and enhance the user experience. To achieve this, the company needs to understand:
1. When streams reach peak viewership, the time when viewers are most active.  
2. Viewer behavior trends such as when users typically join and leave the stream.  
3. Differences in viewer behavior between long and short streams.

## Goal of the Project:
The goal of this project is to analyze viewer behavior during live streams and provide insights to the company. This includes:

- Calculating the peak viewership time in each stream.
- Understanding when users typically join and leave behaviour of the users.
- Comparing peak time patterns between short and long streams.
- Identify the most frequent hours of peak viewership across all streams.

## Technologies, Tools and libraries used:
Python · Exploratory Data Analysis (EDA) · NumPy · Pandas · Matplotlib · Seaborn, Microsoft Excel.

## Steps included:
1) Data Collection – Loaded the 17LIVE stream dataset for analysis.
2) Data Cleaning – Handled missing values and converted time columns to proper formats.
3) Data Manipulation – Created new metrics like time_to_peak and peak_percent.
4) Data Analysis – Explored viewer behavior, peak hours, and OS-based engagement.
5) Data Visualization – Plotted graphs to uncover patterns and insights clearly.
6) Final Conclusion – Summarized key findings to support business decisions on ad timing and stream strategy.

## Key Insights:
1) Peak viewership is typically reached within the first 20% of stream duration, indicating that ads should be placed at the beginning of the stream for maximum visibility.
2) Around 78% of users leave within 5 seconds, 15% stay for about 2 minutes, and only 6% remain for 10 minutes or more. Ads should therefore be placed immediately when the user joins and at the peak viewership time.
3) Short streams reach peak viewership around 53% of their duration, suggesting early ad placements. Long streams peak around 40%, making mid-stream ads more effective.
4) The highest engagement occurs between 1 AM and 3 AM, identifying late-night hours as the most optimal for reaching peak audiences.

## Business Impact:
1) Helped the company identify the highest peak viewership time, allowing ads to be placed strategically and significantly increasing ad revenue.

2) Found that 78% of viewers leave within 5 seconds, leading to new strategies that monetized even the early-leaving users.

3) Discovered that 1–3 AM had the highest viewer activity but fewer streams, so encouraged creators to stream during this time, which improved viewer satisfaction and increased total active screen time.


