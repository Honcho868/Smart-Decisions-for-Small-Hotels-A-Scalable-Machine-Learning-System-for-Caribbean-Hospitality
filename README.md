# GROUP 4 Hotel Cancellation Prediction

## Description
This project is a comprehensive data analysis and machine learning solution focused on predicting hotel booking cancellations. The project combines advanced data analysis, machine learning, and customer segmentation techniques to help hotels better understand customers and predict booking cancellations to aid in improved marketing and promotion strategies.

## Key Features
1. Data Analysis and Preprocessing
- Comprehensive data cleaning and preprocessing pipeline
- Handling of missing values and data normalization
- Feature engineering for improved model performance

2. Cancellation Prediction
- Machine learning models to predict booking cancellations
- Implementation of various classification algorithms
- Model evaluation and performance metrics analysis

3. Customer Segmentation
- K-Prototypes clustering for customer segmentation
- Identification of distinct customer groups
- Analysis of cancellation patterns across different segments

4. Seasonal Analysis
- Analysis of booking and cancellation trends across different seasons
- Identification of peak booking and cancellation periods
- Time-series analysis of booking patterns

## Technical Stack

The project utilizes a robust set of Python libraries:
- Data manipulation: NumPy, Pandas
- Machine Learning: Scikit-learn, Kmodes
- Data Visualization: Matplotlib, Seaborn
- Statistical Analysis: Statsmodels, Scipy
- Model Interpretation: SHAP
- Handling Imbalanced Data: Imbalanced-learn

## Project Structure

```
GRP 4 Hotel Cancellation Prediction/
├── data/             # Data files
│   ├── raw/          # Raw data
│   └── processed/    # Processed data
├── Notebooks/        
│   ├── data_preprocessing.ipynb         # Notebook for cleaning, preprocessing, and preparing the raw data for analysis
│   ├── Cancellation_prediction.ipynb    # Notebook for predicting hotel cancellations
│   ├── K_Prototyping.ipynb              # Notebook for K-Prototypes clustering and customer segmentation
│   └── Seasonality_Trends.ipynb      # Notebook for analyzing seasonal trends in hotel bookings and cancellations
└── requirements.txt  # Project dependencies
```

## Setup

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebooks in the following sequence (not mandatory but just suggestive):
data_preprocessing.ipynb -> Seasonality_Trends.ipynb -> Cancellation_prediction.ipynb -> K_Prototyping.ipynb 
