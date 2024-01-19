# Instagram-Profile-Engagement-Analysis
## A Comprehensive Study of Audience Interaction and Content Impact
## Introduction
This report aims to provide analysis and insights about a Tech-Ed Instagram profile (@dataanalystduo) with an impressive following of approximately 106,000 enthusiasts. This analysis is based on the invaluable data generously shared by the account holder which includes information about contents posted and the account’s growth over a period of time.

## Objectives
* Conduct a comprehensive analysis of the content reach, engagement metrics and growth rate of the Instagram profile, aiming to unveil patterns and trends; and to provide strategic recommendations to enhance the profile's outreach.
* Develop a data-driven Instagram engagement analysis dashboard using Excel to gain insights on performance metrics of various types of posts.

## Data Cleaning and Preparation
The source dataset contained blank columns and insignificant data in certain tables. These inconsistencies were rectified to facilitate further analysis. Here are the specific steps taken:
1) Date columns from ‘reach’, ‘profile visits’ and ‘new followers’ tables contained dates with unnecessary zeroes which were subsequently removed.
2) The required columns for content analysis were separated from content table and stored in a new table on a separate worksheet.
3) Data from various tables were consolidated based on a common start date to analyse relationships and trend among them.
4)Several important metrics, including total engagement, retention rate, growth rate, and daily follower counts, were calculated using the provided details:
	* Total followers on a particular day: 
	The total followers count on the start date is calculated by summing up all the daily new followers and subtracting this from the total followers count on the final date of the dataset.
	The daily followers count is the sum of existing followers and new follows on the previous day. 
		* Total followers= total followers on the previous day+new follows on the previous day  
	* Retention rate of reels: Percentage of people who viewed the reel for at least 3 seconds,
		* Retention rate = 3s views /  Impressions 
	* Total Engagement: Computed as the sum of all forms of engagement with the particular post,
 		* Total Engagement =  likes + comments + shares + saves
	* Growth rate: Represents the rate at which the profile grows on daily basis,
		* Growth rate =  ( (new follows on that day - new follows on the previous day))/(new follows on the previous day)

	##### NOTE: 	Information about unfollows not available in the dataset, hence not included in the calculations.

## Analysis and Insights
### 1.	Comparison of trends among reach, profile visits and new follows
 
* The significant surge in reach during mid-2023 attracted over 6000 profile visits and gained more than 1k followers. 
* Conversely, at the end of 2022, the profile experienced a rise in followers (nearly 1.5k follows) despite lower reach and profile visits.
* Notably, a consistent pattern emerges where increased content reach correlates with heightened profile visits and new follows, indicating a strong relationship between content reach and follower growth.

### 2.	Gender and age diversity of followers
 	   
* Up to 67% of followers are male, predominantly below the age of 45, with the majority falling within the 25-34 age group.
* Regardless of gender, the majority of followers are concentrated within the 18-34 age group.

### 3.	Location diversity of followers
 	 	
* Followers hail from diverse global locations, with over 70% based in India.
* The second-highest follower concentration is from the United States, comprising 7%, followed by the UK, Canada, and Indonesia, each with a 2% share.
* Within India, the state of Karnataka boasts the highest number of followers, exceeding 15,000.
* Interestingly, there is a higher follower count from regional states like Karnataka, Tamil Nadu, and Telangana compared to the host state, Maharashtra.

### 4.	Engagement across different types of posts

* Reels outperform images and carousels in overall engagement, reaching a larger audience.
* Reels are shared among large number of people and reached a wide audience, contributing significantly to gaining new followers.
* Despite the higher reach of Reels, carousels tend to generate more comments and interactions, fostering meaningful connections with followers.

### 5.	Engagement across reels of different length 
 
* Shorter reels, although posted more frequently, slightly underperform compared to longer reels.
* Contrary to the general trend, reels exceeding 30 seconds in duration show higher reach and engagement, with an average retention rate of 52%. This suggests that longer reels maintain viewer interest, leading to sustained engagement.

### 6.	Analysing important keywords used in posts having high impressions 
  
* A thorough analysis of the keywords used in the descriptions of 20 posts with over 1 lakh impressions, aiming to identify crucial terms.
* Recognizing the significance of these keywords related to data analytics and hashtags in gaining views, as they play a vital role in content discovery through search queries related to specific domains.

### 7.	Analysing important keywords used in posts having high follows 
  		
* Examining keywords in the descriptions of 13 reels that gained over 1000 new followers.
* Noteworthy keywords such as "follow," "interview," "project," "job," "trending," "portfolio," and "learning" emerge as influential in driving profile growth, indicating their impact beyond the domain-specific terms related to data analytics.

## Engagement Dashboard
 
* The dashboard offers a thorough visual overview of crucial metrics related to the @dataanalystduo Instagram profile, providing comprehensive insights into its performance. 
* It features trend lines illustrating profile’s reach, new profile visits, and new follows over time. These lines effectively capture the profile’s response among audience and highlight its growth patterns.
* It enables a detailed understanding of audience engagement through an interactive column chart connected with a post type slicer, allowing users to dynamically analyse the overall engagement on various types of posts.
* A map visualization is inserted, providing both a global and country-level perspective on follower distribution. Additionally, a pie chart representing gender diversity of followers is included.
* This comprehensive visualization empowers users to make informed decisions, enhancing their strategy for content creation and audience engagement on the platform.

## Recommendations
* Due to a robust correlation between reach and new followers, it is imperative to maintain a consistent content creation strategy specifically targeting a broader audience and learners within the Tech-Ed community. Regularly producing engaging content attracts a potential audience, expanding reach, and fostering organic growth on Instagram.
* Utilize insights into the demographics and location diversity of followers to identify and target specific audience segments. Tailoring content that resonates with diverse followers, enhances inclusivity and engagement.
* Emphasize the creation and posting of Reel content, as they have proven to be highly effective in reaching a broader audience and gaining new followers. The sharing dynamics of Reels, especially longer ones, contribute significantly to profile growth.
* While Reels are crucial for broad reach, it is equally important to maintain a balanced content strategy by incorporating images and carousels. These formats play a vital role in building a personal connection and fostering direct interaction with followers.
* Continue incorporating keywords and hashtags that have proven effective in posts with high impressions and follows. Stay attuned to trends in relevant domains and regularly update keywords to align with changing user search behaviours.
* Comprehensive analysis of different kinds of contents, profile progress and everyday growth rates facilitate content creation to pull more learners all through the internet. ensuring relevance and resonance with a diverse audience, particularly those seeking learning opportunities online.
 

