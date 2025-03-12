# Powerlifting Success Prediction using Machine Learning

## Overview
This project analyzes real-world powerlifting data from OpenPowerlifting to predict whether an athlete’s lift attempt will be successful or failed using various machine learning models. The goal is to identify key factors affecting lift success and build an optimized predictive model.

## Dataset

- **Data Source:** [openpowerlifting-2024-01-06-4c732975.csv on Kaggle](https://www.kaggle.com/datasets/open-powerlifting/powerlifting-database/data?select=openpowerlifting-2024-01-06-4c732975.csv)
- Includes lifter details (weight class, sex, equipment type), lift type (squat, bench press, deadlift), and attempt outcomes.
- Preprocessing includes handling missing values, encoding categorical variables, and normalizing numerical features.

## Tech Stack & Tools
- Python (Pandas, NumPy, Scikit-learn)
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning Models:** Logistic Regression, Random Forest, Decision Tree, XGBoost, ANN

## Exploratory Data Analysis (EDA)
- Visualized feature distributions and correlations.
- Analyzed the impact of bodyweight, attempt number, lift type, and equipment on success probability.
- Identified and handled imbalanced class distributions

## Key Challenges & Improvements
- Handling imbalanced success/failure classes.
- Feature selection to improve model interpretability.
- Hyperparameter tuning for better generalization.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/chandwaniarnav/powerlifting-success-prediction.git
    ```

2. Install required Python libraries:

    ```bash
    pip install numpy pandas matplotlib seaborn sklearn tensorflow imblearn xgboost
    ```
3. Run the Jupyter Notebook to train the model
```bash
jupyter notebook
```
## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
