# phishing-url-detection-code
Machine learning-based phishing URL detection system code

# phishing-url-detector
Machine learning-based phishing URL detection system

This project applies machine learning algorithms to detect phishing URLs using lexical features extracted from publicly available datasets.

## Files
- 'InitialDataset.ipynb' - initial preprocessing for initial flawed dataset
- 'Final_dataset.ipynb` – preprocesses the raw datasets "url-dataset.csv" and "phishing_url.csv".
- 'RF.ipynb' – Random Forest model used for experimenting with features. many test features were added and removed throughout the project for clarity and quicker computing times.
- 'RF30.ipynb' – Version of Random Forest testing with the top 30 features.
- `SVM.ipynb' – Support Vector Machine implementation for Model Comparison.
- 'DecisionTree.ipynb' – Decision Tree testing for Model comparison.
- 'Correlation.ipynb' – Visualises correlation between features to assist in feature reduction.
- 'NormaliseFeatures.ipynb' - Normalisation of features for SVM
