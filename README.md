# Autism Screening Analysis Project

## Overview
This project analyzes an adult autism screening dataset to build a predictive model for autism spectrum disorder (ASD) diagnosis. The analysis includes data preprocessing, exploratory data analysis (EDA), and the implementation of a logistic regression model for classification.

## Dataset
The dataset is sourced from Kaggle: [Autism Screening Dataset for Adults](https://www.kaggle.com/datasets/andrewmvd/autism-screening-on-adults)

### Features Include:
- Demographic information (age, gender, ethnicity)
- Medical history (jaundice, autism in family)
- Geographic data (country of residence)
- Other relevant screening factors

## Requirements
- Python 3.x
- Required packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - plotly express

## Project Structure
1. **Data Cleaning**
   - Handling missing values
   - Age validation and outlier removal
   - Categorical data encoding

2. **Exploratory Data Analysis**
   - Distribution analysis of age
   - Country-wise autism cases visualization
   - Class distribution analysis

3. **Data Preprocessing**
   - Class balancing using downsampling
   - Feature scaling
   - Label encoding for categorical variables

4. **Model Development**
   - Logistic Regression implementation
   - Model evaluation using confusion matrix
   - Classification metrics analysis

## Key Findings
- The dataset was initially imbalanced and required downsampling of the majority class
- Logistic Regression model shows promising results in predicting ASD cases
- Detailed performance metrics are available in the confusion matrix and classification report

## Model Performance
The Logistic Regression model's performance metrics include:
- Confusion Matrix visualization
- Detailed classification report with precision, recall, and F1-score

## Future Improvements
- Implementation of additional machine learning models
- Feature importance analysis
- Cross-validation implementation
- Hyperparameter tuning

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
