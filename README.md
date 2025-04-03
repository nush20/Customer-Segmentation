# Customer Segmentation Analysis

## Project Overview
This repository explores advanced customer segmentation techniques using three sophisticated machine learning approaches: **K-Means Clustering**, **Gaussian Mixture Model (GMM)**, and **GMM with Explainable AI (XAI)**.

## Methodology

### 1. K-Means Clustering
- **Technique**: Centroid-based clustering  
- **Key Features**:  
  - StandardScaler for feature normalization  
  - Elbow Method for optimal cluster selection  
  - Silhouette Score validation  
- **Performance Metrics**:  
  - Optimal Clusters: Determined through Elbow and Silhouette analyses  
  - Evaluates cluster separation and cohesion  

### 2. Gaussian Mixture Model (GMM)
- **Technique**: Probabilistic soft clustering  
- **Key Features**:  
  - Bayesian Information Criterion (BIC) for model selection  
  - Handles complex, non-spherical cluster shapes  
- **Performance Metrics**:  
  - Optimal Components: Selected by lowest BIC score  
  - Provides probabilistic cluster memberships  

### 3. GMM with Explainable AI (XAI)
- **Technique**: Advanced interpretable clustering  
- **Explainability Methods**:  
  - **SHAP**: Global feature importance  
  - **LIME**: Local instance explanations  
- **Key Insights**:  
  - Transparent model decision explanations  
  - Detailed customer segment characteristics  

## Dependencies

- scikit-learn  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- SHAP  
- LIME  

## Use Cases

- Targeted Marketing  
- Customer Lifecycle Management  
- Personalized Customer Engagement  
