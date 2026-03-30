# 🎛️ Hyperparameter Tuning With Keras Tuner

## 📖 Overview
This project tackles one of the most critical and time-consuming aspects of deep learning: finding the optimal configuration for a neural network. Instead of relying on manual trial and error, this notebook demonstrates how to automate the optimization process using Keras Tuner. It walks through building a dynamic model, configuring the tuner, executing a search strategy, and evaluating the final optimized network.

## 🎯 Objective
The primary objective is to implement automated hyperparameter optimization using the Keras Tuner library. By defining a tunable model architecture and employing a Random Search strategy, the project aims to systematically discover the best combination of hyperparameters (such as layer units and learning rates) to maximize model evaluation metrics.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Deep Learning Framework:** TensorFlow / Keras
* **Hyperparameter Optimization:** Keras Tuner
* **Data Manipulation & Visualization:** NumPy, pandas, Matplotlib

## 🧠 Key Learnings & Skills Demonstrated
* **Dynamic Model Building:** Constructing a Keras model with a specific build function that accepts tunable hyperparameters (e.g., dynamic ranges for dense units or learning rates).
* **Data Preparation:** Importing and efficiently formatting the dataset for neural network training and validation.
* **Automated Tuning:** Configuring and initializing Keras Tuner to explore the hyperparameter space automatically.
* **Random Search Implementation:** Executing a Random Search strategy to systematically sample and test different model configurations.
* **Model Evaluation:** Extracting the best-performing hyperparameters from the search, retraining the optimal model, and evaluating its final accuracy on unseen data.

## 🚀 Getting Started

### 📋 Prerequisites
To run this project, you will need:
* Python 3.x
* Jupyter Notebook or JupyterLab

### ⚙️ Installation & Setup

1. Clone the repository to your local machine:
   git clone https://github.com/Raaaj2005/Hyperparameter-Tuning-With-Keras-Tuner.git

2. Navigate into the downloaded project folder:
   cd Hyperparameter-Tuning-With-Keras-Tuner

3. Install the required dependencies:
   pip install tensorflow keras-tuner pandas numpy matplotlib jupyter

4. Launch the Jupyter Notebook environment:
   jupyter notebook

5. Open the project's .ipynb file and execute the cells sequentially to start the tuning process and evaluate the optimal model.

## 👤 Author
Name: Raj Fatehveer Singh Brar<br>
Email ID: rbrar_be23@thapar.edu<br>
University: Thapar Institute of Engineering and Technology
