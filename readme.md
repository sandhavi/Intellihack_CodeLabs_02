# E-commerce Customer Segmentation Analysis

## Overview
This repository contains a comprehensive analysis of e-commerce customer behaviors using unsupervised machine learning techniques. By leveraging clustering algorithms, we successfully identified three key customer segments: Bargain Hunters, High Spenders, and Window Shoppers, providing valuable insights for targeted marketing strategies.

## Customer Segments
- **Bargain Hunters**: Customers who make frequent purchases of low-value items and heavily rely on discounts
- **High Spenders**: Premium buyers focusing on high-value purchases who are less influenced by discounts
- **Window Shoppers**: Customers who spend significant time browsing but make few purchases

## Dataset
The dataset contains customer interaction data from an e-commerce platform with the following features:
- `total_purchases`: Number of purchases made by the customer
- `avg_cart_value`: Average value of items in the customer's cart
- `total_time_spent`: Total time spent on the platform (in minutes)
- `product_click`: Number of products viewed by the customer
- `discount_counts`: Number of times the customer used a discount code
- `customer_id`: Unique identifier for each customer

## Installation and Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Git

### Clone the Repository
```bash
git clone https://github.com/sandhavi/Intellihack_CodeLabs_02
cd Intellihack_CodeLabs_02
```

### Create a Virtual Environment (Optional but Recommended)
```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### Install Dependencies
on terminal
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dependencies
The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- yellowbrick

## Repository Structure
```
├── IntelliHack_CodeLabs_02.ipynb  # Main Jupyter notebook
├── data2.csv                             # Dataset file
├── output/                               # Directory for visualization outputs
│   ├── cluster_profiles.png
│   ├── correlation_matrix.png
│   ├── elbow_method.png
│   ├── feature_boxplots.png
│   ├── feature_distributions.png
│   ├── membership_distribution.png
│   ├── pca_3d_visualization.png
│   ├── pca_visualization.png
│   ├── radar_chart.png
│   ├── silhouette_analysis.png
│   ├── tsne_visualization.png
│   └── customer_segments_results.csv     # Segmented customer data
├── README.md                             # This file
```

## Analysis Workflow
1. **Data Preprocessing**: Cleaning, handling missing values, and feature engineering
2. **Exploratory Data Analysis**: Understanding feature distributions and correlations
3. **Clustering Algorithm Selection**: Comparing K-Means, Hierarchical Clustering, and Gaussian Mixture Models
4. **Optimal Cluster Determination**: Using Elbow Method and Silhouette Analysis
5. **Cluster Evaluation**: Using multiple metrics to validate clustering quality
6. **Customer Segmentation**: Mapping clusters to business-relevant customer segments
7. **Visualization**: Creating informative visualizations of the segments
8. **Business Insights**: Providing actionable recommendations for each segment

## Contributors
- Team: CodeLabs
- Task Number: Task-02
