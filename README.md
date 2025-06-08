# Hybrid CNN-TCN Model for Epileptic Seizure Detection

This project presents a deep learning-based solution to detect epileptic seizures using EEG signals. A **hybrid CNN-TCN architecture** is employed, combining the spatial feature extraction power of Convolutional Neural Networks (CNNs) with the long-range temporal modeling capabilities of Temporal Convolutional Networks (TCNs).

## 🔍 Motivation

Traditional recurrent models like LSTMs and GRUs are effective for sequence modeling but suffer from sequential computation, making them slower and harder to parallelize. In contrast, CNNs offer efficient parallelization across input windows and kernel operations, but their limited receptive field constrains their ability to capture long-term dependencies. TCNs combine the strengths of both approaches—they provide large temporal memory through dilated convolutions and support full parallelization, making them well-suited for modeling EEG time-series data. This hybrid CNN-TCN architecture thus balances efficient computation and long-range temporal modeling for accurate seizure detection.

---