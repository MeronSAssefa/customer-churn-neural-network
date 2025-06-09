# Customer Churn Prediction using ANN

This project uses a neural network to predict customer churn — whether a customer is likely to stop using a service — based on their account and service usage data.

---

## 📊 Dataset

- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Size: 7,043 customers and 21 features
- Target column: `Churn` (Yes = customer left, No = stayed)
- Features include demographics, services signed up, billing info, and contract type

---

## 🔧 Project Steps

1. Load and explore the data
2. Clean missing values and fix data types
3. Encode categorical variables
4. Normalize numerical features
5. Build an ANN using TensorFlow/Keras
6. Train and evaluate the model
7. Visualize accuracy, loss, and confusion matrix

---

## 🛠️ Tools Used

- Python
- Pandas & NumPy for data handling
- Seaborn & Matplotlib for visualization
- Scikit-learn for preprocessing & metrics
- TensorFlow/Keras for the neural network

---

## ✅ Result

The trained model predicts churn with good accuracy and gives insight into which customers are likely to leave. This can help companies take action to improve customer retention.
