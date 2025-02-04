# Synthetic-Health-Monitoring-Dataset

📊 Dataset Overview

A comprehensive synthetic health monitoring dataset featuring time-series health metrics for 100 patients, collected at 10-minute intervals. Ideal for healthcare-related machine learning applications such as anomaly detection, patient monitoring, and predictive analytics. Includes realistic anomalies to mimic real-world scenarios

🔗 View and Download the Dataset on Kaggle

📂 Dataset Structure

The dataset is provided in CSV format and contains the following key features:

Features

Patient Information:

Patient ID: Unique identifier for each patient.

Age, Gender, Weight, Height, BMI: Demographic and physical information.

Health Metrics:

Heart Rate: Normal range of 60-100 bpm with anomalies.

BP Systolic, BP Diastolic: Blood pressure metrics.

SpO2: Blood oxygen levels (normal: 95-100%).

Respiration Rate: Breaths per minute.

Body Temperature: Normal range around 37°C.

Blood Glucose: Synthetic blood glucose levels.

Lifestyle Factors:

Activity Level: Simulated physical activity levels.

Sleep Pattern: Approximate sleep patterns.

Anomalies:

Sudden spikes, gradual changes, periodic patterns, and sensor errors.

Missing data points to simulate real-world data collection issues.

🚀 Intended Use

This dataset is designed for machine learning tasks in healthcare, such as:

Anomaly detection in health metrics.

Predictive analytics for patient monitoring.

Research and educational purposes.

⚠ Note: This is synthetic data and should not be used for clinical decision-making.

📈 Example Use Case

If you are working on anomaly detection, you can use this dataset to train models to detect unusual patterns in heart rate or blood pressure readings. The anomalies included in the dataset provide a rich source for testing model robustness.

🛠️ How to Use

Download the Dataset: https://www.kaggle.com/datasets/shrishagrawal/synthetic-health-dataanomaly-100patients10-min

Load the dataset into your preferred environment using pandas:
```python
import pandas as pd
data = pd.read_csv("synthetic_health_timeseries.csv")
data.head()
```

Explore the data, handle missing values, and visualize trends to identify anomalies.

💡 Potential Applications

Healthcare Analytics: Monitor patient vitals and flag anomalies.

Research Projects: Ideal for academic studies on synthetic healthcare datasets.

Model Training: Build machine learning models for time-series predictions.

🔧 Tools and Techniques Suggested

Data Visualization: Matplotlib, Seaborn

Time Series Analysis: Statsmodels, Prophet

Machine Learning: Scikit-learn, TensorFlow, PyTorch

🤝 Contributions

Contributions to enhance the dataset or provide better anomaly detection models are welcome! Please feel free to submit a pull request or open an issue.

📜 License

This dataset is provided under the MIT License. Feel free to use it responsibly.

📧 Contact

For any questions or suggestions, please contact [Your Name] at [Your Email].
