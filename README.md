# Breast Cancer Dataset

## Description

This dataset is used for binary classification to predict whether a breast tumor is malignant (cancerous) or benign (non-cancerous). It contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. These features describe characteristics of the cell nuclei present in the images.

## Data Source

The dataset is commonly known as the Wisconsin Breast Cancer Diagnostic Dataset and is often included in machine learning libraries like scikit-learn. You can find it in various online repositories, including the UCI Machine Learning Repository.

## Features

The dataset includes the following features:

- **radius (mean)**: Mean of distances from center to points on the perimeter
- **texture (mean)**: Standard deviation of gray-scale values
- **perimeter (mean)**: Mean size of the core tumor
- **area (mean)**: Mean area of the core tumor
- **smoothness (mean)**: Mean of local variation in radius lengths
- **compactness (mean)**: Mean of perimeter^2 / area - 1.0
- **concavity (mean)**: Mean of severity of concave portions of the contour
- **concave points (mean)**: Mean for number of concave portions of the contour
- **symmetry (mean)**: Mean of symmetry
- **fractal dimension (mean)**: Mean for "coastline approximation" - 1
- **... (and similar features for standard error, worst/largest)**

**Target Variable:**

- **target**: Diagnosis (0 for benign, 1 for malignant)

## Usage

This dataset is commonly used for practicing binary classification tasks in machine learning. It's suitable for algorithms like logistic regression, support vector machines, decision trees, and others.

## Code Example

The provided Jupyter Notebook demonstrates a basic binary classification workflow using this dataset with logistic regression. You can adapt this code for other models and further analysis.

## License

This dataset is often publicly available and used for educational and research purposes. However, always check the specific license and terms of use associated with the source from which you obtained the dataset.
