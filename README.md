
# Bank Customer Churn Prediction

This project predicts whether a bank customer will churn (leave the bank) using a machine learning model. The project uses Support Vector Machines (SVM) as the main classifier and handles class imbalance using random undersampling (RUS) and oversampling (ROS).

## **Features**
- Preprocessing data: Encoding categorical variables, feature scaling, and creating new features.
- Handling imbalanced data: Applied RUS and ROS techniques.
- Machine Learning model: SVM with hyperparameter tuning using GridSearchCV.
- Performance evaluation with confusion matrices and classification reports.

## **Technologies Used**
- Python
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn

## **Dataset**
The dataset is sourced from [GitHub YBI Foundation Dataset](https://github.com/YBI-Foundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv).

## **How to Run**
1. Clone this repository to your local machine.
   ```bash
   https://github.com/Vishnuvardhangupthajavvaji/Bank_Customer_Churn_Prediction.git
   
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Navigate to the project directory:
   ```bash
   cd Bank_Customer_Churn_Model

4. Run the Bank_Customer_Churn_Model.ipynb to train the model and make predictions
