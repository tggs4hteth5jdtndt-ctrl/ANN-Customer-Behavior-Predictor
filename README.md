# 🏦 Bank Customer Churn Prediction using ANN

An end-to-end Deep Learning project to predict the likelihood of customers leaving a bank (Churn) using **Artificial Neural Networks (ANN)**.

---

## 📊 About the Project
This project analyzes a banking dataset containing customer information (Credit Score, Geography, Gender, Balance, etc.) to classify whether a customer is likely to exit the bank or stay as an active member. 

It helps banking institutions identify "at-risk" customers and take proactive retention measures.

### 🛠️ Technologies Used
*   **Python** (Core language)
*   **TensorFlow/Keras** (For building and training the ANN)
*   **Scikit-Learn** (For Data Preprocessing, OneHotEncoding, and Scaling)
*   **Pandas & NumPy** (For Data Manipulation)

---

## 🧠 Model Architecture
The network is designed with a sequential architecture:
1.  **Input Layer:** Processes input features including encoded categorical variables.
2.  **Hidden Layers:** Two dense layers with **6 neurons** each, using the **ReLU** activation function.
3.  **Output Layer:** 1 neuron with **Sigmoid** activation to output the probability of churn (0 to 1).

---

## 📈 Model Configuration
*   **Optimizer:** Adam (Adaptive Moment Estimation)
*   **Loss Function:** Binary Cross-Entropy
*   **Epochs:** 100
*   **Batch Size:** 32

---

## 🚀 How to Run
1.  Open the notebook file in **Google Colab** or **Jupyter Notebook**.
2.  Upload the `Churn_Modelling.csv` dataset.
3.  Run all cells to execute data preprocessing, model training, and evaluation.
4.  **Interactive Mode:** The final section of the code allows you to input custom customer data to get a real-time churn prediction.

---

## 📄 License
This project is open-source and available for educational purposes.
