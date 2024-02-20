# Quantum-Spectral-Clustering-an-hybrid-based-quantum-kernel-approach.
This repository contains code and documentation for the project investigating the integration of quantum computing techniques with spectral clustering algorithms.

## Overview

The study explores a hybrid approach that combines quantum kernels and feature maps with classical spectral clustering algorithms. The goal is to evaluate the effectiveness of quantum spectral clustering in comparison to traditional methods, particularly in scenarios with non-linear separability and high complexity.

## Abstract

This study investigates the integration of quantum computing techniques with spectral clustering algorithms, proposing and evaluating a hybrid approach that combines quantum kernels and feature maps with classical spectral clustering. Extensive experimentation on two datasets, including the ad\_hoc dataset from Qiskit and a synthetic complex dataset, reveals that quantum spectral clustering, particularly utilizing the ZZFeatureMap, outperforms classical methods in identifying clusters, especially in datasets with non-linear separability and high complexity. However, computational trade-offs exist, with quantum methods showing higher accuracy on smaller datasets but requiring exponentially more computational time as dataset size increases. The findings underscore the current limitations of quantum simulation on classical hardware and highlight the need for advancements in quantum hardware development to realize the full potential of quantum algorithms. While promising, practical challenges such as scalability and computational efficiency remain, suggesting avenues for future research including scalability enhancement, adaptive feature maps, error mitigation strategies, and exploration of hybrid quantum-classical algorithms for more efficient utilization of quantum resources.

## Results

The repository includes quantitative results obtained from extensive experimentation on two datasets: the ad\_hoc dataset from Qiskit and a synthetic complex dataset. Additionally, visualizations in the form of graphs are provided to illustrate key findings and comparisons between quantum spectral clustering and classical methods.

## Code Structure

- `notebook/`: Contains the notebook code for implementing the hybrid approach of quantum spectral clustering.
- `report/`: Contains a complete report and analysis of the work.

## Contributions and Feedback

Contributions to this project are welcome! If you have any feedback, suggestions, or would like to contribute, please feel free to open an issue or submit a pull request.
