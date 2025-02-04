# Synthetic Health Monitoring Dataset

This dataset contains synthetic health metrics for 100 patients over a year, collected at 1-minute intervals. It includes heart rate, blood pressure, SpO2, respiration rate, body temperature, blood glucose, activity level, and sleep patterns, with introduced anomalies for realistic simulation.

---
🔗 View and Download the Dataset on Kaggle

📂 Dataset Structure

The dataset is provided in CSV format and contains the following key features:

## Features

- **Patient ID**: Unique identifier for each patient.
- **Timestamp**: Date and time of each observation.
- **Age**: Age of the patient in years.
- **Gender**: Gender of the patient (Male/Female).
- **Weight**: Weight of the patient in kilograms.
- **Height**: Height of the patient in centimeters.
- **BMI**: Body Mass Index of the patient.
- **Heart Rate**: Heart rate in beats per minute (bpm).
- **BP Systolic**: Systolic blood pressure in mmHg.
- **BP Diastolic**: Diastolic blood pressure in mmHg.
- **SpO2**: Oxygen saturation level in percentage (%).
- **Respiration Rate**: Respiration rate in breaths per minute.
- **Body Temperature**: Body temperature in degrees Fahrenheit (°F).
- **Blood Glucose**: Blood glucose level in mg/dL.
- **Activity Level**: Steps taken per 10 minutes (simulated using a Poisson distribution).
- **Sleep Pattern**: Sleep stage (0: Awake, 1: Light Sleep, 2: Deep Sleep).
- **Anomaly**: Binary indicator for anomalies (0: Normal, 1: Anomaly).

---

🛠️ How to Use

Download the Dataset: https://www.kaggle.com/datasets/shrishagrawal/synthetic-health-dataanomaly-100patients10-min

Load the dataset into your preferred environment using pandas:
```python
import pandas as pd
data = pd.read_csv("synthetic_health_timeseries.csv")
data.head()
```

Explore the data, handle missing values, and visualize trends to identify anomalies.

📈 Example Use Case

Anomalies such as sudden spikes, gradual changes, periodic patterns, and sensor errors have been introduced to mimic real-world scenarios. Missing data is also included to simulate real-world data collection issues.

---

🚀 Intended Use

This dataset is intended for use in healthcare-related machine learning tasks, such as:
- **Anomaly Detection**: Train models to detect anomalies in health metrics.
- **Predictive Modeling**: Predict future health events based on historical data.
- **Data Visualization**: Create visualizations to explore trends and patterns in the data.

⚠ Note: This is synthetic data and should not be used for clinical decision-making.
---



## Acknowledgements

This dataset was inspired by real-world health monitoring systems and created using Python libraries such as NumPy, Pandas, and Matplotlib.

---

## Column Descriptions

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| Patient ID          | Unique identifier for each patient.                                         |
| Timestamp           | Date and time of each observation.                                          |
| Age                 | Age of the patient in years.                                                |
| Gender              | Gender of the patient (Male/Female).                                        |
| Weight              | Weight of the patient in kilograms.                                         |
| Height              | Height of the patient in centimeters.                                       |
| BMI                 | Body Mass Index of the patient.                                             |
| Heart Rate          | Heart rate in beats per minute (bpm).                                       |
| BP Systolic         | Systolic blood pressure in mmHg.                                            |
| BP Diastolic        | Diastolic blood pressure in mmHg.                                           |
| SpO2                | Oxygen saturation level in percentage (%).                                  |
| Respiration Rate    | Respiration rate in breaths per minute.                                     |
| Body Temperature    | Body temperature in degrees Fahrenheit (°F).                                |
| Blood Glucose       | Blood glucose level in mg/dL.                                               |
| Activity Level      | Steps taken per 10 minutes (simulated using a Poisson distribution).        |
| Sleep Pattern       | Sleep stage (0: Awake, 1: Light Sleep, 2: Deep Sleep).                      |
| Anomaly             | Binary indicator for anomalies (0: Normal, 1: Anomaly).                     |

---

🤝 Contributions

Contributions to enhance the dataset or provide better anomaly detection models are welcome! Please feel free to submit a pull request or open an issue.

📜 License

This dataset is provided under the CC0 (Public Domain Dedication). Feel free to use it responsibly.

📧 Contact

For any questions or suggestions, please contact [Shrish Agrawal] at [@agrawalshrish321@gmail.com].





