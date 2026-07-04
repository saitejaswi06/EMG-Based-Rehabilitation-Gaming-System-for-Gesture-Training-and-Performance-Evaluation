# EMG-Based Rehabilitation Gaming System for Gesture Training and Performance Evaluation

An EMG-based rehabilitation system that acquires, processes, and classifies forearm muscle activity to provide real-time visual feedback for upper-limb rehabilitation exercises. The project combines biomedical signal processing, embedded systems, and machine learning to improve rehabilitation engagement through an interactive gaming interface. The system was developed as part of the B.Tech curriculum at the National Institute of Technology Calicut. :contentReference[oaicite:0]{index=0}

---

## Overview

Traditional rehabilitation exercises are often repetitive, resulting in reduced patient engagement and limited objective performance assessment. This project addresses these challenges by integrating **surface Electromyography (sEMG)** with machine learning and an interactive interface to recognize rehabilitation gestures and provide real-time feedback.

The system detects forearm muscle activity corresponding to wrist movements, processes the acquired EMG signals, classifies user gestures, and translates them into interactive visual responses for rehabilitation training. :contentReference[oaicite:1]{index=1}

---

## Features

- Real-time surface EMG signal acquisition
- Embedded data acquisition using ESP32
- EMG preprocessing and normalization
- Time-domain feature extraction
- K-Nearest Neighbors (KNN) gesture classification
- Interactive Python-based rehabilitation interface
- Real-time gesture visualization
- Performance evaluation using confusion matrix analysis
- Approximately **80% gesture classification accuracy**

---

## System Architecture

```
Forearm Muscles
        │
Surface EMG Electrodes
        │
Signal Conditioning
(Amplification & Filtering)
        │
ESP32 Data Acquisition
        │
Serial Communication
        │
Python Processing Pipeline
        │
Feature Extraction
        │
KNN Classifier
        │
Interactive Rehabilitation Interface
```

---

## Hardware

- Surface EMG Electrodes
- EMG Analog Front-End
- ESP32 Development Board
- BIOPAC Data Acquisition System (validation)
- Personal Computer

---

## Software & Tools

- Python
- NumPy
- Scikit-learn
- Turtle Graphics
- Arduino IDE
- ESP32
- Serial Communication

---

## Signal Processing Pipeline

The acquired EMG signal undergoes multiple processing stages before classification:

- Signal acquisition
- Normalization
- Window segmentation
- Time-domain feature extraction
- Gesture classification
- Real-time visualization

### Extracted Features

- Root Mean Square (RMS)
- Mean Absolute Value (MAV)
- Mean
- Standard Deviation
- Peak Value

---

## Machine Learning

A **K-Nearest Neighbors (KNN)** classifier was trained to recognize three rehabilitation gestures:

- Rest
- Wrist Flexion
- Wrist Extension

The trained model was integrated with the visualization interface to provide real-time rehabilitation feedback. :contentReference[oaicite:2]{index=2}

---

## Results

- Reliable real-time EMG acquisition
- Stable feature extraction pipeline
- Successful gesture recognition
- Interactive rehabilitation interface
- Classification accuracy of approximately **80%**

---

## Skills Demonstrated

- Biomedical Signal Processing
- Embedded Systems
- ESP32 Programming
- Machine Learning
- Python
- Biomedical Instrumentation
- EMG Signal Analysis
- Feature Extraction
- Real-Time Systems
- Data Acquisition

---

## Future Improvements

- Deep Learning-based gesture recognition
- Additional rehabilitation gestures
- Wireless cloud-based monitoring
- Patient progress analytics
- Mobile application integration
- Multi-channel EMG acquisition

---

## Team

- Uppuluri Sai Tejaswi
- Tammireddy Vardhan
- Potturi Sumanth
- Vishwadeep K V

Department of Electrical Engineering  
National Institute of Technology Calicut

---

## Acknowledgement

This project was carried out under the guidance of **Dr. Sanjay M**, Department of Electrical Engineering, National Institute of Technology Calicut.
