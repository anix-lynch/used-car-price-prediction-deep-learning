# 📊 Used Car Price Prediction with Deep Learning

🚗 In this project, we explore used car sales data to predict the price a customer might spend on a used car using a deep learning model built with TensorFlow. We'll uncover patterns in the data through visualizations and construct a deep learning model to make accurate predictions!

---

## 🛠 Technologies Used

- **Python** 🐍
- **Pandas** 🐼
- **Seaborn** 📊
- **TensorFlow** 🤖

---

## 📈 Project Overview

1. **Exploring the Data**:  
   We start by exploring the sales data of used cars using the visualization power of **seaborn**. From correlations to distributions, we uncover the hidden trends that influence used car prices.

2. **Data Preprocessing**:  
   - Handle missing values.
   - Convert categorical variables into numerical representations.  
   This ensures the data is clean and ready for the deep learning model!

3. **Building the Model**:  
   We create a deep learning model using **TensorFlow/Keras**:
   - The model consists of **Dense layers** using suitable activation functions.
   - The **output layer** uses a **linear activation function** to predict continuous car prices.

4. **Model Compilation & Training**:  
   The model is compiled using:
   - **Optimizer**: To fine-tune the model during training.
   - **Loss Function**: Mean squared error (MSE) to minimize prediction errors.
   - **Metric**: Mean absolute error (MAE) to evaluate performance.
   
   We monitor the training process to avoid overfitting or underfitting!

5. **Model Evaluation**:  
   After training, we test the model on unseen data to predict the sale prices. We'll use the **R2 score** to evaluate how well the model performs in predicting real-world car prices.

---

## 📊 Visualizations & Insights:
Using **seaborn**, we create visualizations that provide valuable insights into the data, such as:
   - Price distribution of cars based on attributes like **brand**, **model**, and **mileage**.
   - Correlations between different features like **engine size**, **year of manufacture**, and **fuel type**.

---

## 🏁 Key Features:
- Preprocessing real-world data for deep learning.
- Building a sequential model to predict car prices.
- Data visualization for understanding key features.
- Model evaluation using R2 score for accuracy.

---

