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
│   └── ...                                   # Raw and processed datasets
│
├── src/
│   ├── dataset.ipynb                         # Data cleaning, preprocessing, station extraction
│   ├── clustering.ipynb                      # Station clustering + cluster label assignment
│   ├── predictions.ipynb                     # Prediction Challenge solution
│   ├── subscription_patterns.ipynb           # Subscriber vs non-subscriber usage analysis
│   ├── exploratory2_subway.ipynb             # Subway station influence analysis
│   ├── Data Analysis and Visualization 2.ipynb  # Plots and initial exploration
│
└── README.md                                 # Project description
```

## 🔧 Notebook Descriptions

### `dataset.ipynb`
- Cleans and preprocesses the full Citi Bike dataset  
- Generates:
  - Processed trips dataset  
  - Stations dataset  

### `clustering.ipynb`
- Performs spatial clustering of stations  
- Assigns each station to a cluster based on geographic coordinates  

### `predictions.ipynb`
- Implements the **Prediction Challenge**  
- Builds and evaluates predictive models  

### `subscription_patterns.ipynb`
- Analyzes usage patterns of **Subscribers vs Non-Subscribers**  

### `exploratory2_subway.ipynb`
- Examines the relationship between bike-sharing activity and proximity to subway stations  

### `Data Analysis and Visualization 2.ipynb`
- Produces visualizations and initial exploratory analysis  

---

