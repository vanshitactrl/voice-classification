# Voice Classification Using Deep Learning

# Overview

*This project focuses on classifying voices from the first 30 minutes of the 2020 U.S. presidential debate, featuring:
*Chris Wallace (Moderator)
*Donald J. Trump (Former President)
*Joe Biden (Former Vice President)
*Using Convolutional Neural Networks (CNNs), we analyze audio spectrograms to distinguish between these voices.

#Technologies Used

*Python (NumPy, Pandas, Matplotlib, Scikit-learn)
*Librosa (Audio processing)
*TensorFlow/Keras (Deep learning)
*Principal Component Analysis (PCA) (Feature reduction)

Dataset
The dataset consists of:
*Audio File: A trimmed 30-minute debate segment.
*CSV File: Includes labeled speaker data with:
*Speaker (Wallace, Biden, Trump)
*Timestamp (M:S or H:M:S)

# Speech Transcript

## Methodology

1. Data Preprocessing

*Convert audio into MEL spectrograms.
*Align the dataset with the audio timeline.
*Extract speech segments from the CSV.

2. Feature Extraction

*Extract 20 frequency features.
*Resample at 22010 Hz.
*Apply PCA to reduce dimensionality.
*Use Mutual Information to select key features.

3. Model Development

*Use a CNN-based architecture for classification:
*Convolutional Layers (Feature extraction)
*Dense Layers (Classification)
*Softmax Activation (Multi-class prediction)

4. Training & Evaluation

*Split into train/test sets.
*Train using categorical cross-entropy loss.
*Achieved 68% accuracy.
*Results & Improvements

✔ 68% accuracy using CNNs.
✔ Confusion matrix & classification report for performance.
✔ Future Enhancements:

Implement temporal smoothing.

Expand dataset size.

Apply transfer learning.

Repository Structure

Usage

Install Dependencies

git clone https://github.com/vanshitactrl/voice-classification.git
cd voice-classification
pip install -r requirements.txt

Run the Model

Preprocess Data:

python src/preprocess.py

Train the Model:

python src/train.py

Make Predictions:

python src/predict.py --audio sample_audio.mp3

Contributions & Contact

Feel free to open issues or submit pull requests.

📌 LinkedIn: Your Profile
📧 Email: your.email@example.com