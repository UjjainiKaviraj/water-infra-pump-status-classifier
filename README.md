# Water Pump Functionality Prediction

![Water Pump Infrastructure Optimization](images/project-image.png) 
*Machine learning models for predicting water pump functionality*

## Project Overview
Develops machine learning models to predict operational status of rural water pumps (functional/non-functional) based on physical, geographical, and socio-economic attributes. Goal is to optimize maintenance schedules and resource allocation for water infrastructure in developing regions.

## Key Features
- **Data Analysis**: Examined 5,000 water pump records with 11 predictive features
- **Model Comparison**: Implemented and tested 6 machine learning algorithms
- **Best Model**: Voting Ensemble (XGBoost + Gradient Boosting) achieved 74.6% accuracy
- **Key Insights**: Identified critical predictive factors:
  - Water source type
  - Pump age
  - Distance to nearest town
  - Water quality

## Technical Implementation
### Data Preparation
- Handled missing values:
  - Numerical columns: KNNImputer
  - Categorical columns: SimpleImputer (mode strategy)
- Removed irrelevant columns (GPS coordinates, Water Pump ID)
- Transformed GPS coordinates into latitude/longitude
- Retained meaningful outliers

### Models Compared
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 73.5% |
| Random Forest | 74.2% |
| XGBoost | 74.2% |
| Gradient Boosting | 74.5% |
| Neural Network | 72.7% |
| **Voting Ensemble (XGBoost + GB)** | **74.6%** |
