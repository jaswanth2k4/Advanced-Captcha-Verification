# Advanced CAPTCHA Verification System

**Deep Learning | Computer Vision | Adversarial Learning | Cybersecurity**

A deep learning-based CAPTCHA verification project that explores robust CAPTCHA recognition and resistance against automated solving through CNN-based recognition, adversarial distortion, and GAN-based experimentation.

---

## Overview

Traditional CAPTCHA systems are increasingly challenged by OCR and machine-learning-based automated solvers. This project investigates a CAPTCHA verification framework designed to improve resistance against automated attacks while maintaining human-readable challenges.

The project combines:

- CNN-based CAPTCHA character recognition
- GAN-based adversarial distortion
- Image preprocessing and augmentation
- Distorted CAPTCHA generation
- Adaptive challenge generation concepts
- Behavioral threat assessment concepts
- Evaluation against multiple automated attack categories

The implementation is provided as a Python-based Jupyter/Google Colab notebook.

---

## Key Features

- **CAPTCHA Recognition** — CNN-based recognition of distorted alphanumeric CAPTCHA images.
- **Image Processing** — Image resizing, normalization, augmentation, and preprocessing using OpenCV and Pillow.
- **Deep Learning** — CNN architecture for CAPTCHA character recognition using TensorFlow/Keras.
- **Adversarial Distortion** — GAN-based experimentation for generating distorted CAPTCHA samples.
- **Robustness Evaluation** — Testing recognition performance on distorted CAPTCHA samples.
- **Threat-Aware Design** — Research framework incorporating adaptive difficulty and behavioral threat assessment.
- **Visualization** — Training performance, predictions, and CAPTCHA samples are visualized within the notebook.

---

## Technologies

| Category | Technologies |
|---|---|
| Programming | Python |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | OpenCV, Pillow |
| Machine Learning | Scikit-learn |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib |
| Environment | Google Colab, Jupyter Notebook |

---

## System Architecture

The research framework follows the workflow below:

```text
                    CAPTCHA Dataset
                           |
                           v
                 Image Preprocessing
                           |
                           v
                CNN Character Recognition
                           |
                           v
                 GAN-Based Distortion
                           |
                           v
                  Threat Assessment
                           |
                           v
              Adaptive Challenge Generation
                           |
                           v
                     User Response
                           |
                           v
                 Verification Decision
                           |
                           v
                     Accept / Reject
```

### Main Components

1. **Image Preprocessing**
   - Noise reduction
   - Image normalization
   - Resizing
   - Data augmentation

2. **CNN Recognition Engine**
   - Convolutional feature extraction
   - Batch normalization
   - ReLU activation
   - Max pooling
   - Dropout-based regularization

3. **GAN-Based Distortion**
   - Generator and discriminator experimentation
   - Adversarial image distortion
   - Preservation of CAPTCHA character information

4. **Adaptive Challenge Generation**
   - Dynamic challenge difficulty based on threat level
   - Behavioral signals incorporated into the research framework

5. **Threat Assessment**
   - Behavioral anomaly detection
   - Historical threat patterns
   - Attack-frequency and verification-failure signals

---

## Implementation

The main implementation is available in:

```text
notebooks/
└── advanced_captcha_verification.ipynb
```

The notebook includes the following workflow:

```text
Dataset Loading
      |
      v
Image Preprocessing
      |
      v
Character Encoding
      |
      v
CNN Model Construction
      |
      v
Model Training
      |
      v
Validation & Testing
      |
      v
CAPTCHA Prediction
      |
      v
GAN Experimentation
      |
      v
CAPTCHA Distortion
      |
      v
Distorted CAPTCHA Evaluation
```

### Notebook Includes

- CAPTCHA dataset loading
- Image preprocessing
- Character encoding and decoding
- CNN model construction
- CNN training and validation
- CAPTCHA prediction
- Model evaluation
- GAN generator and discriminator experimentation
- CAPTCHA distortion experiments
- Evaluation on distorted samples
- Visualization of predictions and generated CAPTCHA images

---

## Results

The following results are **reported in the published research paper**:

| Metric | Reported Result |
|---|---:|
| CNN Validation Accuracy | **96.8%** |
| Human Completion Rate | **≥ 91%** |
| Reported Latency | **< 85 ms** |
| Traditional OCR Resistance | **98.7%** |
| Deep Learning CNN Resistance | **96.2%** |
| Adversarial ML Resistance | **97.8%** |
| Reinforcement Learning Resistance | **95.4%** |
| Ensemble Methods Resistance | **94.9%** |

The reported experimental evaluation used **10,000 synthetic CAPTCHA images**, which were augmented to **50,000 images** for training.

The research evaluated resistance against multiple automated attack categories, including traditional OCR, deep-learning CAPTCHA solvers, adversarial machine learning, reinforcement learning, and ensemble methods.

> **Note:** The numerical results in this section are results reported in the published research paper. They are not presented as independently reproduced results from the current repository notebook.

---

## Running the Project

The notebook is designed primarily for **Google Colab**.

### 1. Open the Notebook

Open:

```text
notebooks/advanced_captcha_verification.ipynb
```

in Google Colab.

### 2. Provide the Dataset

The notebook expects the CAPTCHA image dataset to be available through Google Drive at:

```text
MyDrive/captcha_images
```

If your dataset is stored at a different location, update the dataset path in the notebook.

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Execute the notebook cells sequentially.

The CAPTCHA dataset and trained model files are intentionally not included in this repository.

---

## Repository Structure

```text
Advanced-Captcha-Verification/
│
├── notebooks/
│   └── advanced_captcha_verification.ipynb
│
├── README.md
├── RESULTS.md
├── CITATION.cff
├── requirements.txt
└── .gitignore
```

## Publication

This project resulted in the following peer-reviewed conference publication:

**Achu Jayan, Adithya N Reddy, Jaswanth Kumar N, and Sagar Basavaraju**

*Advanced CAPTCHA Verification System Using Deep Learning and Adversarial Distortion Techniques for Enhanced Cybersecurity*

**IEEE International Conference on Intelligent Computing, Communication, Networking and Cybersecurity (IC2NC 2025)**

**DOI:** https://doi.org/10.1109/IC2NC67409.2025.11376476
