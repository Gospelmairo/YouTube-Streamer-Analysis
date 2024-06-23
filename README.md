# YouTube Streamer Analysis

This project explores trends and performance metrics of YouTube streamers, providing valuable insights into streaming trends, audience demographics, and high-performing content categories.

## Data Exploration

I investigated the data structure, identified key variables, and addressed missing data and outliers.

## Analysis

### Trends
- Discovered popular content categories.
- Analyzed subscriber-engagement correlations.

### Audience
- Examined the geographic distribution of viewers.
- Identified regional content preferences.

### Performance Metrics
- Calculated and visualized average metrics (subscribers, visits, likes, comments) to uncover patterns and anomalies.

### Content Categories
- Explored the distribution of content types.
- Identified high-performing categories.

### Benchmarking
- Identified top streamers based on key metrics to understand success factors.

### Brands and Collaborations
Analyzed whether streamers with high performance metrics receive more brand collaborations and marketing campaigns.
- Defined high performance metrics based on the top quartile for each of the following columns: 'Subscribers', 'Visits', 'Likes', and 'Comments'.
- Assessed the correlation between high performance metrics and the number of brand collaborations and marketing campaigns.

### Content Recommendations
Proposed a system for enhancing content recommendations to YouTube users based on streamers' categories and performance metrics.
- Created a user-item interaction matrix using likes across different categories.
- Converted the interaction matrix to a sparse matrix for efficient computation.
- Computed cosine similarity between users to identify similar users based on interaction patterns.
- Developed a function to recommend content based on similarity scores.

## Libraries Used
- Pandas
- Matplotlib
- Numpy
- Scipy
- Scikit-learn

## Expected Outcome

This analysis will provide valuable insights into YouTube streaming trends, audience demographics, high-performing content categories, and the relationship between performance metrics and brand collaborations. Additionally, the content recommendation system aims to enhance user engagement by suggesting relevant content based on user preferences and interaction patterns.





<!-- # YouTube Streamer Analysis

This project explores trends and performance metrics of YouTube streamers.

Data Exploration:

I investigated the data structure, identify key variables, and address missing data and outliers.

Analysis:

Trends: I discovered popular content categories and analyze subscriber-engagement correlations.
Audience: I examined the geographic distribution of viewers and identify regional content preferences.

Performance Metrics: I calculated and visualized average metrics (subscribers, visits, likes, comments) to uncover patterns and anomalies.

Content Categories: Explored the distribution of content types and identify high-performing categories.

Benchmarking:
We'll identify top streamers based on key metrics to understand success factors.

## Libaries Used
Pandas
Matplotlib
Numpy

### Expected Outcome:

This analysis will provide valuable insights into YouTube streaming trends, audience demographics, and high-performing content categories. -->