# Exploratory Data Analysis on Iris Dataset

This project performs an **Exploratory Data Analysis (EDA)** on the classic **Iris dataset**, which is widely used for tasks such as classification, clustering, and pattern recognition. The aim is to uncover meaningful patterns, relationships, and trends within the data using Python libraries.

## About the Iris Dataset

The Iris dataset consists of 150 samples of iris flowers from three species:
- **Iris-setosa**
- **Iris-versicolor**
- **Iris-virginica**

Each sample has the following features:
- **Sepal Length (cm)**: Length of the sepal.
- **Sepal Width (cm)**: Width of the sepal.
- **Petal Length (cm)**: Length of the petal.
- **Petal Width (cm)**: Width of the petal.
- **Species**: The target variable that indicates the flower's species.

The dataset is publicly available through the [Scikit-learn library](https://scikit-learn.org/stable/), making it an excellent choice for beginners.

## Project Structure

### 1. Data Preparation
- **Loading the dataset** using the `scikit-learn` library.
- **Transforming data** into a pandas DataFrame for easy manipulation.
- Mapping numerical target values to their respective species names.

### 2. Data Quality Assessment
- Verified the presence of **NULL values**.
- Checked for **duplicate entries** and ensured dataset balance.
- Confirmed data types and structure.

### 3. Descriptive Analysis
- Generated descriptive statistics for all features.
- Compared feature distributions across the three species.

### 4. Data Visualization
- **Scatter Plots**: Examined relationships between features (e.g., petal length vs. width).
- **Correlation Heatmap**: Analyzed correlations between features to identify trends.
- **Pair Plots**: Visualized all features simultaneously to explore hidden patterns.

### 5. Key Observations
- Petal dimensions are the most **distinctive features** for differentiating species.
- **Setosa** is easily separable due to its unique feature distributions.
- **Versicolor** and **Virginica** show some overlap in feature space.

## Prerequisites

To run this project, you'll need:

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

```
Run the file Locally

If you wish to remotely access and view the Jupyter Notebook you can utilize jupyter nb viewer: https://nbviewer.org/

Created by Bhavya Bhargava
