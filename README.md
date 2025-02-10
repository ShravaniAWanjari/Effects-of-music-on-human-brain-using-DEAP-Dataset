# Deap-data-Classification-with-XGBoost
Classifying EEG data from DEAP dataset using XGBoost 

# EEG Emotion Classification with Feature Extraction

This repository contains code for classifying emotional states (valence, arousal, dominance, liking) from EEG data using feature extraction techniques.

**Abstract**

This project explores the use of XGBoost model to classify emotional states based on extracted features from EEG signals. The data is preprocessed by selecting relevant channels, converting the format, and applying feature extraction methods like Welch's method to compute the spectral power within predefined frequency bands. The feature-extracted dataset is then split into training, validation, and testing sets for model development and evaluation. 

A variety of machine learning models, including Random Forest Regression, K-Nearest Neighbors, Feedforward Neural Network, and XGBoost, are evaluated using stratified cross-validation to ensure balanced representation of emotional dimensions across training and testing folds. The best performing model is selected based on metrics such as accuracy, F1-score, mse, mae and standard deviation scores.

**Key Features**

* **EEG Feature Extraction:** Implements Welch's method for spectral power calculation within frequency bands.
* **Data Preprocessing:** Handles channel selection, format conversion, normalization and converting the deap dataset from .dat file to .npy file for easier handling of data. 
* **Machine Learning Model:** XGBoost.

**Getting Started**
1. **Clone the Repository:**

   ```bash
   [git@github.com:tongdaxu/EEG_Emotion_Classifier_DEAP.git](https://github.com/tongdaxu/EEG_Emotion_Classifier_DEAP.git)


2. **Run the Scripts:**

   The specific script for preprocessing, feature extraction, model training, and evaluation.

**Data Format**

The expected data format is:

* **Preprocessed EEG data:** `.npy` file containing features extracted from EEG signals.


**Future Work**

This project can be extended in several ways:

* Explore additional machine learning models and hyperparameter tuning for potentially improved performance.
* Investigate the use of deep learning architectures like convolutional neural networks (CNNs) for EEG classification.

**Contributing**

We welcome contributions to this project. Feel free to submit pull requests with improvements, bug fixes, or new features. 


**Contact**

If you have any questions or suggestions, please feel free to create an issue or contact [shravani22wanjari@gmail.com].
```
