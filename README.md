# Detecting Financial Anomalies using Isolation Forest

##  Project Overview
This project demonstrates anomaly detection in financial transactions using the Isolation Forest algorithm.

The approach focuses on identifying rare and unusual patterns (potential fraud) within a dataset that is largely composed of normal transactions.

Unlike traditional clustering or classification methods, Isolation Forest isolates anomalies based on their uniqueness rather than modelling normal behaviour.

---

##  Objectives
- Detect anomalous financial transactions
- Understand how Isolation Forest isolates outliers
- Analyse anomaly score distribution
- Study the effect of contamination parameter
- Visualise normal vs anomalous behaviour

---

##  Dataset
- Synthetic financial transaction dataset
- Structure:
  - Dense cluster → normal transactions
  - Scattered points → anomalies (fraud-like behaviour)

---

##  Methods Used

###  Isolation Forest
An ensemble-based anomaly detection algorithm that isolates observations using random partitioning.

###  Anomaly Scoring
Measures how quickly a point is isolated in decision trees.

### Contamination Analysis
Controls the proportion of anomalies detected.

---

##  Visualisations Included

- Transaction distribution plot
- Isolation Forest anomaly detection
- Normal vs anomaly comparison
- Anomaly score histogram
- Contamination parameter analysis
- Decision boundary / separation insight (if included)

---
