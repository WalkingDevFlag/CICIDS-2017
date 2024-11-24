# CICIDS 2017 Repository

## Overview
This repository contains Jupyter notebooks designed for analyzing the CICIDS 2017 dataset, which focuses on intrusion detection. The notebooks provide a comprehensive framework for data exploration, preprocessing, and machine learning model training.

## Features
- **Dataset Download**: Automates the retrieval of the CICIDS 2017 dataset.
- **Exploratory Data Analysis (EDA)**: Provides insights into data distributions and patterns.
- **Model Training**:
  - **Binary Classification**: Logistic Regression and Support Vector Machine.
  - **Multi-Class Classification**: K-Nearest Neighbors, Random Forest, Decision Tree.
  - **Deep Learning**: Multi-Layer Perceptron, Convolutional Neural Network, Deep Neural Network for both binary and multi-class tasks.

## Usage
Clone the repository and open the Jupyter notebooks to start analyzing the dataset. Follow the instructions within each notebook to execute the code and interpret the results.

## Setting Up the Conda Environment
To set up a Conda environment for working with the CICIDS 2017 dataset, follow these steps:

1. **Create a new Conda environment**:
   ```bash
   conda create -n cicids python=3.9
   ```

2. **Activate the environment**:
   ```bash
   conda activate cicids
   ```

3. **Install necessary libraries**:
   ```bash
   pip install numpy pandas seaborn matplotlib scikit-learn tensorflow
   ```

4. **Install additional packages**:
   ```bash
   pip install missingno imbalanced-learn wget
   ```

5. **Install Jupyter Notebook**:
   ```bash
   pip install jupyter notebook
   ```

6. **Install IPython kernel for Jupyter**:
   ```bash
   pip install ipykernel
   ```

7. **Add the Conda environment to Jupyter Notebook**:
   ```bash
   python -m ipykernel install --user --name=cicids
   ```

## Requirements
Ensure you have the necessary libraries installed, such as `pandas`, `numpy`, `seaborn`, `missingno`, `imbalanced-learn`, `scikit-learn`, and `tensorflow` or `keras` for deep learning models.

## References
1. **CICIDS Dataset**: [CICIDS 2017 Machine Learning Repository](https://github.com/djh-sudo/CICIDS2017-Machine-Learning/blob/main/README.md)
2. **Data Preprocessing**: [Data Preprocessing Notebook](https://github.com/liangyihuai/CICIDS2017_data_processing/blob/master/data_preprocessing_liang.ipynb)
3. **DNN and Preprocessing**: [DNN and Preprocessing Repository](https://github.com/fabian692/DNN-and-preprocessing-cicids-2017)
4. **Intrusion Detection**: [Intrusion Detection Notebook](https://github.com/noushinpervez/Intrusion-Detection-CICIDS2017/blob/main/Intrusion-Detection-CIC-IDS2017.ipynb)
5. **Dataset Preprocessing**: [CICIDS 2017 ML Preprocessing](https://github.com/mahendradata/cicids2017-ml)
6. **Autoencoder**: [Autoencoder Model for CICIDS 2017](https://github.com/fasial634/Autoencoder-model-for-CICIDS-2017-/blob/main/Autoencoder.ipynb)
7. **Data Cleaning and Random Forest**: [CICIDS 2017 Data Cleaning](https://github.com/Moetezafif-git/cicids2017)

## License
This project is licensed under the MIT License.
