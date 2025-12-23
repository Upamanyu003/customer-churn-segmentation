# Customer Churn Prediction & Segmentation System

Customer churn is a growing challenge for subscription-based businesses, especially in the telecommunications sector, since retaining customers is much cheaper than acquiring new ones. This project discusses a system for churn prediction and segmentation through machine learning to identify customers at risk of leaving and support businesses in deploying targeted and data-backed retention strategies.

##  Project Overview

The system analyses the following key customer attributes using a Random Forest classifier:

- Tenure
- Monthly charges
- Type of contract
- Internet and support services
- Payment methods
- Customer Demographics

Using these features, the model predicts the probability of churn and segments the customer into:

- **Heigh-Risk Customer**
- **Medium-Risk Customer**
- **Low-Risk Customer**

It helps business firms to focus their retention efforts, personalise offers, and decrease customer churn more effectively.

##  Key Features

 - Designed a Random Forest-based churn prediction model that attained very high accuracy. 
 - Segmentation of customers based on the probability threshold for targeted retention  
 - Major churn indicators and behavioural patterns identified through exploratory analysis. 
 - Real-time predictions are provided via a Flask-based web application. 
 - The user interface allows the input of customer details and instant churn risk output.  

## Business Impact

This solution enables organisations to:

- Proactively intervene to reduce churn.
- Improve customer satisfaction by personalising engagement
- Optimise marketing and retention budgets
- Improve long-term customer loyalty and revenue stability.

It transforms raw customer data into meaningful insights, thereby assisting decision-makers in the identification of vulnerable customers, even before they churn. This enables timely and effective action.

## Technology Stack 

- **Machine Learning**: Random Forest - Scikit-learn
- **Backend**: Flask
- **Languages**: Python
- **Visualization**: Matplotlib, Seaborn
- **Dataset**: Customer Churn Data(Telecom)


## Future IMprovement

- Deploy as a cloud-hosted web service.
- Add recommendations for retention strategies based on customer persona.
- Incorporate a feedback loop for retraining the model


