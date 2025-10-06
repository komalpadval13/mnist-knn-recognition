# MNIST Handwritten Digit Classification using KNN

This project demonstrates training and optimization of a **K-Nearest Neighbors (KNN)** classifier on the MNIST dataset, with interactive visualizations using **Plotly Express**.

## Dataset
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/) of handwritten digits (0-9)

## Project Overview
- **Baseline Model:** Trained KNN on MNIST, achieving **96% accuracy** with prediction time ~41 seconds.
- **Optimized Model:** Improved prediction speed to **9 seconds** while slightly increasing accuracy to **96.75%**.
- **Visualization:** Used **Plotly Express** to create interactive charts for model performance and class-wise analysis.
- **Techniques Used:** Model optimization, performance comparison, PCA (optional for dimensionality reduction)

## Libraries Used
- Python
- scikit-learn
- Plotly Express
- NumPy, Pandas

## Results
| Model            | Accuracy | Prediction Time |
|-----------------|----------|----------------|
| Baseline KNN     | 96%      | 41s            |
| Optimized KNN    | 96.75%   | 9s             |

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mnist-knn-classification.git
