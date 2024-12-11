# Music Genre Identification

This project focuses on identifying the genre of music from audio files using machine learning and deep learning models. The genres considered are:

- Blues
- Classical
- Country
- Disco
- HipHop
- Jazz
- Metal
- Pop
- Reggae
- Rock

## Overview

The main challenge of this project is feature extraction from audio files, which are then used to train models. The project utilizes several machine learning algorithms as well as a deep learning neural network for classification.

## Features Extracted

Features like Mel-Frequency Cepstral Coefficients (MFCCs) are extracted from audio files using the `librosa` library. These features represent the audio signals in a form suitable for machine learning models.

## Models Used

The following models are implemented to classify the audio genres:

1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **Support Vector Machine (SVM)**
4. **K-Nearest Neighbors (KNN)**
5. **Neural Network (using TensorFlow/Keras)**


## Data Used

Dataset: https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz?dl=0
## Results

Each model outputs the following metrics:

- **Log Loss**: Measures the uncertainty of predictions.
- **Accuracy**: Measures the proportion of correctly classified samples.

4. Run the notebook or script to extract features, train models, and evaluate results.

## File Structure

- `Music_Genre_Identification.ipynb`: Jupyter Notebook with the implementation of feature extraction and models.
- `requirements.txt`: Contains the list of dependencies.
- `README.md`: Project documentation.
- `audio_path/`: Directory for storing audio files (not included in the repository).

## Results and Visualizations

The project includes:

- **Metrics**: Log Loss and Accuracy for each model.
- **Training History**: Loss and accuracy plots for the neural network.

## Future Work

- Enhance feature extraction by incorporating additional audio features.
- Experiment with other deep learning architectures like CNNs for audio spectrograms.
- Fine-tune hyperparameters for improved accuracy.
