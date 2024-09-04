# Automatic Consumer Goods Classification Engine

## Overview

Feasibility study for an automatic classification engine that categorizes articles based on their images and descriptions using the dataset provided.
Implementation of classification using text features, images features, or both

## Data Source

- **Dataset**: [Download Dataset](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)

## Objectives

1. **Data Preprocessing**:
   - **Text Data**: Clean and prepare textual descriptions of the products.
   - **Image Data**: Preprocess images for feature extraction.

2. **Feature Extraction**:
   - Extract meaningful features from both textual descriptions and images.

3. **Dimensionality Reduction**:
   - Reduce the feature dimensions to 2D for visualization.
   - Project the products on a 2D graph where each point's color represents the actual category.

4. **Graph Analysis**:
   - Analyze the 2D graph to determine the feasibility of grouping products by category based on visual and descriptive information.

5. **Validation**:
   - Calculate the similarity between actual categories and those obtained from clustering to confirm the visual analysis.

## Feature Extraction Methods

### Image Features
- **SIFT / ORB / SURF**: Use algorithms for extracting image features.
- **CNN Transfer Learning**: Implement a Convolutional Neural Network (CNN) with transfer learning for feature extraction.

### Text Features
- **Bag-of-Words**:
  - **Simple Count**: Count the frequency of words.
  - **Tf-idf**: Compute Term Frequency-Inverse Document Frequency.
- **Word/Sentence Embeddings**:
  - **Word2Vec / Glove / FastText**: Use classical embedding methods.
  - **BERT**: Implement embeddings with Bidirectional Encoder Representations from Transformers.
  - **USE (Universal Sentence Encoder)**: Apply embeddings with Universal Sentence Encoder.

## Notebook 2

- **Supervised Classification**:
  - Perform supervised classification using the image data.
  - Implement data augmentation to optimize the model performance.

## Setup and Requirements

- **Programming Language**: Python
- **Libraries**: OpenCV, TensorFlow/Keras, Scikit-learn, NLTK/Spacy, etc.



