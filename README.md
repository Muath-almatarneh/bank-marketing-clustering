# Bank Marketing Clustering Analysis

This repository contains a complete clustering analysis of the Bank Marketing dataset using Python and Jupyter Notebook.

## Project Overview

- **Goal:** Segment bank customers based on their characteristics and campaign outcomes using unsupervised learning (KMeans clustering).
- **Dataset:** [Bank Marketing Dataset](https://www.kaggle.com/datasets/sahistapatel96/bankadditionalfullcsv)  
  Contains information about direct marketing campaigns of a Portuguese banking institution.

## Main Steps

1. **Data Loading & Exploration:**  
   Load the dataset, inspect its structure, and understand feature types.
2. **Data Cleaning & Preprocessing:**  
   Handle 'unknown' values, scale numerical features, and encode categorical features.
3. **Feature Selection:**  
   Exclude columns that may bias clustering (e.g., 'duration').
4. **Exploratory Data Analysis (EDA):**  
   Visualize distributions and detect outliers.
5. **Clustering:**  
   Apply KMeans, use Elbow and Silhouette methods to select optimal cluster count.
6. **Visualization:**  
   Use PCA for 2D cluster visualization.
7. **Interpretation:**  
   Summarize cluster characteristics and actionable insights.

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/your-username/bank-marketing-clustering.git
   ```
2. Open the notebook `#2.ipynb` in Jupyter or VS Code.
3. Make sure you have the dataset at the specified path or update the path in the notebook.
4. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
5. Run the notebook cells step by step.

## Results & Insights

- The analysis segments customers into three clusters with distinct characteristics.
- Cluster summaries can help target future marketing campaigns more effectively.

## References

- [scikit-learn Clustering Documentation](https://scikit-learn.org/stable/modules/clustering.html)
- [scikit-learn Preprocessing Documentation](https://scikit-learn.org/stable/modules/preprocessing.html)

---

Feel free to contribute or open issues for suggestions!
