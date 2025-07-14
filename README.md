# 🏏 Cricket Score Predictor

A machine learning project that predicts the final score of a T20 cricket match based on live match conditions. Built using Python, this project leverages feature engineering and regression modeling to estimate the expected total score.

---

## 📌 Project Overview

This project uses past t20 data to predict the **final score** of a team during a live T20 match using match-specific inputs such as current run rate, overs remaining, and wickets left. It is designed for cricket enthusiasts, broadcasters, and analysts who want real-time score predictions.

---

## ✅ Key Features

- 🔍 Predicts final score in real-time during a T20 cricket match.
- 📊 Uses historical IPL data for model training.
- 🧠 Implements Random Forest Regressor for robust performance.
- 🌐 Integrated with Flask for web-based user interaction.

---

## 📂 Dataset Description

The dataset contains:
- Team-wise match performance (batting and bowling teams)
- Venue of the match
- Match progress (overs completed, current score, wickets)
- Derived features like run rate and wickets left

---

## 🔧 Tools & Technologies Used

- **Languages**: Python
- **Libraries**:  
  - `Pandas`  
  - `NumPy`  
  - `Matplotlib`, `Seaborn`  
  - `Scikit-learn`  
- **Model**: Random Forest Regressor
- **Deployment**: Flask Web Framework

---

## 📐 Feature Engineering

The following features were derived or engineered:
- `current_run_rate`
- `wickets_left`
- `balls_left`
- `crr` (Current Run Rate)
- `last_five` (Runs in last 5 overs)
- Categorical encoding of teams and venues

---

## 📈 Model Building & Evaluation

- Data split into training and test sets
- Trained using `RandomForestRegressor` from `sklearn`
- Evaluated using:
  - R² Score
  - Mean Absolute Error
- Scatter plot of **actual vs predicted** scores to assess accuracy

---

## 🌐 Web App Integration

A user-friendly interface was built using **Flask**, allowing users to:
- Select teams, venue, current score, and other match details
- Submit inputs and receive the predicted final score

To run the Flask app:
python app.py



# Screenshot predicted score

<img width="1906" height="905" alt="image" src="https://github.com/user-attachments/assets/8d8b4169-e9f8-4700-b0cf-4d1cb66a559e" />


Made with  ❤️ by [Rabindra kumar](https://github.com/rabindra1x)





