# Superstore Customer Clustering & Product Recommendation

This project is built using the Superstore dataset to segment customers based on their purchasing behavior and recommend products using Machine Learning techniques.

Project Summary
We performed the following steps:

Data Preprocessing

Focused on customer sales

Grouped by Customer ID and calculated median sales per customer

Scaled the sales values using MinMaxScaler

Customer Segmentation

Applied K-Means Clustering

Used the Elbow Method to determine the optimal number of clusters (K = 4)

Evaluated cluster quality using the Silhouette Score

Product Recommendation System

Based on cluster assignment, we recommended the top 10 selling products for each customer group

Deployment

The model and results were deployed using Flask with a front-end built using HTML & CSS



## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib

Flask (for deployment)

HTML, CSS (for the UI)

## Team Members
This project was built collaboratively as part of a youth innovation initiative.

Fayza Ahmed Ewais

Belal Abdelrhman Fikry

Esraa Mamdouh Omar 

Ahmed Mahmoud Ahmed

Youssef Abdelnasser Ahmed

## 🇪🇬 Initiative
This project was submitted as part of the "Innovative Youth Initiative" (مبادرة شباب مبتكرون) supported by the Ministry of Youth and Sports, Egypt.
