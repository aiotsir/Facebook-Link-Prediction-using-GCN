# Facebook-Link-Prediction-using-GCN
Using Graph Convolution Network to predict Facebook friends


# Project Description: Graph Convolutional Network (GCN) for Link Prediction 
## (Social Media Network Link prediction using Graph Convolution Network)
**This project implements a Graph Convolutional Network (GCN) for link prediction on a graph data (Facebook). The goal is to predict the likelihood of connections between nodes in a graph, making it applicable to various domains such as social network analysis, recommendation systems, and biological network inference.**

## Key Components:
Below is the summary of what my Juypter Notebook code includes :

**Data Loading:**

The project begins by loading graph data from an edgelist file, creating an adjacency matrix to represent the connections between nodes.
## Dataset - https://snap.stanford.edu/data/    Stanford Large Network Dataset Collection

**Model Architecture:**

The GCN model is defined using TensorFlow, comprising graph convolutional layers and a decoder for link prediction. The model is trained to capture the underlying patterns in the graph structure.

**Training and Evaluation:**

The model is trained using a specified number of epochs on a training set, and its performance is evaluated on validation and test sets.
Evaluation metrics include ROC score, Average Precision (AP) score, precision, recall, and a confusion matrix. 

**Testing:**

The trained model is tested on a separate test set, and key metrics are calculated to assess its ability to predict links accurately.

**Visualization:**

The project includes visualizations such as precision-recall curves and a confusion matrix heatmap to provide insights into the model's performance.

**Outcome:**
The project aims to demonstrate the effectiveness of GCNs in predicting links in a graph. High ROC and AP scores, along with visualizations, indicate the model's ability to capture meaningful patterns in the graph structure.

**Dependencies:**

TensorFlow

NumPy

SciPy

NetworkX

Matplotlib

Seaborn

Scikit-learn

**Usage:**

* Load graph data using the provided edgelist file.
* Train the GCN model and evaluate its performance on validation and test sets.
* Analyze key metrics and visualizations to assess the model's link prediction capabilities.
