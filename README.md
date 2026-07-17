# 📈 Stock Price Prediction using Machine Learning

## 📌 Project Overview

Stock price prediction is an important application of Machine Learning in the financial domain. This project predicts the closing price of Tesla stock using historical stock market data and a Linear Regression model.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature selection, model training, prediction, and performance evaluation.

---

## 🎯 Objective

The objective of this project is to develop a Machine Learning model that predicts Tesla's stock closing price based on historical stock market features.

---

## 📂 Dataset

**Dataset:** Tesla Stock Price Dataset (2000–2025)

The dataset contains the following features:

- Date
- Open Price
- High Price
- Low Price
- Close Price (Target)
- Volume

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Project Workflow

1. Import required libraries
2. Load the dataset
3. Clean and preprocess the data
4. Select input features and target variable
5. Split the dataset into training and testing sets
6. Train a Linear Regression model
7. Predict stock closing prices
8. Evaluate model performance
9. Compare actual and predicted values
10. Visualize prediction results

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Linear Regression

---

## 📊 Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Results

| Metric | Value |
|---------|--------|
| Mean Absolute Error (MAE) | 0.8103 |
| Mean Squared Error (MSE) | 3.5294 |
| R² Score | 0.9997 |

The high R² score indicates that the model accurately predicts the closing stock price using the selected features.

---

## 📁 Project Structure

```
Stock-Price-Prediction/
│
├── Stock_Price_Prediction.ipynb
├── Tesla.csv
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Stock-Price-Prediction.git
```

2. Open the notebook using Google Colab or Jupyter Notebook.

3. Upload the Tesla dataset.

4. Run all cells sequentially.

---

## 📌 Conclusion

A Linear Regression model was successfully developed to predict Tesla stock closing prices using historical stock market data. The model achieved a high R² score of **0.9997**, indicating excellent predictive performance. This project demonstrates how Machine Learning techniques can be applied to financial data for stock price prediction.

---

## 👨‍💻 Author

**Sourav Krishna**

B.Tech Computer Science & Engineering (Artificial Intelligence)

SCMS School of Engineering and Technology

Kerala, India

---

## ⭐ Acknowledgements

- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Kaggle (Dataset Source)
