# ChurnScope — Customer Churn Prediction

ChurnScope is a machine learning project that explores customer churn patterns and builds predictive classification models to identify customers who are likely to discontinue a telecom service.

The project uses the IBM Telco Customer Churn dataset and investigates how customer demographics, service subscriptions, account information, and billing patterns relate to churn.

## 🎯 Project Objectives

- Explore customer data to understand churn patterns.
- Perform data cleaning and preprocessing.
- Identify important factors associated with customer churn.
- Build and evaluate multiple machine learning classification models.
- Compare model performance using classification metrics.

## 📊 Dataset

**Dataset:** IBM Telco Customer Churn

The dataset contains customer information, including:

- Demographic details
- Customer tenure
- Internet and phone services
- Contract and payment methods
- Monthly and total charges
- Customer churn status

**Target variable:** `Churn`

The target indicates whether a customer has discontinued the service.

## 🔍 Project Workflow

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature encoding and transformation
5. Model training and prediction
6. Model evaluation and comparison

## 🤖 Machine Learning Models

Three classification algorithms are explored:

| Model | Description |
|---|---|
| Logistic Regression | Baseline classification model |
| Decision Tree | Tree-based classification model |
| Random Forest | Ensemble learning model |

## 📈 Model Evaluation

The models are evaluated using classification performance metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The comparison helps examine how different classification algorithms perform on the customer churn prediction task.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📁 Repository Structure

```text
ChurnScope-Customer-Churn-Prediction/
│
├── Churn_Analysis_Using_Logistic_Regression.ipynb
├── Churn_Analysis_Using_Decision_tree_classifier.ipynb
├── Churn_Analysis_Using_Random_Forest.ipynb
├── customer_data.csv
├── README.md
└── LICENSE
```

## 🚀 Future Improvements

- Develop an interactive customer churn analytics dashboard.
- Compare model performance through visualizations.
- Integrate the trained models into a prediction API.
- Build a web application for customer churn analysis and prediction.

## 📄 License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Machine learning model development and evaluation completed; dashboard and application integration are planned future improvements.
