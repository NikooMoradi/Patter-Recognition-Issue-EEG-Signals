# Patter-Recognition-Issue-EEG-Signals

This repository contains the code and reports for my project on the impact of feature extraction and selection on the performance of neural networks, specifically focusing on EEG signal classification. This project was completed as part of the AI and Biological Computation course under the supervision of **Dr. Sepideh Hajipur** at Sharif University of Technology.

## Project Overview

### Objective
The primary objective of this project is to investigate how feature extraction and selection influence the performance of Multilayer Perceptron (MLP) and Radial Basis Function (RBF) neural networks. We explored time and frequency domain features of EEG signals and employed advanced feature selection techniques, including Fisher score and Particle Swarm Optimization (PSO), to enhance model accuracy.

### Methodology
- **Feature Extraction**: Time and frequency domain features were extracted from EEG signals recorded during 3D VR video exposures.
- **Feature Selection**: Fisher score was used for initial feature selection, followed by further optimization using a PSO algorithm to refine the features and select the most relevant ones.
- **Neural Network Models**: Both MLP and RBF neural networks were trained using the selected features under 5-fold cross-validation to assess their performance.
- **Comparison**: The effectiveness of the PSO algorithm in feature selection was compared with the traditional Fisher score method by evaluating the accuracy of both neural network models.

## Files in this Repository

- `CI_Project.pdf`: The project presentation detailing the problem statement, methodology, and results.
- `Report.pdf`: The comprehensive report on the project, including detailed explanations of the methods and results.
- `project_best.ipynb`: The Jupyter notebook containing the code for feature extraction, selection, and neural network training.
- `Results`: The folder containing predicted labes of my models on the test data and the extrecated features using different methods.

## Authors
- **Nikoo Moradi**

## Supervisor
- **Dr. Sepideh Hajipur**, Department of Electrical Engineering, Sharif University of Technology
