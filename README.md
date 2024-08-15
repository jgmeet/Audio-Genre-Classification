## Music Genre Classification

### Project Overview
This project focuses on classifying music genres using machine learning techniques, particularly K-Means clustering and Convolutional Neural Networks (CNNs). The dataset used includes audio features from Spotify, which were leveraged to develop a highly efficient genre classifier. In addition to predicting standard genres, advanced clustering techniques were employed to discover and classify synthetic genres, enhancing the model's interpretability and accuracy.

### Key Features
- **K-Means Clustering**: Used to discover over 10 synthetic music genres by analyzing audio features.
- **Convolutional Neural Networks (CNNs)**: Achieved 93% accuracy in genre classification through fine-tuned CNN models.
- **Interpretability**: Identified key audio features contributing to genre classification, achieving around 80% accuracy for synthetic genres.

## Table of Contents
1. Installation
2. Usage
3. Dataset
4. Model Details
5. Results
6. Contributors

## Installation
To run this project, you will need Python 3.8+ and the following libraries:
- TensorFlow
- Keras
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Usage
1. Clone the repository.
2. Prepare the dataset (see the Dataset section).
3. Train the models (K-Means Clustering and CNN Model).
4. Evaluate the models.

## Dataset
The project uses Spotify's audio features dataset. You can download the dataset from the Spotify API or use an existing dataset containing features like tempo, energy, and valence. Ensure the dataset is placed in the appropriate directory before running the models.

## Model Details

### K-Means Clustering
- **Objective**: Discover synthetic genres by clustering music based on audio features.
- **Approach**: Applied K-Means clustering to identify over 10 clusters, representing synthetic genres.
- **Result**: Enhanced genre classification accuracy by incorporating these synthetic genres.

### CNN Model
- **Objective**: Classify music genres with high accuracy.
- **Approach**: Designed and fine-tuned a CNN model to classify music genres based on audio features.
- **Result**: Achieved a classification accuracy of 93%.

## Results
- **K-Means Model**: Discovered 10+ synthetic genres, with around 80% accuracy in synthetic genre identification.
- **CNN Model**: Achieved a genre classification accuracy of 93%.
