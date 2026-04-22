# Predicting Happiness Levels Through Digital Behavior

## Project Overview
The main goal of this project is to build a machine learning model capable of predicting a person's **Happiness Index** based on various lifestyle and mental-health-related factors. 

Happiness and well-being are heavily influenced by our daily habits. By analyzing metrics such as daily screen time, sleep quality, stress levels, and social media usage, this project aims to extract useful insights into which behaviors contribute most to our mental health.


## Dataset
The project uses the `Mental_Health_and_Social_Media_Balance_Dataset.csv` which contains the following key features:
* **Digital Behavior:** Daily Screen Time (hrs), Days Without Social Media, Preferred Social Media Platform.
* **Health Metrics:** Sleep Quality (1-10), Stress Level (1-10), Exercise Frequency (per week).
* **Demographics:** Age, Gender.
* **Target Variable:** Happiness Index (1-10).

## Results & Model Performance
We treated this as a classification problem and evaluated three different machine learning models:
1. Logistic Regression
2. Support Vector Classifier (SVC)
3. **Random Forest**

**Conclusion:** The feature set proved to be highly informative for predicting happiness levels. While all models performed reasonably well, the **Random Forest** algorithm stood out as the best overall performer across key metrics (Accuracy, Precision, Recall, F1-Score, and AUC-ROC) for this specific task.

## Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/al1naaa/happiness-prediction-ml.git
   cd happiness-prediction-ml
