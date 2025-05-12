# Healthcare-Appointment-No-Show-Prediction


This project aims to predict whether patients will miss their healthcare appointments and optimize scheduling to reduce no-shows. Using a decision tree model built with Python (Scikit-learn, Pandas) and a Power BI dashboard for visualization, the project identifies high-risk patients and provides actionable recommendations to improve appointment attendance.

**Objectives**
Develop a machine learning model to predict no-shows with high recall.
Analyze trends in no-show behavior (e.g., SMS reminders, age, weekday).
create an interactive Power BI dashboard to visualize insights.
Recommend strategies to minimize no-shows and optimize scheduling.

**Dataset**
The project uses a healthcare appointment dataset (appointments.csv) with 106,987 records and 14 features, including:
Gender, Age, Neighbourhood: Patient demographics.
Scholarship, Hipertension, Diabetes, Alcoholism, Handcap: Socioeconomic and health factors.
SMS_received: Whether a reminder was sent.
Showed_up: Target variable (True for attended, False for no-show).
Date.diff, DaysBetween, ScheduledDay_DOW, AppointmentDay_DOW: Appointment timing details.

**Deliverables**
Prediction Model: Decision tree classifier (noshow_model.pkl) with 81% recall for no-shows.
Power BI Dashboard: Interactive visualizations (NoShowDashboard.pbix) showing no-show trends and predictions.
Optimization Recommendations: Strategies to reduce no-shows based on model and EDA insights.
Scripts: Python scripts for data preparation, exploratory data analysis (EDA), and model training.

**Software:**
Power BI Desktop
Python Libraries:
Pandas
Scikit-learn
matplotlib
seaborn
imblearn (for optional SMOTE)
