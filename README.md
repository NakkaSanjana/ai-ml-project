# Household Power Consumption Prediction using Machine Learning

## Project Overview
This project focuses on predicting household energy consumption using real-world
power usage data. The objective is to apply machine learning fundamentals such as
data preprocessing, feature selection, model training, and evaluation to a
realistic dataset.

The emphasis of this project is on understanding data behavior and model reasoning
rather than achieving very high prediction accuracy.

---

## Dataset Description
The Household Power Consumption dataset contains measurements of electric power
usage recorded at regular time intervals in a residential household.

### Key Features:
- Voltage
- Global Intensity
- Sub_metering_1 (Kitchen energy usage)
- Sub_metering_2 (Laundry energy usage)
- Sub_metering_3 (Heating and AC energy usage)

### Target Variable:
- Global_active_power (Total household energy consumption)

---

##  Machine Learning Pipeline

1. Data loading and understanding  
2. Data preprocessing and missing value handling  
3. Feature selection and scaling  
4. Train-test split  
5. Model training using Linear Regression  
6. Model evaluation using regression metrics  

---

##  Model Used
*Linear Regression*

Linear Regression was chosen due to its simplicity and interpretability. It helps
understand how individual electrical parameters influence total energy
consumption, aligning with the project’s focus on model reasoning.

---

##  Evaluation Metrics
The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics provide insight into prediction accuracy and model reliability.

---

##  Results and Inference
The results show that sub-metered energy consumption significantly impacts total
household power usage. Electrical parameters such as voltage and current intensity
also influence energy consumption patterns.

The model demonstrates that even simple machine learning techniques can effectively
capture real-world energy usage behavior when supported by proper data handling and
feature selection.

---

##  Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

##  Project Files
-Household_Power_Consumption_ML.ipynb – Complete implementation and analysis

---

##  Colab Notebook
You can view and run the notebook using the link below:

https://colab.research.google.com/drive/1A1wWLNnIyr248Ho6vFuPZs5EW0ciCJs1?usp=sharing

---

## Conclusion
This project successfully applies core machine learning concepts to a real-world
dataset. It highlights the importance of data preprocessing, model selection, and
interpretability in building reliable ML solutions.
This project successfully applies core machine learning concepts to a real-world
dataset. It highlights the importance of data preprocessing, model selection, and
interpretability in building reliable ML solutions.
