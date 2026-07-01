# FoodHub Order Data Analysis — Exploratory Data Analysis (EDA)
Exploratory data analysis of ~1,900 food delivery orders for **FoodHub**, a food aggregator app connecting NYC restaurants with customers. This project investigates order patterns, restaurant performance, cuisine preferences, delivery/preparation times, and revenue — translating findings into actionable business recommendations.

## Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Objective
The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to get a fair idea about the demand of different restaurants which will help them in enhancing their customer experience. Suppose you are hired as a Data Scientist in this company and the Data Science team has shared some of the key questions that need to be answered. Perform the data analysis to find answers to these questions that will help the company to improve the business.

## Key Questions Explored

- **Data Quality:** Structure, data types, and missing value checks
- **Descriptive Stats:** Distribution of order cost, food preparation time, and delivery time
- **Restaurant Performance:** Top restaurants by order volume; most popular cuisines (including weekend-specific trends)
- **Customer Behavior:** Identifying top repeat customers for loyalty/discount targeting
- **Promotions:** Restaurants eligible for promotional offers based on rating count (>50) and average rating (>4)
- **Revenue Analysis:** Net revenue calculation using FoodHub's tiered commission structure (25% on orders >$20, 15% on orders >$5)
- **Delivery Performance:** Percentage of orders exceeding 60 minutes total delivery time (prep + delivery)
- **Time Trends:** Weekday vs. weekend delivery time comparison
