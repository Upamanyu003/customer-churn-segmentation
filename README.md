# Customer Churn Prediction & Segmentation System

Customer churn is a growing challenge for subscription-based businesses, especially in the telecommunications sector, where retaining existing customers is far more cost-effective than acquiring new ones. This project presents a machine learning-driven churn prediction and segmentation system designed to identify customers at risk of leaving and assist businesses in deploying targeted, data-backed retention strategies.

##  Project Overview

The system uses a **Random Forest** classifier to analyse key customer attributes such as:

- Tenure
- Monthly charges
- Contract type
- Internet and support services
- Payment methods
- Customer demographics

Based on these features, the model predicts churn probability and segments customers into:

- **High-Risk Customers**
- **Medium-Risk Customers**
- **Low-Risk Customers**

This segmentation enables businesses to prioritise retention efforts, personalise offers, and reduce customer turnover more efficiently.

##  Key Features

 - Developed a churn prediction model using Random Forest with high accuracy  
 - Segmented customers based on probability thresholds for targeted retention  
 - Identified major churn indicators and behavioural patterns through exploratory analysis  
 - Enabled real-time predictions through a **Flask-based web application**  
 - The user interface allows customer details input and instant churn risk output  

##  Business Impact

This solution empowers organisations to:

- Reduce churn with proactive interventions
- Improve customer satisfaction using personalised engagement
- Optimise marketing and retention budgets
- Strengthen long-term customer loyalty and revenue stability

By converting raw customer data into meaningful insights, the system supports decision-makers in identifying vulnerable customers **before** they churn, enabling timely and effective action.

##  Technology Stack

- **Machine Learning**: Random Forest (Scikit-learn)
- **Backend**: Flask
- **Languages**: Python
- **Visualization**: Matplotlib, Seaborn
- **Dataset**: Customer churn data (Telecom)


##  Future Enhancements

- Deploy as a cloud-hosted web service
- Add retention strategy recommendations based on customer persona
- Integrate feedback loop for model retraining


