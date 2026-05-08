# Advertisements-Regression
# 📈 Advertising Sales Prediction App

A simple Machine Learning web application built with **Streamlit** that predicts product sales based on advertising budgets spent on **TV, Radio, and Newspaper** marketing.

## 🚀 Project Overview

This project uses a **Linear Regression Model** trained on the Advertising dataset to estimate sales based on advertising investments.

Users can interact with the app using sliders to enter budgets and instantly get predicted sales.

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

## 📂 Project Structure

```bash
├── app.py                  # Streamlit Web App
├── train.py               # Model Training Script
├── advertising_model.pkl  # Saved Model + Scaler
├── Advertising.csv        # Dataset
└── README.md              # Project Documentation
## 📊 Features

✅ Predict sales based on advertising budgets
✅ Interactive sliders for user input
✅ Real-time predictions
✅ Clean Streamlit UI
✅ Pretrained model with saved scaler

## ⚙️ How It Works
Input Features:
TV Budget
Radio Budget
Newspaper Budget
Output:
Predicted Product Sales

The model was trained using Linear Regression after scaling the input data with StandardScaler.

▶️ Run This Project Locally
1️⃣ Clone Repository
git clone https://github.com/your-username/Advertising-Sales-Prediction.git
cd Advertising-Sales-Prediction
2️⃣ Install Requirements
pip install -r requirements.txt
3️⃣ Train Model (Optional)
python train.py
4️⃣ Run Streamlit App
streamlit run app.py
📈 Model Performance
RMSE: Good Performance
R² Score: High Accuracy

(Actual values generated during training)

📸 App Preview

Add screenshot here after deployment.

## 🌐 Deployment Options

You can deploy this project on:

Streamlit Cloud
Render
Railway
Hugging Face Spaces
## 📚 Learning Outcomes

Through this project, I learned:

Regression Model Building
Feature Scaling
Model Serialization using Pickle
Streamlit Deployment
Building End-to-End ML Projects
