# Telco Customer Churn Analysis
![image](https://sdmntpreastus.oaiusercontent.com/files/00000000-fb78-61f9-bb59-76728e0481e2/raw?se=2025-07-23T12%3A12%3A04Z&sp=r&sv=2024-08-04&sr=b&scid=89cd1e0e-012a-57ba-96a0-ba34452cdd19&skoid=02b7f7b5-29f8-416a-aeb6-99464748559d&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-07-22T23%3A43%3A05Z&ske=2025-07-23T23%3A43%3A05Z&sks=b&skv=2024-08-04&sig=QQTRynhUhLNrXHcS6GIzM7uAoX9fYEdvG46pQjksFOY%3D)

This project explores and models customer churn data for a telecommunications company. The main objective is to understand the key drivers of customer churn and to build predictive models that can help identify customers who are likely to leave the service.This will help the organisation improve their services and be able to retain customers.

## Project Overview

In today’s fast-paced and highly competitive telecommunications sector, retaining customers is more important than ever. This project focuses on understanding customer churn—the phenomenon where users terminate their service. By analyzing historical customer data, the goal is to uncover trends and pinpoint the main drivers of churn. These findings will help the company craft targeted strategies to boost customer retention and reduce the rate of churn.
This project includes:

## Business and Data Understanding
The dataset used is available as a file in this repository and it contains the following elements:-
- States
- Phone numbers and area codes
- Total day, evening and night calls, charges and minutes.
- Customer service calls.
- Churn. Whether a customer left or not.
### Some of the methods used to analyse this data are:-
- Data loading and cleaning
- Exploratory data analysis (EDA)- Where I was able to assess the customer churn distribution as below
This figure shows the rate of customer churn as compared to the customer service calls. which indicates that customers tend to leave if not given proper service.
- Feature engineering
- Machine learning model building and evaluation
- Insights and recommendations

## Files Included

- `CHURN PROJECT.ipynb`: The main Jupyter Notebook with all code, visualizations, and analysis.
- `README.md`: This file.
- `Churn.csv`: The data set


- 
## Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
From the classification I was able to obtain the following findings:-
 **Interpretability:** Logistic Regression provides clear coefficients for each feature, making it easy to interpret how each variable (e.g., customer service calls, international plan) affects the likelihood of churn.
- **Simplicity:** It is straightforward to implement and computationally efficient, making it suitable for quick baseline modeling.
- **Probability Outputs:** The model gives probability scores, which can be useful for ranking customers by churn risk.

#### **Outcome in This Project**
- Random Forest, as seen in the classification report and confusion matrix, typically achieves higher accuracy and better captures complex patterns in customer behavior.

**Complex, Non-Linear Relationships:**  
  The churn dataset contains a mix of numerical features (call minutes, charges, number of service calls) and categorical features (international plan, voice mail plan, state). Random Forest is well-suited to capture complex, non-linear interactions between these variables, which are common in customer behavior data.

- **Strong Predictive Performance:**  
  The classification report and confusion matrix show that the Random Forest model achieves high accuracy and balanced precision/recall for both churners and non-churners. This means the model is effective at flagging customers at risk of leaving, while minimizing false alarms.


**Note that** While feature importance is available, individual predictions are less transparent compared to logistic regression.


Given the complexity and variety in the telecom churn data, Random Forest provides a strong balance of predictive power and business interpretability. Its ability to highlight the most influential churn factors makes it not only a high-performing model but also a valuable tool for guiding business decisions.

## Key Findings
 Through comprehensive data cleaning, exploration, and modeling, we identified key drivers influencing churn, such as frequent customer service calls, international plan usage, and high day-time call activity.

By transforming raw telecom data into actionable insights, this solution empowers the organization to:

- Reduce churn through targeted interventions

- Optimize plan offerings

- Improve overall customer satisfaction

In conclusion, machine learning provides a scalable, data-driven approach to enhancing customer loyalty and reducing revenue loss — critical components for long-term business sustainability in the competitive telecom industry.

