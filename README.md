# Assignment-5-FakeNews-Detection
# Fake News Detection using Spark MLlib

## Overview
This project implements a Fake News Detection system using Apache Spark MLlib. It leverages machine learning techniques to classify news articles as either **Fake** or **Real** based on their textual content.

## Project Structure

![image](https://github.com/user-attachments/assets/cffbfa2b-9864-474e-8b20-cb9e0d365553)


## Setup Instructions

1. Install Apache Spark & PySpark  
   Ensure Spark and Python are installed. Then install PySpark:

   ```bash
   pip install pyspark
   ```
   
Install Dependencies

```
pip install faker
pip install pandas
```

Execution Steps
```bash
spark-submit src/task1.py
spark-submit src/task2.py
spark-submit src/task3.py
spark-submit src/task4.py
spark-submit src/task5.py
```
---
Model Details

Model Used: Logistic Regression

Feature Extraction: TF-IDF Vectorizer

Evaluation Metric: Accuracy (can be extended to F1-Score, Precision, Recall)

---
Output 
![task1output](https://github.com/user-attachments/assets/9cc0f4da-7e34-498f-a285-c71ef1faf4ea)
![image](https://github.com/user-attachments/assets/91c123ed-5dab-45ab-9a80-ca3537583396)
![image](https://github.com/user-attachments/assets/7d414e09-976f-4279-876a-742f907dd9c1)
![image](https://github.com/user-attachments/assets/07aafb2b-2935-49db-8618-9bd3680daea6)




