# User Demography Analysis Project

This project focuses on analyzing user demographics to gain insights into user engagement, segment users for targeted marketing strategies, and optimize budget allocation. The dataset includes various user metrics such as the number of users, new users, engaged sessions, engagement rate, and average engagement time across different cities in India.

## Project Overview

### 1. **User Engagement Analysis**
   - **Objective**: Analyze engagement metrics across top cities to identify patterns in user behavior.
   - **Methodology**: Visualized and compared key metrics like the number of users, engagement rate, engaged sessions per user, and average engagement time across the top 20 cities by user count.
   - **Key Findings**: Cities like Hyderabad, Bengaluru, and Chennai showed the highest user engagement, with significant variation in engagement patterns across other cities.
   - **Visualizations**:
     - ![Top 20 Cities by Number of Users](https://github.com/aarish22/DemographyAnalysisUsingPython/blob/main/Plots/top20citiesbynumbverofusers.png)
     - ![Engagement Rate in Top 20 Cities](https://github.com/aarish22/DemographyAnalysisUsingPython/blob/main/Plots/engagementrate.png)
     - ![Engaged Sessions per User](https://github.com/aarish22/DemographyAnalysisUsingPython/blob/main/Plots/engagedsessionsperuser.png)
     - ![Average Engagement Time](https://github.com/aarish22/DemographyAnalysisUsingPython/blob/main/Plots/avgengagementtime.png)

### 2. **User Segmentation**
   - **Objective**: Segment users based on activity levels, user type, and geographic location to tailor marketing strategies.
   - **Methodology**: Created segments such as high-engagement users, new users, returning users, and categorized cities into low, medium, and high user count groups based on quantile analysis.
   - **Key Findings**: Identified key user segments that offer the highest potential for engagement and conversions, such as high-engagement users and cities with large user bases.
   - **Visualizations**:
     - ![New Users vs Returning Users in Top 20 Cities](https://github.com/aarish22/DemographyAnalysisUsingPython/blob/main/Plots/newusersvreturningusersintop20cities.png)

### 3. **Budget Allocation Strategy**
   - **Objective**: Develop data-driven budget allocation strategies for targeted marketing campaigns.
   - **Methodology**: Proposed specific budget allocation strategies for each user segment, emphasizing the importance of personalized marketing, retention strategies, and awareness campaigns in underperforming cities.
   - **Recommendations**: Allocated a substantial portion of the budget to high-potential segments, such as high-engagement users and high-user cities, while recommending awareness campaigns for low-user cities to drive growth.

## Dataset

The dataset includes the following fields:

- **Town/City**: Name of the town or city.
- **Country**: The country (all entries are from India).
- **Users**: Total number of users.
- **New users**: Number of new users.
- **Engaged sessions**: Total number of engaged sessions.
- **Engagement rate**: The engagement rate.
- **Engaged sessions per user**: Average number of engaged sessions per user.
- **Average engagement time**: Average time users are engaged.
- **Event count**: Total count of events.

## Technologies Used

- **Python**: Data manipulation and analysis
- **Pandas**: Data processing
- **Seaborn & Matplotlib**: Data visualization
- **Google Colab**: Development environment

## Conclusion

This project provides a comprehensive analysis of user engagement, enabling the formulation of targeted marketing strategies and optimized budget allocation. The insights derived from this analysis can help drive user growth, retention, and overall engagement in key geographic areas.
