# Data Analysis and Machine Learning for Educational Data

This project demonstrates a comprehensive approach to data cleaning, feature engineering, and machine learning using a dataset related to educational performance. The workflow includes data preprocessing, outlier detection, feature importance evaluation, and model training using various techniques.

## Installation

Before running the code, install the required Python packages:

```bash
pip install category_encoders shap xgboost
```

## Project Overview

1. **Data Preprocessing**
   - Load and inspect data from `Expanded_data_with_more_features.csv`.
   - Drop duplicates and handle missing values.
   - Create new features and clean outliers.
   - Save cleaned data and outliers to CSV files.

2. **Feature Engineering**
   - One-hot encode categorical features.
   - Perform feature importance analysis using Random Forest.

3. **Model Training and Evaluation**
   - Train and evaluate models using Random Forest Classifier and XGBoost Classifier.
   - Perform logistic regression with feature scaling and encoding.
   - Evaluate models using accuracy scores and feature importance plots.

4. **Outlier Analysis**
   - Classify students based on performance and analyze outliers.
   - Build and evaluate models separately for outlier and non-outlier data.

## Data Visualization

For a visual representation of the data and analysis, please refer to the Tableau dashboard linked below:

[Interactive Data Visualization Dashboard](https://public.tableau.com/views/Midproject_17129736632710/Story1?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For any questions or issues, please open an issue or contact me directly.
