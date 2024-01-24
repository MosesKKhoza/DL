
# Deep Learning on Cassava Leaves Diseases

## Introduction
Cassava is a staple food across countries in Sub-Saharan Africa. However, it is plagued by two 
primary diseases: the Cassava Mosaic Disease and the Cassava Brown Streak disease. The goal of this 
project is to apply deep learning techniques to help classify the diseases.

The primary domain for this project is Agriculture Technology (AgriTech), with primary users being 
machine learning researchers and data scientists interested in disease detection in Cassava leaves. 
Additionally, the model/s may then be adopted into technologies used by farmers and their 
organisations to assist with early disease detection for early intervention and potential improvements 
in crop yield and food security.

This solution trains a U-Net Model (primarily used in medical applications) to segment the leaf from its background as part of identifying the region of interest (ROI) in the images as part of the image processing and then applying deep learning 
techniques. The Cassava Image Dataset is accessible on [Kaggle](https://www.kaggle.com/datasets/visalakshiiyer/cassava-image-dataset) for more details.

## Repo structure
- `MK-DL.ipynb` notebooks for data eploration, training models 
- `Cassava/`: input data (images are not included due to size constraints and can be downloaded [here](https://www.kaggle.com/datasets/visalakshiiyer/))
- `Cassava Test/`: test data (images are not included due to size constraints and can be downloaded [here](https://doi.org/10.7910/DVN/T4RB0B))

## Working with the repo
### Reproducing solution

The solution can be reproduced by the following steps:

1. Downloading the image dataset and adding it into the `Cassava/` folder.
2. Running notebook cells in ascending order to create the U-Net Model and initial base models.
3. Adding test images to the `Cassava Test/` folder.
4. Running inference with the models on the test dataset to get predictions.

More details are provided in the documentation within the notebook.
