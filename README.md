# ML_Project-Credit_Card_Fraud_Detection

This project tackles credit card fraud detection using Logistic Regression, a powerful machine learning technique. It analyzes historical transaction data to identify patterns that distinguish legitimate transactions from fraudulent ones.

### Data:
This directory stores the credit card transaction data in CSV format. It's assumed the dataset contains attributes like:

- Time
- v1
- v2
- ....
- v28
- Amount
- Class (0 for legit, 1 for fraud)

**Note:** You might need to adjust this list based on your specific dataset.

### Notebooks:
This directory contains the Jupyter Notebook (`credit_card_fraud_detection.ipynb`) for data exploration, preprocessing, model training, evaluation, and visualization.

### Running the Project

The Jupyter Notebook (`credit_card_fraud_detection.ipynb`) guides you through the following steps:

1. **Data Loading and Exploration:** 
    - Loads the transaction data.
    - Explores data distribution, identifying missing values and data types.
2. **Data Preprocessing:**
    - Handles missing values.
    - Encodes categorical variables (e.g., location) into numerical representations.
    - Prepares features for model training (potential scaling).
3. **Model Training with Logistic Regression:**
    - Trains the model, potentially tuning hyperparameters.
4. **Model Evaluation:**
    - Evaluates model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Visualization of Results:**
    - Explores feature importance and analyzes the confusion matrix.

### Addressing Imbalance

- Credit card fraud data is often imbalanced (more legitimate transactions than fraudulent ones). The notebook might address this by:
    - Undersampling the majority class (legitimate transactions).
    - Oversampling the minority class (fraudulent transactions).
    - Using cost-sensitive learning that prioritizes correctly classifying fraudulent transactions.

### Customization

- Modify the Jupyter Notebook to:
    - Experiment with different hyperparameters for Logistic Regression.
    - Try other classification algorithms for comparison (e.g., Random Forest, Support Vector Machines).
    - Explore advanced techniques like SMOTE (handling imbalanced data).


### Further Contributions

- Extend this project by:
    - Incorporating additional transaction features (e.g., device used, IP address).
    - Implementing real-time fraud detection using the trained model.
    - Integrating the model into a fraud detection system for a financial institution.

By leveraging Logistic Regression, we can analyze historical credit card transactions and potentially build a model to identify fraudulent activities. This project provides a foundation for further exploration in credit card fraud detection and machine learning applications.
