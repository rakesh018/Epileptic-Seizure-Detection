# Hybrid CNN-TCN Model for Epileptic Seizure Detection

This project presents a deep learning-based solution to detect epileptic seizures using EEG signals. A **hybrid CNN-TCN architecture** is employed, combining the spatial feature extraction power of Convolutional Neural Networks (CNNs) with the long-range temporal modeling capabilities of Temporal Convolutional Networks (TCNs).

## 🔍 Motivation

Recurrent models like **LSTMs** and **GRUs** are commonly used for sequential data modeling, but their sequential nature hinders parallelization, making training and inference slower. On the other hand, **CNNs** can be highly parallelized (both in terms of input windows and kernels), but they have a limited memory of past inputs.

**Temporal Convolutional Networks (TCNs)** address both these limitations by:
- Offering **parallel computation** capabilities similar to CNNs.
- Maintaining **long-range temporal dependencies** through dilated convolutions.

This makes TCNs especially effective for time-series data like EEG. By fusing CNN and TCN features, our model achieves improved accuracy and efficiency in epileptic seizure detection.

---