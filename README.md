# PredX - Multiple Disease Prediction System

## 🚀 Overview
The **Multiple Disease Prediction System** is a web-based application built with **Streamlit** that allows users to predict the likelihood of having **Diabetes, Heart Disease, or Parkinson’s Disease** based on user input parameters. The system utilizes pre-trained machine learning models saved in `.sav` format.

## 🏗️ Features
- **Predicts three diseases:** Diabetes, Heart Disease, and Parkinson's.
- **Interactive UI** using Streamlit.
- **Fast & Efficient Predictions** using trained ML models.
- **User-friendly Interface** for easy data input and result visualization.

## 📂 Project Structure
```
📂 Multiple-Disease-Prediction
│── 📂 saved_models
│    ├── diabetes_model.sav
│    ├── heart_disease_model.sav
│    ├── parkinsons_model.sav
│── app.py
│── requirements.txt
│── README.md
```

## 🛠️ Installation & Setup
### Prerequisites
Ensure you have **Python 3.7+** installed. You also need to install **Streamlit** and required dependencies.

### Clone the Repository
```
git clone https://github.com/RJ-Hossan/PredX.git
cd PredX
```

### Install Dependencies
```
pip install -r requirements.txt
```

### Run the Streamlit App
```
streamlit run app.py
```

## 📌 Technologies Used
- **Python**
- **Streamlit** (for UI)
- **Scikit-learn** (for ML models)
- **Pickle** (for model storage & loading)

## ✨ Future Enhancements
- Adding more diseases for prediction.
- Enhancing UI with better visualization.
- Deploying the application on **AWS/GCP/Heroku**.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.
