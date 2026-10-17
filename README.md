# Machine Learning — Lab Solutions

Solutions to the laboratory assignments of the **Machine Learning** course (Prof. F. Chiariotti), MSc in Physics of Data, University of Padova.

Most algorithms are implemented **from scratch in NumPy** and, where relevant, compared with their scikit-learn counterparts.

## Contents

| Folder | Topic | Main content |
|---|---|---|
| `Lab1` | Model validation | Training, validation and test splits on SNR measurement data |
| `Lab2` | Perceptron & Regression | Perceptron with randomized updates for binary classification; linear regression |
| `Lab3` | Soft SVM | Soft-margin SVM trained with stochastic gradient descent; choice of λ via K-fold CV; comparison with the perceptron |
| `Lab4` | Random Forest | ID3 decision tree, Random Forest with bagging and Extra Trees |
| `Lab5` | Neural Networks | MLP classifier on Kuzushiji-MNIST: architecture and learning-rate search with scikit-learn, and an MLP with backpropagation written from scratch |
| `Lab6` | Clustering | Clustering of synthetic 2D data (moons) and of image pixels |
| `Lab7` | Reinforcement Learning | Reinforcement learning algorithms |

## Datasets

- **SNR measurements** — signal-to-noise ratio data (Lab 1).
- **Telecom Customer Churn** — 3,758 customers described by tenure, monthly charge and age; binary task: churned vs. stayed (Labs 3–4).
- **[Kuzushiji-MNIST](https://github.com/rois-codh/kmnist)** — 28×28 images of 10 handwritten Japanese hiragana characters (Lab 5).
- **Moons dataset and images** — 2D synthetic data and photographs used for clustering (Lab 6).

## Requirements

Python 3 with `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.

The data files are stored next to each notebook. Some notebooks load them from a `data/` subfolder, so either move the files there or adjust the path in the loading cell.
