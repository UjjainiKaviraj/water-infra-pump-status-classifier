Water Pump Functionality Prediction

Project Overview
This project develops machine learning models to predict the operational status of rural water pumps (functional/non-functional) based on physical, geographical, and socio-economic attributes. The goal is to optimize maintenance schedules and resource allocation for water infrastructure in developing regions.

Key Features
Data Analysis: Examined 5,000 water pump records with 11 predictive features

Machine Learning Models: Implemented and compared 6 different algorithms

Best Performing Model: Voting Ensemble (XGBoost + Gradient Boosting) achieved 74.6% accuracy

Key Insights: Identified water source type, pump age, and distance to nearest town as critical predictive factors

Technical Implementation
Data Preparation
Handled missing values using KNNImputer (numerical) and SimpleImputer (categorical)

Removed irrelevant columns (GPS, Water Pump ID)

Transformed GPS coordinates into latitude/longitude

Retained meaningful outliers

Models Compared
Logistic Regression (73.5% accuracy)

Random Forest (74.2% accuracy)

XGBoost (74.2% accuracy)

Gradient Boosting (74.5% accuracy)

Neural Network (72.7% accuracy)

Voting Ensemble (74.6% accuracy)

Repository Structure
text
/water-pump-optimization
│── /data                   # Contains project datasets
│── /notebooks              # Jupyter notebooks with analysis
│── /reports                # Project documentation and final report
│── /src                    # Source code and scripts
│── README.md               # This file
│── requirements.txt        # Python dependencies
Getting Started
Clone the repository

Install dependencies: pip install -r requirements.txt

Run Jupyter notebooks in /notebooks to reproduce analysis

Team
Ujjaini Kaviraj

Mihir Girish Sali

Sindhuja Jupudi

Richard Freeman

Acknowledgments
Special thanks to Professor Javier Rubio-Herrero for guidance and support throughout this project.

For the repository image, I recommend using an AI-generated visualization that combines:

A rural water pump as the central element

Data visualization elements (graphs, charts) surrounding it

Machine learning symbols (decision trees, neural networks)

A color scheme of blues (for water) and greens (for infrastructure)
