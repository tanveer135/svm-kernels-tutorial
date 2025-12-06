# **SVM Kernel Tutorial - A Comprehensive Guide**

## **Objective:**
This tutorial demonstrates the usage of **Support Vector Machines (SVM)** with different kernels: **Linear**, **Polynomial**, and **RBF (Radial Basis Function)**. You will learn how to:
- Understand the basic concepts of SVMs and their kernels
- Explore the impact of different kernels on decision boundaries and model performance
- Visualize the results and compare kernel performance using the **Iris dataset**

---

## **Dataset: Iris Dataset**
The **Iris dataset** is used for this tutorial, which contains:
- **150 samples** of iris flowers
- **4 features**: sepal length, sepal width, petal length, and petal width
- **3 classes**: Setosa, Versicolor, Virginica

### **Why This Dataset?**
- Well-known and easy to understand
- Allows clear comparison of linearly and non-linearly separable data
- Perfect for visualizing SVM kernels in action

---
## Run the Jupyter notebook to see the code and output in action:

## **Tutorial Workflow:**
1. **Import Libraries and Setup**: Import necessary Python libraries and set up the environment.
2. **Load and Explore Data**: Load the Iris dataset and visualize it using scatter plots and histograms.
3. **Kernel Comparison**: Train SVM models using different kernels:
   - **Linear Kernel**: Suitable for linearly separable data.
   - **Polynomial Kernel**: Works well for moderately non-linear data.
   - **RBF Kernel**: Best for complex non-linear relationships.
4. **Visualization**: Visualize the decision boundaries of each kernel type and analyze their effectiveness.
5. **Performance Comparison**: Compare training and testing accuracy for each kernel.
6. **Hyperparameter Tuning**: Understand and explore the impact of parameters like **C** (regularization) and **gamma** (kernel coefficient).

---

## **Key Features of This Tutorial:**
- **Visualizations**: Plots of decision boundaries for Linear, Polynomial, and RBF kernels.
- **Hyperparameter Tuning**: Explore the effect of **C** and **gamma** parameters.
- **Grid Search**: Automatically find optimal hyperparameters using Grid Search and cross-validation.
  
---
## Run the Jupyter notebook to see the code and output in action:
svm-kernels-tutorial.ipynb

## **How to Use This Repository:**
**Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/tanveer135/svm-kernels-tutorial.git
```

License:
This repository is licensed under the MIT License. You are free to use, modify, and distribute this work with appropriate attribution.
