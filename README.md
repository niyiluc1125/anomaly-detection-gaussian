# Anomaly Detection using Gaussian Distribution 🕵️‍♀️

This project implements **anomaly detection** using the **multivariate Gaussian distribution**, a core concept in unsupervised learning. It identifies rare or abnormal data points by modeling the probability distribution of normal examples.

## 💡 What the Project Does

- Estimates the **mean** and **variance** of features in a dataset
- Computes **probability densities** using a Gaussian model
- Automatically selects the best **threshold (epsilon)** to flag anomalies
- Visualizes anomalies and decision boundaries

## 📁 Contents

- Python implementation of:
  - `estimate_gaussian`: computes mean and variance
  - `multivariate_gaussian`: computes probability of each example
  - `select_threshold`: finds best threshold based on F1 score
- Final anomaly detection and visualization
- Sample output showing detected anomalies

## 🔧 Technologies Used

- Python
- NumPy
- Matplotlib
- Unsupervised Learning (Anomaly Detection)

## 🚀 Result

Successfully identified outliers in a dataset using a Gaussian-based model.  
The model was tuned using F1 score from a cross-validation set and achieved strong performance in detecting rare abnormal data points.

---

⭐ Created as part of the **Machine Learning Specialization**  
📚 Guided by practice exercises from Andrew Ng’s course
