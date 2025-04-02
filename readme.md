# Predicting Buyer Retention for Campaign Effectiveness

## Background

The goal is to predict whether a new buyer will become a retained buyer or not based on their behavior in their first two weeks on the platform. This helps assess whether a certain campaign is attracting more retained buyers.

## Objective

Develop a predictive model that accurately identifies new buyers likely to be retained, enabling the e-commerce platform to optimize marketing campaigns by focusing on initiatives that attract high-quality, long-term buyers.

## Data Dictionary

The dataset includes user registration information, early purchase behavior, transactional data, platform engagement metrics, payment and financial activity, delivery and shipping preferences, and shop interaction behavior. Key features include:

*   **User and Registration Information**: registration date, gender, age group, region.
*   **Early Purchase Behavior**: purchase made within the first 14 days, down payment option used.
*   **Transactional Data**: number of vouchers claimed, number of orders placed, total Gross Merchandise Value (GMV).
*   **Platform Engagement Metrics**: product detail page views, store page views, unique login days, total login sessions, time spent on the platform, average time per session.
*   **Payment and Financial Activity**: usage frequency of various payment methods, digital wallet top-up amount.
*   **Delivery and Shipping Preferences**: delivery options chosen.
*   **Shop Interaction Behavior**: interaction with different shop types, participation in flash sale events.

## Key Insights

*   Activating digital wallet within the first two weeks shows a strong positive impact on retention.
*   Frequent logins correlate with higher retention.
*   Increased voucher claims imply that users who actively claim vouchers tend to stay engaged.

## Model Selection

CatBoost was selected as the best performing model due to its high ROC AUC and precision.

## Feature Importance

Key features influencing buyer retention include digital wallet activation, login frequency, and voucher usage.
