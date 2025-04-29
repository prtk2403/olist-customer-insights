# Olist E-commerce Customer Insights Analysis

Authored by - [Pratheek Nistala](https://github.com/prtk2403)
## Overview
This project analyzes the Brazilian e-commerce public dataset by Olist, focusing on customer behavior, satisfaction, and value prediction. The dataset contains information about 100,000 orders made between 2016 and 2018 across multiple marketplaces in Brazil, providing comprehensive insights into various aspects of e-commerce operations.

## Dataset Description
The dataset includes detailed information about:
- Orders and their statuses
- Pricing and payment information
- Shipping performance
- Customer locations and demographics
- Product attributes
- Customer reviews and satisfaction scores
- Geolocation data mapping Brazilian zip codes to coordinates

Data Source: 
- [Olist Brazilian E-commerce Dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce)
- [Olist Marketing Funnel Dataset](https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist/data)

## Project Structure

```
.
├── preprocessing_analysis     
│   ├── geolocation_analysis.ipynb                        #Detailed analysis related to geolocation of a customer
│   └── overall_data_analysis.ipynb                       #Data analysis from all the files to better understand data
|   └── understanding_metrics.ipynb                       #Metrics like new customer vs old customers
|
├── predictions                   
│   ├── customer_lifetime_value_prediction.ipynb          #Predicting which customer is most important to act accordingly  
│   └──predicting_customer_satisfaction                   #Customer review score prediction
|
├── customer_segmentation.ipynb                           #Dividing customers as active, non active using RFM matrix
│           
└── README.md
```
---

## Analysis Components

### 1. Data Preprocessing and Analysis
- **Geolocation Analysis**: Explores customer geographical distribution and its impact on business metrics
- **Overall Data Analysis**: Comprehensive analysis of all available datasets to understand patterns and relationships
- **Metrics Understanding**: Focuses on key customer metrics including customer acquisition and retention

### 2. Predictive Models
- **Customer Lifetime Value Prediction**: 
  - Identifies high-value customers
  - Predicts future customer value
  - Helps in customer prioritization and targeting

- **Customer Satisfaction Prediction**:
  - Predicts customer review scores
  - Identifies factors influencing customer satisfaction
  - Helps in proactive customer experience management

### 3. Customer Segmentation
- Implements RFM (Recency, Frequency, Monetary) analysis
- Segments customers based on their purchasing behavior
- Helps in targeted marketing and customer relationship management

## Technologies Used
- Python
- Pandas & NumPy for data manipulation
- Matplotlib, Seaborn, and Plotly for visualization
- Scikit-learn for machine learning models
- XGBoost for advanced predictive modeling

## Key Insights
The analysis provides insights into:
- Customer purchasing patterns
- Geographical distribution of sales
- Factors affecting customer satisfaction
- Customer lifetime value predictions
- Effective customer segmentation strategies

## Usage
Each notebook is self-contained and includes detailed comments and explanations. To use this project:
1. Clone the repository
2. Install required dependencies
3. Run the notebooks in the suggested order:
   - Start with preprocessing notebooks
   - Move to analysis notebooks
   - Finally, explore prediction models

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Plotly
- Matplotlib
- Seaborn

