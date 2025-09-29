 # PCA Implementation on Iris Dataset

This Jupyter Notebook demonstrates the implementation of **Principal Component Analysis (PCA)** on the famous **Iris dataset** using Python's **scikit-learn** library.

---

## Overview
Principal Component Analysis (PCA) is a **dimensionality reduction technique** that transforms a large set of variables into a smaller one while preserving most of the information in the original dataset.  

In this project:
- The 4-dimensional Iris dataset is reduced to **2D and 3D** for visualization and analysis.

---

##  Dataset
The **Iris dataset** contains **150 samples** of iris flowers with **4 features** each:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

The flowers belong to **3 species**:
- Setosa  
- Versicolour  
- Virginica  

---

##  Implementation Steps
1. **Data Loading and Preparation**
   - Load the Iris dataset from scikit-learn  
   - Split into training (67%) and testing (33%) sets  
   - Separate features (**X**) and target labels (**y**)  

2. **PCA Implementation**
   - Apply PCA with **2 components** for 2D visualization  
   - Transform training and test data  
   - Examine **principal components** and **explained variance ratios**  

3. **3D Visualization**
   - Create a 3D scatter plot after PCA transformation  
   - Color-code points by species (Setosa, Versicolour, Virginica)  
   - Display the three principal components as eigenvectors  

---

##  Key Results
- **Explained Variance Ratio**:
  - PC1: **92.01%**  
  - PC2: **5.49%**  
  - Total (first two PCs): **97.5%**  

- **Principal Components**:
  - Component 1: `[0.369, -0.070, 0.856, 0.355]`  
  - Component 2: `[0.682, 0.697, -0.187, -0.121]`  

---

##  Visualization
- **2D and 3D scatter plots** of PCA-transformed data  
- Clear separation between species  
- Color-coded clusters:  
  - **Red** → Setosa  
  - **Green** → Versicolour  
  - **Blue** → Virginica  

---

##  Dependencies
Make sure the following libraries are installed:
