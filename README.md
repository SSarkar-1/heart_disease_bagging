# Bagging and Ensemble Methods for Heart Disease Prediction

This project demonstrates the use of ensemble learning techniques, including Bagging with SVM and Decision Trees, as well as Random Forests, for predicting heart disease from a real-world dataset. The notebook covers data preprocessing, outlier removal, feature encoding, scaling, model training, hyperparameter tuning with GridSearchCV, and model evaluation.

## Features

- Loads and explores the heart disease dataset
- Removes outliers using Z-score
- Encodes categorical and ordinal features
- Scales features with MinMaxScaler
- Implements and compares:
  - Standalone SVM
  - Bagged SVM
  - Bagged Decision Trees
  - Random Forest
- Hyperparameter tuning with GridSearchCV
- Model evaluation with cross-validation and OOB score

## Requirements

- Python 3.x
- pandas
- scikit-learn
- scipy

Install dependencies with:
```bash
pip install pandas scikit-learn scipy
```

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-bagging.git
    cd heart-disease-bagging
    ```
2. Make sure `heart.csv` is in the project directory.
3. Open `Bagging_Heart.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells to follow the workflow and see results.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
