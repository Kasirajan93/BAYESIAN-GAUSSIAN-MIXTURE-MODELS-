# BAYESIAN-GAUSSIAN-MIXTURE-MODELS-

Bayesian Gaussian Mixture Model (BGMM) in Machine Learning
-
This repository contains an exploration of the Bayesian Gaussian Mixture Model (BGMM), an advanced clustering technique that extends the Gaussian Mixture Model (GMM) by introducing Bayesian priors.

📖 Overview
-
Unlike traditional clustering methods such as K-Means, which assign each data point to exactly one cluster, BGMM models clusters as probability distributions and allows for uncertainty in cluster assignments.

The Bayesian approach provides a principled way to:

Automatically determine the optimal number of clusters.

Prevent overfitting by using priors.

Capture uncertainty in model parameters.

🔑 Key Concepts Covered
-
Introduction to Mixture Models

Difference between GMM and BGMM

Variational Inference for parameter estimation

Model selection with Bayesian Information Criterion (BIC)

Visualizations of clustering results

📂 Contents
-
notebooks/ → Jupyter notebooks with BGMM implementation and experiments

data/ → Sample datasets for clustering

src/ → Python scripts for model training and visualization

README.md → Project documentation

🛠️ Installation
-
Clone this repository and install the required dependencies:

git clone https://github.com/your-username/bgmm-clustering.git
cd bgmm-clustering
pip install -r requirements.txt

🚀 Usage
-
Run the Jupyter notebook to explore BGMM clustering:

jupyter notebook notebooks/bgmm_demo.ipynb


Or run the script on a dataset:

python src/bgmm_clustering.py --data data/sample.csv

📊 Example Output
-
Soft cluster assignments (probabilities instead of hard labels)

Automatic detection of optimal number of clusters

Visual comparison of K-Means, GMM, and BGMM

🎯 Applications
-
Market segmentation

Image compression

Speech recognition

Anomaly detection

👨‍💻 Author
-
Kasi Rajan


