# medical-appointment-no-show-prediction
📘 Predicting Medical Appointment No-Shows Using Machine Learning

A machine learning project improving healthcare scheduling efficiency by identifying patients likely to miss appointments.

🔍 Project Overview

Missed medical appointments create significant operational and financial challenges for healthcare providers — reduced provider utilization, increased wait times, and inefficient resource allocation.

This project analyzes 110K+ medical appointment records and builds a predictive machine learning model to estimate the likelihood of a patient not showing up. The study integrates EDA, feature engineering, model training, and interpretability to deliver actionable insights for scheduling optimization.

The final model can support healthcare teams by flagging high-risk appointments and enabling targeted interventions (reminders, rescheduling, overbooking strategies).

🧩 Dataset

The dataset includes variables such as:

Patient demographics (age, gender)

Appointment characteristics (scheduled day vs. appointment day, wait time)

SMS reminders

Neighborhood

Medical conditions (hypertension, diabetes)

Appointment type

Outcome (No-Show vs. Show)

📊 Exploratory Data Analysis (EDA)

Key insights uncovered during EDA:

Longer wait times between scheduling and appointment dates significantly increase no-show probability.

Younger patients have higher no-show rates.

Receiving an SMS reminder does NOT guarantee attendance.

Certain neighborhoods show statistically higher no-show rates.

Appointment timing (day of week) influences attendance patterns.

Visuals explored include:

Age distributions

No-show correlation heatmaps

Wait-time impact plots

Neighborhood comparisons

🤖 Machine Learning Approach
Models Tested

Logistic Regression

Random Forest Classifier

XGBoost Classifier


Best-Performing Model

Random Forest delivered the best balance between:

Precision

Recall

AUC-ROC

Overfitting avoidance

Feature Importance (Key Drivers)

Wait Days

SMS Reminder Received

Age

Appointment Weekday

Medical Conditions

These insights allow healthcare teams to design targeted strategies.

📈 Results

Model Accuracy: ~78–82% (depending on cross-validation folds)

AUC-ROC: ~0.80

Key operational insight: Reducing wait times and improving reminder strategy can directly decrease no-shows.

High-risk patients can be identified with strong predictive confidence.

🛠 Technologies Used

Python

Pandas, NumPy

Scikit-Learn

Matplotlib, Seaborn

Jupyter Notebook

[Predicting Medical Appointment No-Shows.pdf](https://github.com/user-attachments/files/24156160/Predicting.Medical.Appointment.No-Shows.pdf)
[Medical Appointment No shows Code.pdf](https://github.com/user-attachments/files/24156166/Medical.Appointment.No.shows.Code.pdf)
[No Show Data.csv](https://github.com/user-attachments/files/24156168/No.Show.Data.csv)
