# Master Thesis Code Repository
This repository contains the code used in the development of the master's thesis:
Machine Learning as an Editorial Decision-Support Tool for Metadata Enrichment at TV 2 Play

The repository consists of six Jupyter Notebook files documenting the data preparation process and the development of the machine learning models used throughout the study.

## Repository Structure
### 1. Data Analysis and Dataset Preparation.ipynb
This notebook contains the dataset investigation and preprocessing steps used to construct the final dataset employed in the thesis.

### Model 1: playBERTbase.ipynb
Contains the implementation and training of the baseline model used as the foundation for other experiments.

### Model 2: playBERTbce.ipynb
Extends the baseline model by introducing label-wise threshold optimization, allowing each label to have an individually optimized decision threshold.

### Model 3: playBERTasl.ipynb
Presents the model trained using Asymmetric Loss (ASL) to better address class imbalance and multi-label classification challenges.

### Model 4: playBERThwatt.ipynb
Introduces a head-wise attention mechanism, allowing the model to learn task-specific representations for each metadata category.

### Model 5: playBERTlwatt.ipynb
Introduces a label-wise attention mechanism, enabling the model to learn attention patterns specific to individual labels within each metadata category.

## Notes
The notebooks are presented in the order in which the models were developed and evaluated.
Due to confidentiality considerations, the original dataset is not included in this repository.
