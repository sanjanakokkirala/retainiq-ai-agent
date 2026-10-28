# RetainIQ

Customer churn and retention intelligence · Demo company: Spotify Premium (India) · 60 sample subscribers

## 1 · At-risk segments

## 2 · Subscribers ranked by value of saving them

Segment

## 3 · Why this customer may leave, and what to do

Click a subscriber above.

## 4 · RetainIQ AI agent

## How it works (algorithm)

1\) Collect usage, billing, support and plan data → 2) Engineer features (usage trend, inactivity, skip rate, tickets, payment failures, price, tenure) → 3) Score churn probability with gradient boosting / survival model → 4) Explain each score with SHAP-style driver contributions → 5) Segment at-risk users by their top driver (K-means in production) → 6) Pick the best retention action per segment using uplift modeling → 7) Rank by expected value = risk × annual value × save rate − cost. This demo uses a fixed explainable scoring model on synthetic data.