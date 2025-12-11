1. Project Overview

This project investigates the feature learning dynamics of neural networks, focusing on how internal representations evolve from early to late stages of training. By analysing a convolutional model trained on CIFAR-10, the study illustrates how neural networks first form broad, low-level features before refining them into class-specific, semantically meaningful structures. The project highlights the progression of representational quality rather than just accuracy, offering insight into how deep learning models organise information over time.

2. Objectives

The main goals of this project are:

To examine how feature embeddings change at multiple points during training.

To compare the organisation of early representations with those formed later.

To visualise representational evolution using similarity matrices and low-dimensional projections.

To provide an intuitive explanation of staged feature development in neural networks.

3. Dataset

The experiments use the CIFAR-10 dataset, which contains 60,000 colour images across 10 object categories. Its mix of simple textures and complex semantics makes it ideal for observing how different feature types emerge during learning. Training and evaluation are conducted using the standard train/test split.

4. Repository Structure
project_root/
│
├── feature_learning_report.pdf      # Final written tutorial
├── feature_learning_notebook.ipynb  # Notebook containing all experiments
├── feature_learning_figs/           # Folder containing all generated figures
│
└── README.md                        # This README document

5. Figures Included

The following visual analyses are produced:

Training accuracy progression across epochs

Cosine similarity matrices showing representational structure over time

t-SNE projections illustrating the separation of embeddings

These figures collectively depict the gradual improvement of representational quality.

6. How to Navigate the Project:https://github.com/shivarajvennapureddy/24098150.git

The written report provides conceptual explanation, mathematical foundations, and interpretation of results.

The accompanying notebook demonstrates the full experimental pipeline and generates all figures used in the report.

The figures folder contains labelled images referenced throughout the analysis.

7. Accessibility Notes

High-contrast, colour-blind-friendly palettes were used in all visualisations.

Alt-text accompanies all figures to support screen-reader use.

Headings and structure follow accessible formatting guidelines.

8. License

This project is distributed under the MIT License, allowing reuse, modification, and redistribution with appropriate attribution.
