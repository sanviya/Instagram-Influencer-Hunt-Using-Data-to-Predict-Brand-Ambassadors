# Instagram-Influencer-Hunt-Using-Data-to-Predict-Brand-Ambassadors
Data analysis and visualization to identify top Instagram influencers


# Instagram Influencer Hunt – Using Data to Predict Brand Ambassadors

## Overview
This project uses publicly available Instagram influencer data (from **Kaggle**) to shortlist top influencers efficiently, without manual scrolling.

## Tasks Completed
1. **Basic Data Cleaning**  
   - Removed unnecessary columns and whitespace.  
   - Converted follower and engagement numbers (e.g., "48.5M", "383.1K") to numeric values.  
   - Dropped rows with missing critical information like followers.  

2. **Visualizations**  
   - Created bar charts showing the top 5 influencers by engagement score.  
   - Analyzed engagement vs followers to identify high-performing micro-influencers.  
   - Tools used: Python (`pandas`, `matplotlib`, `seaborn`).  

3. **Top 5 Influencer Selection**  
   - Weighted engagement score formula:  
     `Influencer Score = (0.6 * Authentic Engagement + 0.4 * Avg Engagement) / Followers`  
   - 60% weight to Authentic Engagement – reflects genuine interactions from real followers.
   - 40% weight to Engagement Average – accounts for general engagement trends, slightly less important. 
   - Dividing by followers allows fair comparison,ensuring smaller influencers with highly engaged audiences are not overlooked.

## Bonus / Brownie Points
- Ranked all influencers using the formula and highlighted **Top 5** visually.  
- Dashboard/report made visually neat with clear charts.  
