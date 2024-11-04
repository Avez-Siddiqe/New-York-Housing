# New York Housing Market Analysis

This project analyzes the New York housing market dataset using various machine learning models for regression, classification, and clustering tasks.

## Overview

The analysis includes:
1. Regression models to predict house prices
2. Classification models to categorize houses into price categories
3. K-means clustering to identify housing segments

## Models Used

### Regression Models
- Linear Regression
- Random Forest Regressor
- Support Vector Regression (SVR)

### Classification Models
- Logistic Regression
- Random Forest Classifier
- Support Vector Classification (SVC)

### Clustering
- K-means Clustering

## Requirements

```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/ny-housing-analysis.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Download the New York housing dataset from Kaggle and place it in the project directory
2. Open the Jupyter notebook:
```bash
jupyter notebook NY_Housing_Analysis.ipynb
```

## File Structure

```
ny-housing-analysis/
│
├── data/
│   └── new_york_housing.csv
│
├── notebooks/
│   └── NY_Housing_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

## Results

The notebook includes detailed analysis of model performance with evaluation metrics. Key findings:

- Regression: Random Forest typically performs best with highest R² score
- Classification: Performance varies based on the price threshold
- Clustering: Reveals distinct housing segments based on features

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Dataset source: Kaggle
- Thanks to the scikit-learn team for the excellent machine learning library
