# Tree Species Classification in Rajarata University Garden

This repository contains the implementation and documentation for a project aimed at developing a neural network to classify three tree species found in a university garden: Millettia pinnata (Pongamia/Indian Beech), Bougainvillea glabra, and Ficus benjamina L. The project involves collecting physical measurements from these trees and using the data to train and test a neural network model.

#Group Details






### Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

### Project Overview

This project addresses the challenge of visually distinguishing between three similar tree species by using a neural network to classify them based on physical measurements.

### Objectives

- To accurately classify Millettia pinnata, Bougainvillea glabra, and Ficus benjamina L. using a neural network.
- To collect and prepare a comprehensive dataset of physical measurements from the university garden.
- To design and train a neural network model using this dataset.

### Methodology

The methodology involves several key steps:

1. **Field Survey**: Collecting physical measurements from the selected tree species.
2. **Dataset Preparation**: Organizing the collected data and applying data augmentation techniques.
3. **Model Training**: Developing and training a neural network to classify the tree species.
4. **Evaluation**: Testing the model's performance on a separate test dataset.

### Dataset

The dataset comprises measurements of leaf length, leaf width, leaf area, branch length, branch diameter, tree height, and trunk diameter. Below are some sample images representing the measured attributes:

#### Sample Leaf Measurements
![Leaf Measurements](images/leaf_measurements.jpg)

#### Sample Branch Measurements
![Branch Measurements](images/branch_measurements.jpg)

#### Sample Tree Height Measurement
![Tree Height Measurement](images/tree_height_measurement.jpg)

### Model Architecture

The neural network architecture includes:

- **Input Layer**: 32 units with ReLU activation
- **Hidden Layer**: 32 units with ReLU activation
- **Output Layer**: 3 units with softmax activation

![Model Architecture](images/model_architecture.png)

### Results

The trained neural network achieved high accuracy in classifying the three tree species. The results indicate the model's robustness and its potential application in ecological studies.

![Results](images/results.png)

### Conclusion

This project successfully demonstrates the use of a neural network to classify tree species based on physical measurements. The developed model can aid in ecological research and biodiversity conservation.

### Usage

To use this repository, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/tree-species-classification.git
