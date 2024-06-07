# GDPR Customer Request Prediction Model - Ride-hailing company

## 1. Introduction
This project aims to predict whether customer service requests are related to GDPR compliance using machine learning models. This capability can help organizations respond appropriately to privacy-related inquiries, ensuring compliance with data protection laws.

## 2. Project Description
**Objective**: Develop a predictive model that can classify customer service requests based on whether they pertain to GDPR issues.

**Models Utilized**:
- Random Forest
- XGBoost

**Data**: The dataset includes customer requests in a ride-hailing company with fields like Request ID, Request Type, Request Description, and was randomly created using LLM.

## 3. System Architecture
### Data Preprocessing
- Cleansing and vectorizing text data using TF-IDF.

### Model Training
- Training several machine learning models and selecting the best performer based on evaluation metrics.

### Prediction Module
- Deploying the selected model to predict the category of new requests.
