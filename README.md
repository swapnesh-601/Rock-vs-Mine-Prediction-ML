# 🪨 Rock vs Mine Prediction using Machine Learning

## 📌 Project Overview

This project implements a Machine Learning classification model capable of distinguishing between **Rocks (R)** and **Mines (M)** using sonar signal data.

The model is built using **Logistic Regression**, a supervised machine learning algorithm designed for binary classification tasks.

The project demonstrates a complete Machine Learning workflow, including:

* Data Loading
* Data Exploration
* Data Preprocessing
* Feature & Target Separation
* Train-Test Split
* Model Training
* Model Evaluation
* Prediction on New Data

This project is an excellent beginner-friendly implementation of a binary classification problem using Python and Scikit-learn.

---

## 🎯 Problem Statement

Sonar systems transmit sound waves underwater. These waves reflect back after striking an object. Based on the reflected sonar signals, the objective is to determine whether the detected object is a:

* **Rock (R)**
* **Mine (M)**

A Logistic Regression model is trained to accurately classify these underwater objects.

---

## 📂 Dataset Information

**Dataset Name:** Sonar Dataset

**Features:** 60 numerical features

**Target Variable:**

* **R** → Rock
* **M** → Mine

Each feature represents the energy of sonar signals reflected at different frequencies.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook

---

## 🤖 Machine Learning Algorithm

### Logistic Regression

### Why Logistic Regression?

* Suitable for Binary Classification
* Fast and Efficient
* Easy to Interpret
* Excellent Baseline Model
* Performs well on linearly separable data

---

## 📊 Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Explore and Analyze the Data
4. Separate Features and Target Variable
5. Split the Dataset into Training and Testing Sets
6. Train the Logistic Regression Model
7. Evaluate Model Performance
8. Predict Whether the Object is Rock or Mine

---

## 📈 Model Evaluation

The model performance is evaluated using:

* **Accuracy Score**

The model is evaluated on both:

* Training Dataset
* Testing Dataset

---

## 📁 Project Structure

```text
Rock-vs-Mine-Prediction-ML/
│
├── 📄 README.md                 # Project documentation
├── 📓 RockvsMine_Prediction.ipynb   # Jupyter Notebook
├── 📊 Sonar data.csv            # Dataset
├── 📋 requirements.txt          # Python dependencies
├── 📜 LICENSE                   # MIT License
└── 🚫 .gitignore                # Git ignore rules
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Rock-vs-Mine-Prediction-ML.git
```

Move into the project directory

```bash
cd Rock-vs-Mine-Prediction-ML
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
RockvsMine_Prediction.ipynb
```

Run all the cells to train the model and make predictions.

---

## 📚 Learning Outcomes

By completing this project, you will gain hands-on experience with:

* Binary Classification
* Logistic Regression
* Data Preprocessing
* Train-Test Split
* Model Evaluation
* Prediction on New Data
* Machine Learning Workflow using Scikit-learn

---

## 🔮 Future Improvements

* Feature Scaling
* Cross Validation
* Hyperparameter Tuning
* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier
* Deploy the model using Streamlit or Flask

---

## 🙏 Acknowledgements

This project was developed as part of my Machine Learning learning journey.

Special thanks to **Siddhardhan** for the excellent tutorial and detailed explanation that inspired this implementation.

**📺 YouTube Channel:** Siddhardhan

**🎥 Tutorial Video:**
https://youtu.be/fiz1ORTBGpY?si=HjO9OQmnJ6mDJcn8

---

## 👨‍💻 Author

**Swapnesh Das**

**B.Tech CSE Graduate**

---

⭐ **If you found this project helpful, consider giving it a Star!**
