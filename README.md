# 🎵 Audio Classification: Voice vs Musical Instruments

This project focuses on classifying audio recordings to distinguish **human voice** from **musical instruments** using feature extraction techniques and deep learning models (CNN/RNN).

## 📂 Dataset Overview

- **10 Classes**:  
  - 1 class represents **human voice**
  - 9 classes represent **musical instruments**
- **30 recordings per class**
- Audio files are in `.wav` format

## 🧪 Project Structure

| Notebook | Description |
|----------|-------------|
| `speech-recognition-exploratory-data-analysis.ipynb` | Explores the audio dataset using visualizations and extracts key features like MFCC, FFT, and filter banks. |
| `speech-recognition-modelling.ipynb` | Prepares the dataset for training, defines CNN/LSTM models, and trains the classifier. |

---

## 🔧 Features Extracted

- **Raw Signal**
- **Fast Fourier Transform (FFT)**
- **Mel-Frequency Cepstral Coefficients (MFCCs)**
- **Log Filter Banks**

These features are used as inputs for the deep learning model.
