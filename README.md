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
   git clone [https://github.com/](https://github.com/)<your-username>/EEG-Emotion-Classification.git


2. **Install Dependencies:**

   The required dependencies are listed in a `requirements.txt` file. You can install them using:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Scripts:**

   The specific scripts for preprocessing, feature extraction, model training, and evaluation will depend on your project structure. Refer to the provided scripts or create your own based on the code examples.

**Data Format**

The expected data format is:

* **Preprocessed EEG data:** `.npy` file containing features extracted from EEG signals.
* **Labels:** Separate `.npy` file containing emotional labels (valence, arousal, dominance, liking).

**Future Work**

This project can be extended in several ways:

* Explore additional machine learning models and hyperparameter tuning for potentially improved performance.
* Investigate the use of deep learning architectures like convolutional neural networks (CNNs) for EEG classification.
* Incorporate real-time processing techniques for online emotion recognition applications.

**Contributing**

We welcome contributions to this project. Feel free to submit pull requests with improvements, bug fixes, or new features. 


**Contact**

If you have any questions or suggestions, please feel free to create an issue or contact [shravani22wanjari@gmail.com].
```
