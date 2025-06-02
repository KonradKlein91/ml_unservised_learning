# Mental Health Survey Clustering Analysis

This project supports mental health mitigation programs by analyzing a representative survey of technology-oriented employees. Using unsupervised machine learning techniques, the analysis segments employees into meaningful clusters, providing actionable insights for HR teams to design targeted mental health support strategies.

## Objectives

- **Data Exploration**: Examine the distribution, completeness, and key statistics of the dataset.
- **Preprocessing**: Handle missing values, normalize and encode data, and address non-standard entries.
- **Feature Engineering**: Create new features from existing survey responses to enhance model performance.
- **Dimensionality Reduction**: Apply Principal Component Analysis (PCA) to reduce data complexity.
- **Clustering**: Use unsupervised methods (e.g., K-Means) to identify clusters of employees.
- **Visualization**: Illustrate clusters and their characteristics for actionable HR insights.

## Dataset

- **Source**: [Kaggle - Mental Health in Tech Survey 2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)
- The dataset contains responses from technology sector employees about mental health in the workplace.

## Project Steps

1. **Load Survey Data**  
   The original CSV dataset is loaded for analysis.

2. **Preview & Explore**  
   The first few rows of the dataset are displayed to understand structure and data quality.

3. **Descriptive Statistics**  
   Generate summary statistics for all columns, identifying distributions, outliers, and anomalies.

4. **Preprocessing**  
   - Handle missing values using imputation.
   - Normalize numerical features and encode categorical data.
   - Address non-standard and inconsistent entries.
   - Create New Features by calculating composite scores from multiple survey questions.

5. **Dimensionality Reduction**  
   - Apply PCA to reduce the number of features while retaining key variance.

6. **Clustering Analysis**  
   - Use K-Means and other clustering algorithms (e.g., Gaussian Mixture, Agglomerative Clustering).
   - Evaluate cluster quality using metrics such as Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Score.

7. **Visualization**  
   - Visualize clusters and their characteristics using Matplotlib and Seaborn.

## Requirements

- Python (3.x recommended)
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- sklearn

Install requirements with:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/KonradKlein91/ml_unservised_learning.git
   cd ml_unservised_learning
   ```
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook main.ipynb
   ```
3. Follow the notebook cells to run the analysis step by step.