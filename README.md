# Traffic-monitoring-system-using-Computer-Vision

# Traffic Computer Vision Project

This repository contains a draft notebook for traffic computer vision analysis. The project involves extracting features from traffic video frames, training various machine learning models, and evaluating their performance.

## Table of Contents

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to analyze traffic video frames using computer vision techniques and machine learning models. The project includes the following steps:
1. Splitting video into frames.
2. Loading and preprocessing the dataset.
3. Extracting features using SIFT and pixel values.
4. Training and evaluating various machine learning models.
5. Comparing the performance of the models.

## Repository Structure

- `Traffic_Computer_Vision DRAFT.ipynb`: Jupyter notebook containing the draft of the traffic computer vision analysis.
- `dataset_images/`: Directory containing the dataset images.
- `test_histograms.pkl`: Pickle file containing the test histograms.
- `train_histograms.pkl`: Pickle file containing the train histograms.
- `train_labels.pkl`: Pickle file containing the train labels.
- `test_labels.pkl`: Pickle file containing the test labels.

# 1. Video Data Preprocessing
Annotation: Labeled road users in the video data for supervised learning.
Fragmentation into frames: Converted video sequences into individual frames to facilitate frame-by-frame analysis.
# 2. Feature Extraction
Scale-Invariant Feature Transform (SIFT): Extracted key features from the images that remain stable under scale, rotation, and translation.
Pixel Values: Utilized raw pixel values as an additional set of features for more detailed analysis.
# 3. Image Representation
K-Means Clustering: Grouped similar image features into clusters, creating "visual words" to form a vocabulary for image representation (Bag of Visual Words).
# 4. Machine Learning Models
K-Nearest Neighbors (KNN): Applied KNN for classification, where it showed strong performance.
AdaBoost Ensemble Model:
Combined three classifiers: Random Forest, Support Vector Machine (SVM), and KNN to enhance overall model performance.
# 5. Evaluation and Metrics
Accuracy: Assessed the correctness of predictions across the dataset.
Area Under the Curve (AUC): Measured the classifier’s ability to distinguish between classes, providing insight into the model’s performance.
# 6. Contribution to Traffic Monitoring
Improved the understanding and application of traditional machine learning methods in the context of road user detection and traffic monitoring.


## Getting Started

To get started with this project, you will need to have Jupyter Notebook and the required Python libraries installed. You can install the required libraries using pip:

```sh
pip install -r requirements.txt

 
