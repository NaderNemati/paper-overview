# paper-overview
Overview and abstract for 'Multimodal Generative Deep Learning for ECG Image Digitization and Reconstruction'. This summary includes author information, as well as instructions for accessing the full private repository that includes the full source code and methodology.



# Multimodal Generative Deep Learning for ECG Image Digitization and Reconstruction

## Abstract
ECGs (Electrocardiograms) provide reliable information about cardiovascular health by detecting arrhythmias. However, historical ECG records often remain in paper format, presenting challenges for modern diagnostic tools. Digitizing these records is crucial to developing comprehensive datasets that cover a wide range of clinical conditions. Although digitizing ECG records is crucial, many ECG images suffer from poor quality due to variations in recording standards and scanning artifacts. The purpose of this study is to develop a multimodal generative deep learning framework that reconstructs digital ECG signals from ECG images by training on paired image-signal data, where raw ECG signals act as ground-truth labels to improve the accuracy of reconstruction ECG waveforms. In this method, historical ECG images are reconstructed as high-quality digital ECG signals, achieving an average signal-to-noise ratio (SNR) of 9.53 dB, allowing integration with modern diagnostic equipment. Beyond enhancing signal clarity and preserving critical diagnostic features of the original ECG, the method reconstructs high-quality digital ECG waveforms that are directly compatible with modern clinical workflows.

## Overview

This repository provides a public overview of our research work, including:

- **Abstract & Summary:** A concise explanation of the paper's objectives, methodology, and contributions.
- **Paper Summary:** An explanation of the challenges addressed (e.g., digitization of legacy ECG records) and a description of our multimodal approach.
- **Author Information:** Contact details for the corresponding authors.
- **Access Instructions:** Details on how referees and collaborators can request access to the full code and detailed methodology in a separate, private repository.

## Paper Summary

**Title:** Multimodal Generative Deep Learning for ECG Image Digitization and Reconstruction

The paper discusses digitizing legacy ECG records, which are usually only available as scanned images or paper prints. Due to poor image quality and artifacts, these records can present challenges. A multimodal approach is presented here that combines the spatial characteristics of ECG images with the temporal characteristics of raw ECG signals. The framework produces high-quality digital ECG signals using an encoder-decoder architecture and dedicated preprocessing for both modalities. By enhancing signal clarity and preserving diagnostic features, this method facilitates improved automated diagnosis. Key points include:

- **Data Preparation:** Synthetic ECG images are generated and enhanced using various preprocessing techniques, ensuring robustness to noise and artifacts.
- **Model Architecture:** The framework features an encoder-decoder design that leverages both convolutional neural networks (for image processing) and fully connected layers (for signal processing) to form a unified latent representation.
- **Performance Evaluation:** The reconstructed ECG signals achieve significant improvements in Signal-to-Noise Ratio (SNR), Mean Squared Error (MSE), and Mean Absolute Error (MAE), underscoring the model's accuracy and clinical relevance.

For more detailed information on our methodology and implementation, please refer to the private repository (see below).

## Access to Full Code

The complete codebase, along with detailed methodology and additional documentation, is available in a separate **private repository**. If you are a referee or collaborator interested in accessing the full code, please follow these steps:

1. **Contact the Corresponding Author:**  
   Send an email to [my.email@example.com](mailto:my.email@example.com) with a brief message stating that you are a referee or collaborator requesting access to the full repository.

2. **Access Grant:**  
   Upon verification, you will be added as a collaborator to the private repository.

3. **Repository Link:**  
   Once access is granted, you will receive a direct link to the private repository containing all code, scripts, and comprehensive documentation.

## Authors

- **Nader Nemati**  
  University of Turku, Turku, Finland  
  Email: [naderr.nemati@gmail.com](mailto:naderr.nemati@gmail.com)

- **Mojtaba Jafari Tadi**  
  University of Turku, Turku, Finland  
  Email: [mojtaba.jafaritadi@utu.fi](mailto:mojtaba.jafaritadi@utu.fi)

## License

This repository is provided for review purposes only. The full code (including detailed implementation and additional documentation) in the private repository is subject to separate licensing terms, which will be provided upon access.

---

Thank you for your interest in our research!
