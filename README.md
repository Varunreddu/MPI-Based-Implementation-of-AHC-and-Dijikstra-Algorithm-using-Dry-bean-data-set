# MPI-Based-Implementation-of-AHC-and-Dijikstra-Algorithm-using-Dry-bean-data-set
This repository contains the source code and documentation for the project titled:

**"Implementing Parallel Computing to Enhance the Performance of Agglomerative Hierarchical Clustering (AHC) Algorithm"**

## 🧠 Project Overview

Agglomerative Hierarchical Clustering (AHC) is a foundational unsupervised machine learning technique used for grouping data based on similarity. However, its performance is constrained by its high computational cost, especially with large datasets. This project addresses that limitation by parallelizing AHC using MPI (`mpi4py` in Python) to distribute tasks across processors. It also benchmarks AHC performance against Dijkstra’s algorithm to highlight computational gains.

## 👨‍💻 Contributors

- Cheppalli Naga Sai Varun Kumar reddy — CB.EN.P2EBS24006  
- Katta Sreenivas — CB.EN.P2EBS24023  

## 🏫 Institution

Department of Electrical & Electronics Engineering  
Amrita Vishwa Vidyapeetham, Coimbatore  
M.Tech in Embedded Systems  

## 📁 Repository Structure
├── README.md
├── ahc_sequential.py # Sequential AHC implementation
├── ahc_parallel_mpi.py # MPI-based parallel AHC
├── dijkstra_parallel_mpi.py # MPI-based Dijkstra implementation
├── dataset/ # Dry Bean dataset (CSV format)
├── preprocessing.py # Data cleaning and normalization
└── results/ # Plots and performance outputs

## 📊 Dataset

- **Source**: UCI Machine Learning Repository  
- **Dataset**: Dry Bean Dataset  
- **Records**: 13,611 instances with 16 numerical features and 1 class label  
- **Use Case**: Suitable for classification and clustering tasks in agriculture and computer vision

## ⚙️ Dependencies

- Python 3.x  
- `mpi4py`  
- `numpy`  
- `matplotlib`  
- `scikit-learn`  




