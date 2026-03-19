# RainGap – Income Gap Protection for Delivery Workers

## Problem Statement
Food delivery workers (Swiggy/Zomato) depend on daily orders for income. During heavy rain, they do not always stop working, but their earnings drop significantly due to fewer orders, slower deliveries, and unsafe conditions. This creates an income gap where workers are active but unable to earn enough. Currently, there is no system that identifies and compensates for this hidden income loss.

## Persona
Ravi is a Zomato delivery partner working in a busy urban area. On normal days, he earns around ₹600 per day. During heavy rain, he stays active on the app but receives fewer orders and spends more time per delivery. As a result, his earnings drop to less than ₹100 or sometimes zero. Ravi needs a system that can understand this drop in earning potential and support him financially during such conditions.



## Solution Overview
RainGap is a system that gives money to delivery workers when heavy rain reduces their income.

## Workflow
1. Worker registers in the app
2. Worker selects a weekly insurance plan
3. System checks weather data regularly
4. When heavy rain occurs, system detects it
5. System checks if worker is active but getting fewer orders
6. If income is reduced, claim is triggered automatically
7. Worker receives payout



## Weekly Premium Model
Workers pay a small weekly amount (₹20–₹30) to stay insured. When heavy rain affects their work and reduces their income, they receive a payout of around ₹300–₹500 depending on the situation.

## Parametric Triggers
The system automatically triggers payout when:
- Rainfall crosses a certain level (heavy rain)
- Worker activity drops during that time
- Fewer orders are received compared to normal days

## AI/ML Integration
RainGap uses AI to make the system smarter and more accurate.

1. Risk Prediction
The system analyzes weather data and location to predict how likely heavy rain will affect delivery work.

2. Income Drop Detection
AI compares the worker’s current activity (orders, deliveries) with normal days to detect a drop in earnings.

3. Dynamic Premium
Premium amount is adjusted based on risk level. High-risk areas may have slightly higher premiums.

4. Fraud Detection
AI detects fake claims by checking:
- unusual activity patterns
- repeated claims
- mismatch between location and weather data
