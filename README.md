# User-Churn-Prediction

### Overview
The project is focused to identify the potential customer who will stop use the service in the future based on the the user behavior and basic information dataset. The project incorporate different supervised learning models such as logistic regression, random forest, k-nearest neighbors, SVM to predict the likelihood for each user, as well as to identify the feature importance to help business improve the service and operation.

# Proccess
**Dataset Exploration**: dataset cleaning, feature understanding

**Feature Preparation**: categorical features to dummy variables, normalization/standardization

**Model Training**: optimal parameters by grid search, model setup, cross validation

**Feature Importance**: Deploy logistic regress, RFE, random forest to identify the top features.

# Reflection

- The random forest model set up in the project with 0.92 precision and 0.71 recall in the process.
- The most important features identified are total_day_minutes, num_customer_service_calls,intl_plan,voice_mail_plan.

Based on the features identified, company could invent some plans on international and voice mail, as well as dive deep into the customer service section to identify why the number of customer service would bring people stopping use the company services.
