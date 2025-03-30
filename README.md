# Facebook vs Adwords - AB Testing Analysis

### **Business Challenge**  

Our marketing agency is dedicated to maximizing the return on investment (ROI) for our clients' advertising campaigns. To assess platform effectiveness, we ran two separate ad campaigns—one on Facebook and another on AdWords. Our objective is to determine which platform delivers better results in terms of clicks, conversions, and overall cost efficiency. By identifying the most effective option, we can strategically allocate resources and refine our advertising approach to achieve better outcomes for our clients.  
### **Dataset Description**

| **Column**                | **Description**                                                                 |
|--------------------------------|---------------------------------------------------------------------------------|
| **date_of_campaign**           | The date of each campaign, ranging from 2021 to 2024.                          |
| **facebook_ad_campaign**       | The name of the Facebook ad campaign.                                          |
| **facebook_ad_views**          | Number of people who viewed the Facebook ad.                                   |
| **facebook_ad_clicks**         | Number of people who clicked the Facebook ad after viewing it.                 |
| **facebook_ad_conversions**    | Number of people who became customers after clicking the Facebook ad.          |
| **facebook_cost_per_ad**       | Cost (in USD) of running a Facebook ad.                                        |
| **facebook_ctr**               | Facebook Click-Through Rate (%) = (facebook_ad_clicks / facebook_ad_views) × 100 |
| **facebook_conversion_rate**   | Facebook Conversion Rate (%) = (facebook_ad_conversions / facebook_ad_clicks) × 100 |
| **facebook_cost_per_click**    | Cost per click for Facebook ads (USD) = (facebook_cost_per_ad / facebook_ad_clicks) |
| **adword_ad_campaign**         | The name of the AdWords campaign.                                              |
| **adword_ad_views**            | Number of people who viewed the AdWords ad.                                    |
| **adword_ad_clicks**           | Number of people who clicked the AdWords ad after viewing it.                  |
| **adword_ad_conversions**      | Number of people who became customers after clicking the AdWords ad.           |
| **adword_cost_per_ad**         | Cost (in USD) of running an AdWords ad.                                        |
| **adword_ctr**                 | AdWords Click-Through Rate (%) = (adword_ad_clicks / adword_ad_views) × 100    |
| **adword_conversion_rate**     | AdWords Conversion Rate (%) = (adword_ad_conversions / adword_ad_clicks) × 100 |
| **adword_cost_per_click**      | Cost per click for AdWords ads (USD) = (adword_cost_per_ad / adword_ad_clicks) |


### **Approach**  

- **Platform Comparison:** Evaluate key metrics such as click-through rate (CTR), conversion rate, and cost per click for Facebook Ads and AdWords.  
- **Performance Trends:** Analyze how ad performance metrics evolve over different years.  
- **A/B Testing Insights:** Compare simultaneous campaigns to determine which platform performs better.  
- **Cost Efficiency Analysis:** Identify campaigns that achieve high conversions at lower costs.  
- **Data Visualization:** Use charts to visually compare campaign performance.  
- **Statistical Analysis:** Conduct hypothesis testing to determine significant differences in performance metrics.  
- **Strategic Recommendations:** Offer data-driven insights to optimize future marketing strategies.
