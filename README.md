# MNIST Handwritten Digit Classification using KNN

This project demonstrates training and optimization of a **K-Nearest Neighbors (KNN)** classifier on the MNIST dataset, with and without **PCA** for dimensionality reduction. It includes interactive visualizations using **Plotly Express** and compares accuracy and prediction time for both approaches.

---

## Project Structure

           mnist-knn-classification/
            │
            ├── notebooks/
            │ ├── without_PCA.ipynb 
            │ └── with_PCA_KNN.ipynb 
            │
            ├── dataset/
            │ └── mnist.csv 
            ├── README.md
            ├── requirements.txt


## Project Overview
- **Baseline Model:** KNN without PCA, accuracy **0.9503**, prediction time **18.63 sec**  
- **Optimized Model:** KNN with PCA (50 components), accuracy **0.9507**, prediction time **2.24 sec**  
- **Visualization:** Interactive charts using **Plotly Express** for data and model insights  
- **Techniques Used:** KNN classification, PCA for dimensionality reduction, model performance analysis  

---

## Libraries Used
- `Python 3.x`   
- `scikit-learn`  
- `numpy`  
- `pandas`  
- `plotly`  

---

## Results

| Model             | Accuracy  | Prediction Time (sec) |
|------------------|-----------|---------------------|
| KNN (Without PCA) | 0.9503   | 18.63               |
| KNN (With PCA=50) | 0.9507   | 2.24                |

**Observation:** Applying PCA drastically reduces prediction time (~8x faster) while maintaining similar accuracy.

---

## How to Run

1. Clone the repository:
           git clone https://github.com/komalpadval13/mnist-knn-recognition.git

2.Navigate to the project folder:
          cd mnist-knn-classification

3.Install dependencies:
          pip install -r requirements.txt

4.Run the notebooks:
          without_PCA.ipynb
          with_PCA_KNN.ipynb