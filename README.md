# Social Media Sentiment & Customer Engagement Analysis

> Which sentiment, platform, market and posting time drive engagement, and where is activity just high volume?

## Project Overview
This project analyzes 732 social media posts to understand customer sentiment, engagement, platform performance, geographic activity and time-based patterns. It was completed during my Business Analytics Internship at Codveda Technologies using Power BI, Power Query and DAX.

## Business Problem
The company receives a high volume of social media activity across platforms and markets but lacks a clear view of customer sentiment and engagement. Without it, it is hard to identify high-performing platforms, understand customer reactions, monitor sentiment risks, or tell when and where engagement is strongest.

## Objectives
- Analyze customer sentiment and its link to likes and retweets
- Compare platform performance
- Examine geographic activity
- Identify monthly, hourly and yearly activity patterns
- Turn findings into practical recommendations

## Dataset
- **Records:** 732 social media posts
- **Coverage:** 3 platforms (Instagram, Twitter, Facebook) and 33 countries
- **Fields:** Sentiment, Platform, Country, Likes, Retweets, Timestamp, Hashtag, Year, Month, Day, Hour

## Tools Used
| Tool | Purpose |
|------|---------|
| Power Query | Data cleaning and transformation |
| DAX | Analytical measures (likes and retweets per post) |
| Power BI | Dashboard and visualization |

## Analytical Approach
Business Problem → Data Cleaning → Transformation → Analysis → Dashboard → Deeper Analysis → Insights → Recommendations

The analysis compares **volume** (total posts and likes) with **engagement intensity** (average likes per post). Totals show where activity happens; averages show where content performs.

## Dashboard Pages
1. **Cover:** project title and headline numbers
2. **Overview:** KPIs, sentiment distribution, posts by platform, activity over time (year drill-down)
3. **Analysis:** posts by country, country and sentiment, activity by hour
4. **Insight:** findings, recommended actions and success measures

## Key Insights
- **Sentiment:** Positive had the most posts (45), but Joy earned more per post (49.3 vs 37.8 likes). The gap held in 2023 (46.2 vs 37.8), so the most frequent sentiment is not the most engaging.
- **Platform:** Instagram led with 258 posts and the highest average of 45.1 likes per post. It stayed above average in 2023 (44.75 vs 42.31).
- **Geography:** The USA was the most active market (188 posts, 8,358 likes, about 44.5 per post). Positive led by volume, while Neutral earned more per post (small sample).
- **Timing & growth:** February (85 posts) and 2 PM (94 posts) were the busiest month and hour across all years, yet both average slightly below 42.9 likes per post. Posts surged to 289 in 2023 (39% of the total), but likes per post stayed near 42.

## Recommendations
- Prioritize Instagram for high-impact content
- Build on engaging sentiments, especially Joy
- Monitor sentiment in high-activity markets, particularly the USA
- Test posting around 2 PM and compare likes per post against other hours
- Track likes and retweets per post to measure improvement

## Success Measures
- **Likes per post:** compare engagement quality across platforms, sentiments and years
- **Retweets per post:** monitor how strongly content is shared
- **Sentiment engagement:** check whether Joy keeps outperforming
- **Platform engagement:** compare performance after content changes
- **Peak-period engagement:** test whether 2 PM beats other hours on likes per post

## Limitations
- Some sentiment and country-sentiment groups are small, so their averages are indicative only
- Month and hour results are pooled across years and strongly reflect 2023
- Findings show patterns, not cause and effect
- Retweets were tracked but not analyzed in depth

## Conclusion
Post volume alone does not show performance. Sentiment, platform, geography and timing shape engagement differently, and the 2023 surge in posts did not raise likes per post. These findings support more targeted content planning, stronger engagement strategies and closer sentiment monitoring.

## Repository Contents
- `Social_Media_Sentiment_Dashboard.pbix`: Power BI dashboard
- `Social_Media_Sentiment_Engagement_Report.pdf`: full report
- `screenshots/`: cover and dashboard page images
- `README.md

## Author
**Zainab Danjuma**
Business Analytics Intern, Codveda Technologies
