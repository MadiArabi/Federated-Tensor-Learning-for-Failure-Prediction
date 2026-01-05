# Federated-Tensor-Learning-for-Failure-Prediction

This repository contains the **code and real data** accompanying the paper:

**A Federated Tensor Learning Method for Failure Time Forecasting of Industrial Assets Using Heterogeneous Imaging Data**  
Madi Arabi, Xiaolei Fang  
IISE Transactions

---

## 📌 Overview

This project addresses **failure time prediction in industrial systems** using **heterogeneous imaging data** in a **federated learning setting**.  
Unlike existing federated prognostic models that assume homogeneous data across users, this work supports **user-specific imaging heterogeneity** (e.g., camera resolution, placement, modality) while preserving **data privacy**.

The proposed method:
- Projects heterogeneous imaging tensors into a **shared low-dimensional tensor subspace**
- Uses **local and global projection matrices** estimated in a federated manner
- Employs an **iterative block-updating optimization algorithm**
- Predicts failure time using a **federated log-location-scale regression model**

---

## 📂 Repository Structure

data/
src/
├── main.py //
├── utils.py //
├── regression.py //
└── tensor_learning.py
