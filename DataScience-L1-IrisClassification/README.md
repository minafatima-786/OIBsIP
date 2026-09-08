#  Iris Flower Classification

## Project Overview
This project is part of the **Oasis Infobyte Data Science Internship (Task 1 - Level 1)**.  
The goal is to build a machine learning model to classify iris flowers into three species:  
**Setosa, Versicolor, and Virginica** based on their sepal and petal measurements.

## Dataset
- **Source:** Built-in `sklearn.datasets.load_iris()`
- **Samples:** 150
- **Features:** 4 (sepal length, sepal width, petal length, petal width)
- **Target:** 3 species (balanced: 50 samples each)

## Models Implemented
- Logistic Regression (with Cross-Validation)
- K-Nearest Neighbors (with Hyperparameter Tuning)
- Decision Tree (with Cross-Validation)
- Random Forest (with Hyperparameter Tuning)

## Results
| Model | CV Accuracy | Test Accuracy |
|-------|-------------|---------------|
| Logistic Regression | 96.19% | - |
| KNN (Scaled) | 94.29% | - |
| Decision Tree | 93.33% | - |
| Random Forest | 95.24% | - |
| **KNN (Tuned)** | **97.14%** | **93.33%** |
| Random Forest (Tuned) | 96.19% | 91.11% |

**Best Model:** KNN (Tuned) with 93.33% test accuracy

## Key Findings
- Petal length and petal width are the most discriminative features
- Setosa is clearly separable from other species
- Versicolor and Virginica show some overlap
- The dataset is clean and perfectly balanced

## Author
**Mina Fatima**  
Data Science Intern at Oasis Infobyte  
