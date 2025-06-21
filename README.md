# Webcam-Based Heart Rate Detection Using Deep Learning

## Overview

This project implements a non-contact heart rate detection system using a standard webcam and deep learning techniques. By leveraging facial video data, the model estimates heart rate (BPM) without requiring any physical sensors. The system is trained and evaluated on the UBFC-RPPG dataset, utilizing a CNN-LSTM architecture to process temporal facial features extracted from video frames.

---

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Limitations & Ethical Considerations](#limitations--ethical-considerations)
- [References](#references)
- [License](#license)
- [Contact](#contact)

---

## Features

- Non-contact heart rate estimation using webcam video
- Face detection and region-of-interest extraction
- Feature extraction from facial video (mean green channel intensity)
- Deep learning model (CNN-LSTM) for temporal signal processing
- End-to-end pipeline: video input → face detection → feature extraction → heart rate prediction

---

## Demo


![Demo Screenshot](https://github.com/Kali414/DRDO_PROJECT/blob/main/static/DRDO.webp)


---

## Project Structure


- **Feature/**: Notebooks for feature extraction and exploration.
- **Notebook/**: Model training/testing notebooks and preprocessed data files.
- **static/**, **templates/**: Web application assets (HTML, CSS, JS).
- **app.py**: Main application script (Flask app).
- **bpm_model.keras**, **bpm_model_v2.keras**: Saved Keras models.
- **formula_bpm_measure.py**: Heart rate calculation utilities.
- **haar_cascade_frontal_face.xml**: Face detection model.
- **requirements.txt**: Python dependencies.

---

## Dataset

- **UBFC-RPPG Dataset**: Public dataset for remote photoplethysmography (rPPG) and heart rate estimation.
