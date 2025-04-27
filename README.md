# Portfolio Project | Russel Dayao
TrendSpark Media, founded in 2016, is a digital marketing agency specializing in viral content optimization and influencer strategy. It partners with brands to scale their online presence through data-driven campaigns across top platforms, including TikTok, Instagram, Twitter, and YouTube.

As a data analyst embedded within the performance insights team, I audited over 9,000 viral social media posts to understand engagement behavior across formats and regions. While TrendSpark collects significant data across its campaigns, this engagement data has not yet been deeply leveraged to optimize platform-specific strategies or content creation.

This project analyzes and visualizes those trends using Excel and Power BI to uncover critical insights to enhance content planning, influencer partnerships, and campaign ROI.

 Insights and recommendations are provided on the following key areas:
### • Content Type Performance
Comparing the performance of different content types (Reels, Shorts, Tweets, Posts, etc.) across platforms to identify high-performing formats.  
### • Platform Effectiveness
Measuring which platforms drive the most engagement relative to views and content type.
### • Hashtag Impact
Analyzing the role that trending hashtags play in driving virality and interaction rates.  
### • Improving the region with the least engagement
Analyzing best-performing platforms, content type, and hashtags. To significantly improve the engagement within the region.

## Data Structure & Initial Checks
To ensure a reliable foundation for the analysis, preliminary quality checks and data familiarization steps were carried out using Excel. This included checking for missing values, inconsistent platform naming, duplicate post IDs, and abnormal engagement metrics.


![Data Structure & Initial Checks](Data%20Structure%20%26%20Initial%20Checks.png)

• During the process, inconsistent platform naming was identified (e.g., Tweets labeled as TikTok content, and Reels or Shorts assigned to Twitter). This was resolved by applying a correction formula: =IF(D16="Reel", "Instagram", IF(D16="Shorts", "YouTube", IF(D16="Tweet", "Twitter", IF(D16="Post", "Instagram", [@Column])))), ensuring each content type is accurately mapped to its corresponding platform.       
## Executive Summary
### Overview of findings
This analysis shows that Instagram leads in views (9.5 billion) and engagement (1.28 billion) across platforms. Overall, the average engagement rate across all platforms is strong at 52.7%, with YouTube performing the best at 61%. Content types like "Live Streams" and "Shorts" achieve the highest engagement rates. Regionally, the USA shows high engagement rates above 70%, while Germany lags at 32.76%. This data highlights Live-stream and short-form content as key drivers for maximizing audience interaction globally.

