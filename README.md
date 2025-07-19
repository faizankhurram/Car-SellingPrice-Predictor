# 📊 Car Selling Price Predictor

This is a complete machine learning project that predicts the **selling price of used cars** based on various features such as year, present price, kilometers driven, fuel type, and more. The model is trained and evaluated using a real-world dataset sourced from Kaggle.

---

## 🧠 Project Type

- **Type:** Regression  
- **Best Model:** Linear Regression  
- **R² Score:** ~0.86 on the test set

---

## 📁 Dataset

- **Source:** [Kaggle - Vehicle Dataset from CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)  
- **Description:** Contains information about second-hand cars, including features like manufacturing year, present price, kilometers driven, fuel type, seller type, transmission, and ownership history.

---

## 🔧 Tools & Technologies

- Python 3  
- pandas  
- matplotlib  
- scikit-learn  
- Jupyter Notebook  
- joblib (for model serialization)

---

## 🔄 Workflow

This project follows a complete end-to-end machine learning pipeline:

1. Data loading and exploration  
2. Feature engineering and visualization  
3. Handling missing values and data cleaning  
4. One-hot encoding of categorical features  
5. Train-test split  
6. Model training and performance evaluation  
7. Hyperparameter tuning  
8. Best model selection and serialization

---

## 📈 Final Result

The **Linear Regression** model achieved an **R² score of approximately 0.86**, indicating strong predictive performance on unseen data.

---


## 📌 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/faizankhurram/Car-SellingPrice-Predictor.git
2. **Navigate to the folder**
   ```bash
   cd Car-SellingPrice-Predictor
3. **Open Jupyter Notebook**
   ```bash
   jupyter notebook car_price_prediction.ipynb
