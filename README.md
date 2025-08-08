# Dynamic Kannada Sign Language Recognition on Resource-Constrained Devices (*UNDER DEVELOPMENT*)

## Project Overview

This research project, titled "Dynamic Kannada Sign Language Recognition on Resource-Constrained Devices," focuses on developing and optimizing deep learning models for recognizing Kannada Sign Language (KSL). Given that KSL is significantly under-explored compared to other major sign languages, our work addresses this gap by creating a custom video-based dataset and evaluating several state-of-the-art deep learning architectures.

The primary goal is to create lightweight, efficient models that can be deployed on resource-constrained devices, such as mobile phones, to enable real-time sign language recognition with low latency. This approach leverages the field of TinyML to make KSL recognition more accessible and widely available.

## Key Contributions

* **Custom KSL Video Dataset**: We have curated a unique word-level video dataset for KSL recognition, which includes 33 common vocabulary words to support dynamic gesture analysis.
* **Model Evaluation**: The project trains and evaluates several deep learning models, including **LSTM**, **BiLSTM**, and **Transformer-based** architectures, to determine their effectiveness in recognizing KSL gestures.
* **Optimization for Edge Devices**: We apply various quantization techniques to the trained models, converting them into a `.tflite` format. This process significantly reduces model size and computational requirements, making them suitable for on-device deployment.

## Technologies and Models

* **Deep Learning Models**: LSTM, BiLSTM, and Transformer
* **Feature Extraction**: MediaPipe Holistic
* **Optimization**: TensorFlow Lite (TFLite) Post-Training Quantization
* **Deployment**: Mobile application for real-time inference on edge devices

## Team

* Dr. Umadevi V
* Nishanth K S
* Navneeth K S
* Prabhanjan Prashanth Bhat
* Pranav Srinivas