Below is the overview page from the Power BI dashboard. The entire interactive dashboard can be downloaded [here](https://drive.google.com/file/d/1FVmJrd_GSJkrSFB63pztr2QMiNC-bj4-/view?usp=sharing)  
![Executive Summary](executive%20summary1.png)

## Insights Deep Dive
### Regional Overall Engagement Performance

• The United States leads with the highest engagement rate at 70.77%, followed by Japan (58.23%), the UK (54.28%), Canada (52.61%), Australia (52.16%), and Brazil (50.97%). India (47.08%) and Germany (32.76%) trail behind, indicating regional variations in audience responsiveness.    

• Germany recorded the lowest overall engagement rate at 32.76%, suggesting an urgent need for revised or localized content strategies in that market.    

• A significant engagement gap of over 38% exists between the United States (77.20%) and Germany (32.76%), highlighting the USA as the strongest opportunity region, while Germany presents challenges.    

• Engagement trends demonstrate the importance of highly localized and audience-specific strategies to maximize performance, especially by adopting best practices from high-performing regions like the USA and Japan.  

![Country with the Least Engagement](Country%20with%20the%20least%20engagement2.png)

Here we will analyze the three least performing countries in terms of average engagement (%). 
### Brazil
### Platform Performance:
• Twitter Leads: With an average engagement rate of 60.43%, Twitter stands out as the top-performing platform in Brazil. This indicates a highly active and responsive user base on Twitter content.  

• Instagram Shows Promise: While the overall average engagement rate is provided for Brazil as a whole, the individual platform breakdown shows Instagram also has a significant engagement rate (50.51% ), suggesting a strong appetite for post content on this platform within the Brazilian market.  

• YouTube's Solid Performance: YouTube maintains a respectable engagement rate of 44.74%, highlighting its importance for video content and audience interaction in Brazil.  

• TikTok Lags: TikTok engagement rate (42.75%) is also quite high, especially in the short form videos, with the (106.37%) engagement for Fashion hashtags. 

### Content Type Effectiveness:
• Video Reigns Supreme: Traditional video exhibits the highest engagement rate at 71.37%, confirming the effectiveness of video content in capturing audience attention.  

• Post Drive Interaction: Traditional posts exhibit a high engagement rate at 64.84%, indicating that static image or text-based content continues to resonate strongly with the Brazilian audience. 

• Shorts Show Potential: Shorts have a decent engagement rate of 56.52%, suggesting that short-form vertical video is gaining traction and should be considered as part of your content strategy in Brazil.  

• Live Streams Engage: Live streams, with an engagement rate of 27.95%, offer opportunities for real-time interaction and building community with your Brazilian audience.  

### Hashtag Impact:
• #Fashion (Fashion) Dominates: The hashtag #Fashion shows an exceptionally high engagement rate of 106.37%, indicating a strong interest in fashion-related content within Brazil.  

• #Gaming and #Dance Perform Well: #Gaming (76.43%) and #Dance (74.97% ) also demonstrate significant engagement, suggesting that gaming and dancing content resonates with Brazilian users.  

• Diverse Interests: A range of other hashtags like #Fitness (57.42%), #Comedy (44.01%), #Tech (43.25%), and #Viral (31.12%) also show strong engagement, highlighting the diverse interests of the Brazilian online community.  

![Brazil](Brazil%20overall%20performance1.png)

### India
### Platform Performance:
• Twitter Leads in India: Twitter shows the highest average engagement rate in India at 61.05%. This suggests a very active and engaged user base on Twitter in the Indian market.  

• TikTok Remains Strong: TikTok also performs well in India with an engagement rate of 47.72%, indicating its continued importance.  

• Instagram Shows Potential: Similar to Brazil, Instagram has a notable engagement rate in India at 43.28%, highlighting the popularity of short-form video and post content.  

• YouTube Solid, but Lower: YouTube's engagement rate in India is 40.29%, slightly lower than other platforms but still significant for video content.

### Content Type Effectiveness:
• Tweets Lead Significantly: Tweets have the highest engagement rate in India at 57.60%, aligning with Twitter's overall strong performance.  

• Live Streams Engage Strongly: Live streams also show a high engagement rate in India at 51.69%, suggesting a strong appetite for real-time interaction.

• Posts and Shorts Perform Well: Traditional posts (40.46%) and Shorts (49.95%) also demonstrate good engagement.  

### Hashtag Impact:
• #Music Dominates: The hashtag #Music shows the highest engagement rate in India at 70.52% , indicating a strong interest in music-related content.  

• #Education and #Fitness Perform Well: #Education (65.22%) and #Fitness (62.33%) also exhibit high engagement, suggesting popular content themes.  

![India](India%20overall%20performance1.png)
### Germany
### Platform Performance:
• YouTube Leads: With an average engagement rate of 38.74%, YouTube stands out as the top-performing platform in Germany. This indicates a strong affinity for video content within this market.  

• TikTok Shows Strength: TikTok also performs well with an engagement rate of 36.92%, highlighting its importance for short-video content engagement in Germany.  

• Instagram Solid: Instagram maintains a respectable engagement rate of 33.85%, suggesting a consistent and engaged user base.  

• Twitter Lags: Twitter has a lower engagement rate of 22.48% compared to other platforms in Germany.  

### Content Type Effectiveness:

• Videos Drive Engagement: Videos exhibit the highest engagement rate at 44.89%, confirming their effectiveness in capturing audience attention in Germany.  

• Reels Show Potential: Reels also perform strongly with an engagement rate of 40.13%, indicating the growing popularity of short-form vertical video.  

• Live Streams Engage: Live streams have a solid engagement rate of 39.65%, suggesting opportunities for real-time interaction.  

• Posts Perform Moderately: Traditional posts have an engagement rate of 30.08%, remaining relevant but not the top performer.  

### Hashtag Impact:
• #Gaming Dominates: The hashtag #Gaming shows the highest engagement rate at 74.40%, indicating a significant interest in gaming-related content in Germany.  

• #Music Performs Well: #Music also has a strong engagement rate of 43.18%, highlighting the popularity of music-related content.  

• #Fitness Shows Promise: #Fitness demonstrates a good engagement rate of 40.05%, suggesting an interest in health and wellness.  

• Lower Engagement for Others: Other hashtags like #Challenge (22.63%), #Dance (24.27%), and #Tech (29.57%) show moderate engagement.  


![Germany](Germany%20overall%20performance1.png)  
Below is the overview page from the Power BI dashboard. The entire interactive dashboard for exploring insights per region  can be downloaded [here](https://drive.google.com/file/d/1FVmJrd_GSJkrSFB63pztr2QMiNC-bj4-/view?usp=sharing)
## Recommendation: 
Based on the uncovered insight from the three least performing countries, the following recommendations have been provided: 
### Brazil
• Capitalize on Twitter Dominance: Given its leading engagement rate, prioritize Twitter for key campaigns and content initiatives targeting the Brazilian market. Explore various content formats that perform well on the platform, including visually appealing posts, engaging videos, and interactive Stories.     

• Leverage the Power of Posts: Recognize that traditional posts still hold significant engagement in Brazil. Ensure your strategy includes high-quality static content alongside newer formats. 

• Embrace Video Content: Both standard videos and Reels demonstrate strong engagement. Invest in creating compelling video content tailored to each format's strengths to maximize audience interaction on YouTube and Instagram.   

•  Explore Live Streams for Deeper Connection: Consider incorporating live stream content to foster real-time engagement and build a stronger sense of community with your Brazilian audience. This format can be particularly effective for Q&A sessions, behind-the-scenes content, or event coverage.  

• Harness the Potential of Trending Hashtags: Integrate relevant and high-performing hashtags like #Fashion, #Gaming, and #Dance into your content to significantly boost organic reach and discoverability among Brazilian users. Research and utilize other trending hashtags relevant to your specific niche and campaigns.  

• Cater to Diverse Interests: The strong engagement across various interest-based hashtags (#fitness, #music, #tech, #vlog) suggests opportunities to connect with specific communities within Brazil. Tailor content and hashtag strategies to align with these diverse interests.  
### India
• Prioritize Twitter: Given its leading engagement rate, focus heavily on Twitter for key campaigns and real-time interactions within the Indian market. Tailor content to suit the platform's strengths, such as concise updates, engaging discussions, and timely responses.  

• Capitalize on Live Streams: Leverage the high engagement rate of live streams for Q&A sessions, product launches, or interactive events to connect deeply with the Indian audience.  

• Explore Fitness, Music, and Education Content: Tap into the strong interest in #Fitness, #Music, and #Education by incorporating these themes into your content strategy to maximize reach and interaction in India.  

• Prioritize Instagram and Twitter for Video: Given their leading engagement rates, focus your video content efforts on Instagram for Live-stream and Twitter for longer-form content to maximize audience interaction in India.  
### Germany
• Embrace Video and Reels: Recognize the strong performance of both standard videos and Reels. Invest in creating compelling video content tailored to each format to capitalize on this trend.  

• Tap into the Gaming Community: Leverage the exceptionally high engagement around the #Gaming hashtag by incorporating gaming-related content where relevant to your brand or audience.  

• Explore Music and Fitness Content: Consider integrating music and fitness themes into your content strategy to connect with engaged communities around these interests.    

### Context for Business Impact
These insights are critical for brands and marketing teams aiming to optimize their social media strategies across different international markets. By aligning platform choice, content formats, and hashtag usage with localized engagement trends, businesses can maximize their reach, boost interaction rates, and build stronger connections with their target audiences in Brazil, India, and Germany. Tailored strategies based on these findings can drive higher ROI from social media efforts and ensure campaigns resonate authentically with regional users.









