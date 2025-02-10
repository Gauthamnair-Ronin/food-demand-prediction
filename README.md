# 📌 Food Demand Forecasting - Analytics Vidhya Hackathon

## 🏆 Project Overview
This repository contains my solution for the **Genpact Machine Learning Hackathon** hosted by **Analytics Vidhya**. The objective was to build a demand forecasting model to predict the number of meal orders for upcoming weeks, helping fulfillment centers optimize raw material procurement and staffing.

## 📊 Problem Statement
A meal delivery company operates in multiple cities with various fulfillment centers dispatching orders. Given historical demand data, meal characteristics, and center-specific information, the goal is to predict demand for the next **10 weeks** (Weeks: 146-155) for each **center-meal combination**.

## 📂 Repository Structure
```
├── notebooks/                         # Jupyter Notebooks for data analysis & model training
│   ├── EDA.ipynb                      # Exploratory Data Analysis
│   ├── Model_Training.ipynb           # Machine Learning Model Training & Evaluation
│   ├── Feature_Engineering.ipynb      # Feature Engineering
│
├── data/                              # Datasets
│   ├── train.csv                       # Training dataset
│   ├── fulfillment_center_info.csv      # Fulfillment center metadata
│   ├── meal_info.csv                    # Meal metadata
│
├── assets/                            # Images & leaderboard screenshot
│   ├── vidyaanalytics_leaderboard.jpg  # Analytics Vidhya leaderboard placement
│
├── notebooks/                               # Scripts for training and inference
│   ├── demand_forecasting.ipynb             # Training and testing script
|
├── outputs/                              # output details
│   ├── predicted_data.csv                # model predcition values
│   ├── test_QoiMO9B.csv                  # test data provided
│   ├── sample_submission.csv            # Sample submission format
|
├── requirements.txt                   # Dependencies
├── README.md                          # Project documentation
```

## 📈 Approach & Methodology
1. **Data Exploration & Preprocessing:**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling & engineering

2. **Model Selection & Training:**
   - Tried various models: Linear Regression, Random Forest, Gradient Boosting, and XGBoost
   - Hyperparameter tuning for optimal performance

3. **Evaluation Metric:**
   - The competition used **Root Mean Squared Logarithmic Error (RMSLE)** as the evaluation metric.

4. **Leaderboard Score:**
   - My model achieved an **RMSLE Score of 75.7**, securing **position 1203** on the leaderboard.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/food-demand-forecasting.git
   cd food-demand-forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model and make predictions:
   ```bash
   python notebooks/demand_forecasting.ipynb
   ```


## 📜 Acknowledgments
- **Analytics Vidhya** for hosting the hackathon
- **Genpact** for providing an interesting real-world problem

## 📬 Contact
For any queries, reach out via [P A Gautham Nair](https://www.linkedin.com/in/pagauthamnair) or email at **pagauthamnair@gmail.com**.
