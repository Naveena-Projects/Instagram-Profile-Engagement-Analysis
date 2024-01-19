# Instagram-Profile-Engagement-Analysis
## A Comprehensive Study of Audience Interaction and Content Impact
## Introduction
This report aims to provide analysis and insights about a Tech-Ed Instagram profile (@dataanalystduo) with an impressive following of approximately 106,000 enthusiasts. This analysis is based on the invaluable data generously shared by the account holder which includes information about contents posted and the account’s growth over a period of time.

## Objectives
* Conduct a comprehensive analysis of the content reach, engagement metrics and growth rate of the Instagram profile, aiming to unveil patterns and trends; and to provide strategic recommendations to enhance the profile's outreach.
* Develop a data-driven Instagram engagement analysis dashboard using Excel to gain insights on performance metrics of various types of posts.

## Data Cleaning and Preparation
The source dataset contained blank columns and insignificant data in certain tables. These inconsistencies were rectified to facilitate further analysis. Here are the specific steps taken:
*1 Date columns from ‘reach’, ‘profile visits’ and ‘new followers’ tables contained dates with unnecessary zeroes which were subsequently removed.
	The required columns for content analysis were separated from content table and stored in a new table on a separate worksheet.
	Data from various tables were consolidated based on a common start date to analyse relationships and trend among them.
	Several important metrics, including total engagement, retention rate, growth rate, and daily follower counts, were calculated using the provided details:
	Total followers on a particular day: 
The total followers count on the start date is calculated by summing up all the daily new followers and subtracting this from the total followers count on the final date of the dataset. The daily followers count is the sum of existing followers and new follows on the previous day. 
Total followers= total followers on the previous day+new follows on the previous day  
	Retention rate of reels: Percentage of people who viewed the reel for at least 3 seconds,
Retention rate = 3s views /  Impressions 
	Total Engagement: Computed as the sum of all forms of engagement with the particular post,
 Total Engagement =  likes + comments + shares + saves
	Growth rate: Represents the rate at which the profile grows on daily basis,
Growth rate =  ( (new follows on that day - new follows on the previous day))/(new follows on the previous day)


NOTE: 	Information about unfollows not available in the dataset, hence not included in the calculations.
