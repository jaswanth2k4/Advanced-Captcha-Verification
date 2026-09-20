# Advanced CAPTCHA Verification System Using Deep Learning and Adversarial Distortion

A deep learning-based CAPTCHA verification project developed to study robust CAPTCHA recognition and resistance to automated solving through CNN-based recognition, adversarial distortion, and GAN-based experimentation.

**Published Paper:** Advanced CAPTCHA Verification System Using Deep Learning and Adversarial Distortion Techniques for Enhanced Cybersecurity  
**Conference:** IEEE International Conference on Intelligent Computing, Communication, Networking and Cybersecurity (IC2NC 2025)  
**DOI:** https://doi.org/10.1109/IC2NC67409.2025.11376476

## Project Overview

Traditional text-based CAPTCHA systems can be challenged by OCR and machine-learning-based automated solvers. This project investigates a CAPTCHA verification framework that combines:

- Image preprocessing and normalization
- CNN-based CAPTCHA character recognition
- GAN-based distortion experimentation
- Adversarial image transformations
- Adaptive challenge generation concepts
- Real-time threat assessment concepts

The published research describes a modular workflow connecting CAPTCHA preprocessing, recognition, distortion generation, threat assessment, adaptive challenge generation, and verification.

## Repository Contents

```text
advanced-captcha-verification/
├── README.md
├── RESULTS.md
├── CITATION.cff
├── requirements.txt
├── .gitignore
└── notebooks/
    └── advanced_captcha_verification.ipynb
```

## Notebook

The main implementation is provided in:

```text
notebooks/advanced_captcha_verification.ipynb
```

The notebook is designed primarily for **Google Colab** and contains the experimental implementation used for this project.

The notebook includes:

1. Dataset loading from Google Drive
2. CAPTCHA image preprocessing
3. Character encoding and decoding
4. CNN model construction and training
5. Training and validation evaluation
6. CAPTCHA prediction and testing
7. GAN generator and discriminator construction
8. GAN training experimentation
9. CAPTCHA distortion experiments
10. Evaluation on distorted CAPTCHA samples
11. Visualization of predictions and generated samples

## Dataset

The notebook expects the CAPTCHA image dataset at:

```text
/content/drive/MyDrive/captcha_images
```

The dataset is **not included in this repository**.

To use a different dataset location, update the `image_folder` variable in the notebook.

## Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Pillow
- Google Colab

## Running the Notebook

### Google Colab

1. Upload/open `notebooks/advanced_captcha_verification.ipynb` in Google Colab.
2. Mount Google Drive when prompted.
3. Place the CAPTCHA dataset in:

```text
MyDrive/captcha_images
```

4. Run the notebook cells sequentially.

### Local Environment

Install the dependencies:

```bash
pip install -r requirements.txt
```

The notebook contains Google Colab-specific Drive and file-upload operations, so Google Colab is the simplest environment for running it without modification.

## Published Research Methodology

The published paper describes a five-component framework:

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
GAN-based Distortion
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
```

The paper describes a CNN recognition engine, a GAN-based distortion generator using U-Net-style skip connections, adaptive difficulty based on threat metrics, and hybrid anomaly detection using isolation forests and statistical process control.

## Published Paper Results

The following values are **results reported in the published paper**, not claims that the current notebook reproduces all of them:

- CNN validation accuracy: **96.8%**
- Human completion rate: **at least 91%**
- Reported latency: **below 85 ms**
- Reported automated-attack resistance: **94.9%–98.7%**
- Experimental dataset: **10,000 synthetic CAPTCHA images**
- Augmented training dataset: **50,000 images**
- Reported evaluation included traditional OCR, deep-learning CNN attacks, adversarial ML, reinforcement learning, and ensemble methods
- The paper reports a six-month deployment evaluation

Detailed published-paper results are documented in [`RESULTS.md`](RESULTS.md).

## Reproducibility Note

This repository contains the experimental notebook associated with the project. It should **not** be interpreted as a complete one-command reproduction of every experiment and numerical result reported in the published paper.

In particular:

- The paper describes CAPTCHA images with dimensions of 64 × 128 pixels, while the notebook's recognition configuration uses its own experimental image dimensions.
- The paper describes a U-Net-based GAN generator with skip connections; the notebook contains GAN experimentation but should not be represented as an exact implementation of every architectural detail in the paper.
- The notebook contains a separate image-distortion function used for experimental distorted samples.
- The adaptive threat-scoring and full real-time deployment framework described in the paper are not exposed as a complete production service in this notebook.
- Numerical results in `RESULTS.md` are explicitly labeled as published-paper results.

This distinction is intentional so that the repository accurately represents the supplied implementation and does not claim experiments that the notebook itself does not reproduce.

## Research Publication

**Achu Jayan, Adithya N Reddy, Jaswanth Kumar N, Sagar Basavaraju**

"Advanced CAPTCHA Verification System Using Deep Learning and Adversarial Distortion Techniques for Enhanced Cybersecurity"

IEEE International Conference on Intelligent Computing, Communication, Networking and Cybersecurity (IC2NC 2025).

DOI: https://doi.org/10.1109/IC2NC67409.2025.11376476

## Author

**Jaswanth Kumar N**  
B.Tech, Electronics and Computer Engineering  
Amrita Vishwa Vidyapeetham, Bengaluru

LinkedIn: https://www.linkedin.com/in/jaswanth-kumar-n/  
GitHub: https://github.com/jaswanth2k4
