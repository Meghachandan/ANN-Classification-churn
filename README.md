# ANN-Classification-churn
#  ANN Classification - Customer Churn Prediction

A deep learning project that predicts whether a customer is likely to leave a bank (customer churn) using an **Artificial Neural Network (ANN)** built with **TensorFlow** and **Keras**. The application is deployed with **Streamlit**, allowing users to input customer information and receive real-time churn predictions.

---

## Project Overview

Customer churn prediction is a binary classification problem where the goal is to identify customers who are likely to discontinue using a company's services. This project leverages an Artificial Neural Network (ANN) to analyze customer attributes and predict whether a customer will **stay** or **leave** the bank.

---

## Features

- Customer churn prediction using an ANN
- Interactive Streamlit web application
- Data preprocessing with feature scaling and encoding
- Real-time prediction based on user inputs
- Trained using TensorFlow and Keras
- Clean and user-friendly interface

---

## Tech Stack

- **Python**
- **TensorFlow**
- **Keras**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

##  Project Structure

```
ANN-Classification-Churn-Prediction/
│
├── main.py                 # Streamlit application
├── experiments.ipynb       # Model training notebook
├── model.h5                # Trained ANN model
├── scaler.pkl              # StandardScaler object
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
├── runtime.txt
├── README.md
└── data/
    └── Churn_Modelling.csv
```

---

##  Dataset

The project uses the **Churn Modelling Dataset**, which contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

**Target Variable**

- **Exited**
  - 1 → Customer will leave
  - 0 → Customer will stay

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/ANN-Classification-Churn-Prediction.git
cd ANN-Classification-Churn-Prediction
```

### Create a virtual environment

```bash
python -m venv tfenv
```

### Activate the environment

**Windows**

```bash
tfenv\Scripts\activate
```

**Linux / macOS**

```bash
source tfenv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run main.py
```

The application will open automatically in your browser.

---

## Model Architecture

- Input Layer
- Hidden Dense Layer (ReLU)
- Hidden Dense Layer (ReLU)
- Output Layer (Sigmoid)

Loss Function:

- Binary Crossentropy

Optimizer:

- Adam

Evaluation Metric:

- Accuracy

---

##  Workflow

1. Load the customer dataset
2. Preprocess the data
3. Encode categorical features
4. Scale numerical features
5. Train the ANN model
6. Save the trained model and preprocessing objects
7. Deploy using Streamlit
8. Predict customer churn

---

## Application

The Streamlit application allows users to enter customer details and instantly predicts whether the customer is likely to churn.

---

## Future Improvements

- Hyperparameter tuning
- Model explainability using SHAP
- Docker deployment
- Cloud deployment
- Support for batch predictions

---

##  Author

**Megha Chandan**

# 🧠 ANN Classification - Customer Churn Prediction

A deep learning project that predicts whether a customer is likely to leave a bank (customer churn) using an **Artificial Neural Network (ANN)** built with **TensorFlow** and **Keras**. The application is deployed with **Streamlit**, allowing users to input customer information and receive real-time churn predictions.

---

## 📌 Project Overview

Customer churn prediction is a binary classification problem where the goal is to identify customers who are likely to discontinue using a company's services. This project leverages an Artificial Neural Network (ANN) to analyze customer attributes and predict whether a customer will **stay** or **leave** the bank.

---

## 🚀 Features

- Customer churn prediction using an ANN
- Interactive Streamlit web application
- Data preprocessing with feature scaling and encoding
- Real-time prediction based on user inputs
- Trained using TensorFlow and Keras
- Clean and user-friendly interface

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow**
- **Keras**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 📂 Project Structure

```
ANN-Classification-Churn-Prediction/
│
├── main.py                 # Streamlit application
├── experiments.ipynb       # Model training notebook
├── model.h5                # Trained ANN model
├── scaler.pkl              # StandardScaler object
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
├── runtime.txt
├── README.md
└── data/
    └── Churn_Modelling.csv
```

---

## 📊 Dataset

The project uses the **Churn Modelling Dataset**, which contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

**Target Variable**

- **Exited**
  - 1 → Customer will leave
  - 0 → Customer will stay

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/ANN-Classification-Churn-Prediction.git
cd ANN-Classification-Churn-Prediction
```

### Create a virtual environment

```bash
python -m venv tfenv
```

### Activate the environment

**Windows**

```bash
tfenv\Scripts\activate
```

**Linux / macOS**

```bash
source tfenv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

The application will open automatically in your browser.

---

## 🧠 Model Architecture

- Input Layer
- Hidden Dense Layer (ReLU)
- Hidden Dense Layer (ReLU)
- Output Layer (Sigmoid)

Loss Function:

- Binary Crossentropy

Optimizer:

- Adam

Evaluation Metric:

- Accuracy

---

## 📈 Workflow

1. Load the customer dataset
2. Preprocess the data
3. Encode categorical features
4. Scale numerical features
5. Train the ANN model
6. Save the trained model and preprocessing objects
7. Deploy using Streamlit
8. Predict customer churn

---

## 📷 Application

The Streamlit application allows users to enter customer details and instantly predicts whether the customer is likely to churn.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Model explainability using SHAP
- Docker deployment
- Cloud deployment
- Support for batch predictions

---

## 👨‍💻 Author

**Megha Chandan**
https://github.com/Meghachandan

---

## 📄 License

This project is licensed under the MIT License.

---

If you found this project helpful, consider giving it a star on GitHub!

---

##  License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
