# Speaker Recognition Project

The Speaker Recognition Project is an implementation of speaker identification and verification using deep learning techniques. It leverages TensorFlow for neural network modeling and Librosa for audio feature extraction.

## Features

- **Data Preparation:**
  - Collect a labeled dataset of audio samples from various speakers(In .wav format).
  - Preprocess the audio data (e.g., resampling, normalization).
  - Split the dataset into training and validation sets.

- **Speaker Identification:**
  - Train a neural network to recognize different speakers based on their voice.
  - Extract relevant features from audio samples using Librosa.
  - Implement a classification model to predict speaker identities.

- **Speaker Verification:**
  - Verify whether a given voice sample belongs to a specific speaker.
  - Compare the extracted features of the test sample with the reference speaker's features.
  - Use similarity metrics (e.g., cosine similarity) to determine if the voice matches.

## Dependencies

- TensorFlow: Deep learning framework for model training.
- Librosa: Audio analysis library for feature extraction.
- NumPy: Numerical computing library for data manipulation.
- Matplotlib: Visualization library for plotting results.

## Usage

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Prepare your labeled dataset and organize it into appropriate folders.
3. Run the training script to train the speaker recognition model.
4. Use the trained model for speaker identification or verification tasks.
