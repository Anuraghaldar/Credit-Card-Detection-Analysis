# Credit Card Fraud Detection

![](https://www.xenonstack.com/hubfs/xenonstack-credit-card-fraud-detection.png)

The goal of this project is to detect fraudulent transactions from a dataset containing credit card transactions. This is a binary classification problem where the objective is to classify transactions as either fraudulent or non-fraudulent.
Thus the file [`Credit_Card_detection_analysis.ipynb`](https://github.com/Anuraghaldar/Credit-Card-Detection-Analysis/blob/main/Credit_Card_detection_analysis.ipynb) has the analysis of the Credit Card Fraud Detection.
## Flow Steps for Analysis

- **Import Libraries**:  
  The necessary libraries, such as `pandas`, `numpy`, `seaborn`, `matplotlib`, and `scikit-learn`, are imported for data manipulation, visualization, and modeling.

- **Load Data**:  
  The dataset [`creditcard.csv`](https://github.com/Anuraghaldar/Credit-Card-Detection-Analysis/blob/main/creditcard.csv) is read into a pandas DataFrame.

- **Data Exploration**:  
  Initial exploration of the dataset, such as checking for missing values and understanding the distribution of features.

- **Data Analysis**:  
  Analysis of the dataset, including checking for class imbalance between fraudulent and non-fraudulent transactions.

- **Data Preprocessing**:  
  Data is preprocessed, which may include scaling features, handling missing values, and any other required transformations.

- **Splitting Data**:  
  The dataset is split into training and testing sets to evaluate the model's performance.

- **Model Building**:  
  A Logistic Regression model is trained on the training data to predict fraudulent transactions.

- **Model Evaluation**:  
  The model is evaluated using metrics such as accuracy, precision, recall, and a classification report to understand its performance.

- **Conclusion**:  
  The final results and conclusions are summarized based on the model's performance.
