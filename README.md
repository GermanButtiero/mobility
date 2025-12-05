# Citi Bike Mobility Challenge

Project for the **42577 Introduction to Business Analytics** course – DTU.

---

## 📌 Project Objectives

This project consists of two main components:

1. **Clustering & Prediction Challenge**  
2. **Exploratory Component**

All results are fully reproducible using the notebooks included in this repository.

---

## 📁 Repository Structure

```text
project/
│
├── data/
│   └── processed_metro_hourly.csv              # Condensed from 8GB, for convenience we provide it
│   └── processed_metro_stations.csv            # Condensed from 8GB, for convenience we provide it
│   └── ...                                     # All the remaining sets will be generated with code (Too big for Learn) 
│
├── src/
│   ├── 1_Dataset.ipynb                         # Data cleaning, preprocessing, station extraction
│   ├── 2_Clustering.ipynb                      # Station clustering + cluster label assignment
│   ├── 3_Predictions.ipynb                     # Prediction Challenge solution
│   ├── 4_Subscription Patterns.ipynb           # Subscriber vs non-subscriber usage analysis
│   ├── 5_Subway Patterns.ipynb             # Subway station influence analysis
│
└── README.md                                 # Project description
```

## 🔧 Notebook Descriptions

### `1_Dataset.ipynb`
- Cleans and preprocesses the full Citi Bike dataset  
- Generates:
  - Processed trips dataset  
  - Stations dataset  

### `2_Clustering.ipynb`
- Performs spatial clustering of stations  
- Assigns each station to a cluster based on geographic coordinates  

### `3_Predictions.ipynb`
- Implements the **Prediction Challenge**  
- Builds and evaluates predictive models  

### `4_Subscription Patterns.ipynb`
- Analyzes usage patterns of **Subscribers vs Non-Subscribers**  

### `5_Subway Patterns.ipynb`
- Examines the relationship between bike-sharing activity and proximity to subway stations  

---

