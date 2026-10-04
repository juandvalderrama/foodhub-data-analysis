# FoodHub Order Analysis — Exploratory Data Analysis

## Project Overview
FoodHub is a food aggregator platform in New York that connects 
customers with restaurants through a single app. This project 
analyzes 1,898 orders to identify factors affecting customer 
satisfaction and uncover operational inefficiencies.

## Objective
Understand what drives customer ratings and find actionable 
insights to improve FoodHub's business operations.

## Dataset
- 1,898 orders across 178 restaurants and 14 cuisine types
- 9 variables: order cost, cuisine type, food preparation time, 
  delivery time, customer rating, and day of the week
- Source: UT Austin McCombs PGP in Data Science & Analytics

## Tools & Libraries
- Python (pandas, numpy)
- Visualization (matplotlib, seaborn)
- Google Colab

## Key Findings
1. **39% of orders are unrated** — ratings range only 3-5, 
   suggesting dissatisfied customers don't rate rather than 
   leaving low scores (selection bias)
2. **Weekday deliveries take 6 min longer** than weekends 
   despite 2.5x fewer orders — the biggest operational gap
3. **Prep time is identical across days** — confirming the 
   bottleneck is delivery logistics, not the kitchen
4. **Top 4 restaurants handle 30% of orders** — high 
   concentration risk for the platform
5. **No numerical feature correlates with rating** — 
   satisfaction drivers are not captured in this dataset

## Business Recommendations
- Incentivize ratings from dissatisfied customers to close 
  the feedback gap
- Investigate weekday delivery operations (driver staffing, 
  traffic, routing)
- Launch weekday promotions to balance demand across the week
- Diversify restaurant participation to reduce dependency 
  on top performers

## Project Structure
foodhub-data-analysis/
  FoodHub_Project.ipynb    
  foodhub_order.csv        
  README.md                

## Author
Juan David Valderrama Valencia
- [LinkedIn](https://www.linkedin.com/in/juan-david-valderrama-valencia)
- PGP in Data Science & Analytics — UT Austin McCombs
