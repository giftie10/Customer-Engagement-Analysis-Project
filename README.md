# Student Engagement Analysis

This project analyzes student engagement, measured in minutes watched, between **paid** and **free** users on an educational platform. The comparison covers Q4 2021 and Q4 2022, aiming to understand how new platform features influenced engagement across both user types and between US and Indian users.

## Project Overview

1. **Objective:** Determine engagement trends, yearly changes, and the impact of platform updates on both free and paid users.
2. **Data Scope:** Q4 data from 2021 and 2022, split by paid and free user segments.
3. **Analytical Focus:** Key statistical metrics, t-tests, confidence intervals, and error analysis.

## Key Findings

### 1. Engagement Trends by User Type

**Paid Users**:
- **Engagement Change**: 61.3% of paid users increased engagement from Q4 2021 to Q4 2022.
- **Mean Increase**: Average minutes watched rose significantly (33.80 to 273.02).
- **Variability**: A substantial rise in standard deviation (28.21 to 854.58), indicating a few users engaged far more, while others remained low.

**Free Users**:
- **Engagement Change**: 47.9% showed increased engagement, with a slight majority decreasing.
- **Mean Increase**: Mean minutes rose from 25.39 in 2021 to 117.64 in 2022, but the median fell, highlighting low engagement among most users despite a few high-engagement outliers.
- **Variability**: A rise in standard deviation, revealing a broader engagement disparity.

### 2. Statistical Analysis and Interpretation

- **Hypothesis Testing**:
  - **Paid Users**: Significant increase in minutes watched (t-statistic: 29.78), leading to rejection of the null hypothesis, suggesting higher engagement in 2022.
  - **Free Users**: Decrease in minutes watched (t-statistic: -3.05), with a p-value < 0.05, supporting the conclusion that free users watched fewer minutes in 2022.
- **Regional Comparison (Task 5)**:
  - Comparison between US and Indian free-plan users showed no statistically significant difference in engagement, suggesting engagement was similarly low across regions.

### 3. Conclusions and Recommendations

- **Engagement Shift**: Paid users’ engagement improved post-feature update, whereas free users’ engagement declined, potentially due to the lack of access to premium features.
- **Costly Errors**:
  - **Type I Error**: High risk if the platform continues investing in features that don’t effectively engage users.
  - **Type II Error**: Missed opportunities for user retention, particularly for free users.
- **Localized Strategy**: No significant engagement difference between US and Indian free users, suggesting that future feature updates should target a broader range of users instead of regional adjustments.

## Suggestions for Future Work

1. **Investigate Engagement Drivers**: Identify specific platform features that contributed to the engagement increase among paid users.
2. **Explore Free User Retention**: Consider incentives or additional features for free users to maintain engagement.
3. **Localized Interventions**: While regional differences are insignificant here, ongoing analysis may reveal evolving engagement trends.

## Acknowledgments

Special thanks to Alex the Analyst for the guidance and support to pull of the project.

