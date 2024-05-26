# Tree Species Classification in Rajarata University Garden

This repository contains the implementation and documentation for a project aimed at developing a neural network to classify three tree species found in a university garden: Millettia pinnata (Pongamia/Indian Beech), Bougainvillea glabra, and Ficus benjamina L. The project involves collecting physical measurements from these trees and using the data to train and test a neural network model.

#Group Details

Team Name: Project AI
Team members :
- AM Akhlak (Team Lead)
- P.P. Dissanayaka
- M Asnaff



### Table of Contents

- [Introduction](#Introduction)
- [Overview of Selected Species](#Overview-of-Selected-Species)
- [Dataset Preparation](#Dataset-Preparation)
- [Details on the Training and Testing Datasets](#Details-on-the-Training-and-Testing-Datasets)
- [Architecture of the proposed Model](#Architecture-of-the-proposed-Model)
- [Training](#Training)
- [Hyper Parameters](#Hyper-Parameters)
- [Quantitative and Qualitative presentation](#Quantitative-and-Qualitative-presentation)
- [Highlighting both strength and limitations](#Highlighting-both-strength-and-limitations)
- [Summary of key Findings and their Implications](#Summary-of-key-Findings-and-their-Implications)

### Introduction

This project addresses the challenge of visually distinguishing between three similar tree species by using a neural network to classify them based on physical measurements.

### Overview of Selected Species

The project focuses on three tree species found in the university garden: Millettia pinnata, Bougainvillea glabra, and Ficus benjamina L. These species are visually similar, making them challenging to distinguish through observation alone.


#### Millettia pinnata Leaves
![Leaf Measurements](Tree_Species/Millettia pinnata.jpeg)

#### Bougainvillea glabra Leaves
![Branch Measurements](Tree_Species/Bougainvillea glabra Choisy.jpg)

#### Ficus benjamina L. Leaves
![Tree Height Measurement](Tree_Species/ages/Ficus benjamina L..jpg)


### Dataset Preparation

The methodology involves several key steps:

1. **Field Survey**: Collecting physical measurements from the selected tree species.
2. **Selection of Sampling Sites**: The sites within the university garden where each of the three tree species is found.
3. **Identification and Tagging**: Trees were initially identified by our basic knowledge (for some trees there were QR codes
found in our university context) to ensure correct species identification.
4. **Measurement Protocols**: Leaf Length (cm): Distance from the base to the tip of the leaf.
Leaf Width (cm): Maximum width of the leaf.
Leaf Angle that constructs between leaf base and its petiole (Degree)
5. **Data Recording**: All measurements were manually recorded in a field notebook and later transferred to an
electronic spreadsheet for analysis.

### Details on the Training and Testing Datasets

The dataset comprises measurements of leaf length, leaf width, leaf area, branch length, branch diameter, tree height, and trunk diameter. Below are some sample images representing the measured attributes:


### Architecture of the proposed Model

The neural network architecture includes:

- **Input Layer**: 32 units with ReLU activation
- **Hidden Layer**: 32 units with ReLU activation
- **Output Layer**: 3 units with softmax activation

![Model Architecture](images/model_architecture.png)

### Training

The trained neural network achieved high accuracy in classifying the three tree species. The results indicate the model's robustness and its potential application in ecological studies.

![Results](images/results.png)

### Hyper Parameters

This project successfully demonstrates the use of a neural network to classify tree species based on physical measurements. The developed model can aid in ecological research and biodiversity conservation.

### Quantitative and Qualitative presentation

### Highlighting both strength and limitations

### Summary of key Findings and their Implications




To use this repository, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/tree-species-classification.git
