
## Problem Statement

In traditional machine learning, models are often trained on large datasets, which can be time-consuming and resource-intensive to label. Active learning addresses this problem by selecting the most informative data points for labeling, thus reducing the amount of data needed while maintaining high accuracy.

## What is Active Learning?

Active learning is a machine learning approach where the algorithm selectively chooses the data points that should be labeled next. This process aims to maximize the model's performance with the least amount of labeled data. By focusing on the most informative samples, active learning can significantly reduce the cost and effort associated with data labeling.

## About the Project

In this project, I have implemented an active learning framework using the GCN (Graph Convolutional Network) query technique from the Active Learning GCN paper. The primary goal was to train a ResNet18 model on the CIFAR-10 dataset with a fraction of the data while achieving comparable accuracy to a model trained on the full dataset.

### Key Features

- **Dataset**: CIFAR-10
- **Model**: ResNet18
- **Active Learning Technique**: GCN (Graph Convolutional Network)
- **Data Efficiency**: Trained the model on just 20% of the data while achieving similar accuracy to the full dataset.

### Workflow

1. **Data Preparation**: Load and preprocess the CIFAR-10 dataset.
2. **Initial Training**: Train a ResNet18 model on the entire CIFAR-10 dataset to establish a baseline.
3. **Active Learning**:
   - Implement the GCN query technique to actively select the most informative samples.
   - Train the ResNet18 model using only 20% of the CIFAR-10 dataset.
4. **Evaluation**: Compare the performance of the model trained with active learning to the baseline model.

### Results

- Achieved similar accuracy with only 20% of the labeled data compared to training on the full dataset.


