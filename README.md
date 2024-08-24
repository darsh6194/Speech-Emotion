
# Speech Emotion Detection using TESS Dataset

This project implements a Speech Emotion Detection system using the Toronto Emotional Speech Set (TESS) dataset. The system is designed to classify different emotions expressed in speech, leveraging machine learning techniques.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Speech Emotion Detection (SED) aims to recognize human emotions from voice recordings. This project uses the TESS dataset, which contains audio files of two actresses speaking short phrases with different emotions. The emotions detected include anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.

## Features

- **Emotion Classification:** Classifies audio samples into one of seven emotions.
- **Preprocessing:** Includes audio processing steps such as feature extraction using MFCC.
- **Modeling:** Employs machine learning models such as SVM, Random Forest, or deep learning models (e.g., CNN, LSTM).
- **Visualization:** Visualizes model performance using confusion matrices and ROC curves.

## Dataset

The Toronto Emotional Speech Set (TESS) contains 2800 audio files, including seven emotions. The dataset is publicly available [here](https://tspace.library.utoronto.ca/handle/1807/24487).

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/speech-emotion-detection.git
   cd speech-emotion-detection
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```


## Usage

1. **Prepare the dataset:**
   - Download and extract the TESS dataset into the `data/` directory.
   - Ensure the directory structure is as follows:
     ```
     data/
       └── TESS/
           └── OAF_angry/
           └── OAF_disgust/
           └── ...
     ```


## Model Architecture

The model uses extracted features such as Mel-frequency cepstral coefficients (MFCC) and applies machine learning or deep learning algorithms to classify emotions.

## Results

The model achieves an accuracy of `X%` on the test set. Below is a sample confusion matrix:


## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The TESS dataset was provided by the [University of Toronto](https://tspace.library.utoronto.ca/handle/1807/24487).
- Inspired by various open-source projects on speech emotion detection.

---

Feel free to customize this template to fit your project's specifics.
