# Voice Classification

This project focuses on building a machine learning system to classify voices based on audio features. The system uses **Librosa** to extract audio features and **Convolutional Neural Networks (CNNs)** for classification.

## Features

✅ Classifies voice samples into different categories  
✅ Extracts features such as MFCCs, chroma, and spectrograms using Librosa  
✅ Uses CNN architecture for high accuracy  
✅ Includes training, evaluation, and predictions

## Files

- `app.py`: Main Python application  
- Jupyter Notebook / scripts: Model development and training  
- `.google-cookie`: (Optional helper file, not essential to core logic)

## Dataset

Due to file size limits, the dataset is **not included in this repository**.  
Please download the dataset separately from Kaggle or another source.

Example Kaggle datasets you can explore:
- [Audio MNIST](https://www.kaggle.com/datasets/ervinas/audio-mnist)
- [Speaker Recognition Dataset](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)

Make sure to place the dataset in the appropriate folder before running the code.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/vanshitactrl/voice-classification.git
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the main application:
    ```bash
    python app.py
    ```

## Requirements

- Python 3.x  
- librosa  
- numpy  
- tensorflow  
- keras  
- matplotlib

## Model Architecture

- Feature extraction: MFCC, chroma, mel-spectrogram  
- Model: Convolutional Neural Network (CNN)  
- Training: Supervised learning on labeled voice data  
- Evaluation: Accuracy, confusion matrix, loss curves

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For questions, collaborations, or improvements:
- GitHub: [vanshitactrl](https://github.com/vanshitactrl)
