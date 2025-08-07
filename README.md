# Predictive Maintenance Framework with Sensor Data and NLP Logs

This repository contains the final MSc Data Science dissertation project focused on building a predictive maintenance system by combining time-series sensor data and natural language processing (NLP) of maintenance logs. The project addresses data scarcity in underdeveloped industrial contexts by integrating structured and unstructured data to improve fault classification and enable proactive maintenance interventions.

## 🧠 Project Overview

Many industrial systems lack sufficient historical sensor data to support effective predictive maintenance. This project proposes a hybrid framework that:

- Uses synthetic sensor data to simulate machine metrics.
- Applies Natural Language Processing (NLP) to operator-maintenance logs.
- Combines both data sources to predict equipment failure.

Key outcomes:
- Improved classification accuracy by 35% over baseline models using only sensor data.
- Demonstrated the value of unstructured textual logs in failure prediction.
- Offers a scalable approach adaptable to data-scarce industrial settings.


## 📊 Technologies Used

- **Python**: Core programming language
- **Pandas, NumPy**: Data handling
- **Matplotlib, Seaborn**: Visualization
- **Scikit-learn**: Machine learning models
- **NLTK, spaCy**: Text processing and NLP
- **Jupyter Notebooks**: Exploratory development

## 🧪 Methodology

1. **Sensor Data Simulation**  
   Time-series data generated to mimic real-world industrial machine behavior using NumPy.

2. **Maintenance Log Generation**  
   NLP templates used to simulate realistic operator logs with embedded fault information.

3. **Feature Engineering**  
   - Statistical features from sensor metrics
   - TF-IDF vectorization and embeddings from text logs

4. **Model Training & Evaluation**  
   - Trained classifiers (Logistic Regression, Random Forest, etc.)
   - Evaluated using accuracy, precision, recall, F1-score

5. **Hybrid Model Integration**  
   Combined structured and unstructured data into a single model to enhance prediction capability.

## 📌 Key Insights

- Maintenance logs, even when loosely structured, provide critical context often missing from raw sensor metrics.
- Integrating NLP-derived insights with sensor data leads to significantly improved predictive performance.
- The approach supports industrial settings where full IoT infrastructure is not yet available.

## 📚 Dissertation Reference

This repository accompanies the dissertation titled:

> **"Predictive Maintenance in Industrial Systems"**  
> MSc Data Science, University of East London, 2025

📩 Contact
For questions or collaborations:

Asante Agyei Boakye
agyeiboakyeasante@gmail.com
