# Python EEG Signal Analyis Practice

Welcome to the Python EEG Signal Analyis Practice repository. This repository contains 10 short exercises designed to practice essential skills in Python, signal processing, and machine learning for EEG and physiological data analysis. Each exercise should take approximately 1 hour to complete. These exercises were created by ChatGPT for practicing EEG signal analysis in Python.

## Table of Contents
1. [Signal Denoising with EEG Data](#exercise-1-signal-denoising-with-eeg-data)
2. [Power Spectrum Analysis (FFT)](#exercise-2-power-spectrum-analysis-fft)
3. [EEG Feature Extraction](#exercise-3-eeg-feature-extraction)
4. [Signal Filtering with FIR Filters](#exercise-4-signal-filtering-with-fir-filters)
5. [ERP Detection](#exercise-5-erp-detection)
6. [Heart Rate Variability (HRV) Calculation](#exercise-6-heart-rate-variability-hrv-calculation)
7. [Principal Component Analysis (PCA) on EEG Data](#exercise-7-principal-component-analysis-pca-on-eeg-data)
8. [Classification of Mental States using Machine Learning](#exercise-8-classification-of-mental-states-using-machine-learning)
9. [Time-Frequency Analysis with Wavelets](#exercise-9-time-frequency-analysis-with-wavelets)
10. [Simulating and Analyzing Artificial EEG Data](#exercise-10-simulating-and-analyzing-artificial-eeg-data)

## Exercise 1: Signal Denoising with EEG Data
**Objective:** Perform denoising on an EEG signal by applying a low-pass filter.
- **Libraries:** `numpy`, `scipy`, `matplotlib`
- **Tasks:**
  - Load an EEG dataset.
  - Apply a low-pass Butterworth filter.
  - Visualize both raw and filtered signals.
- **Expected Output:** Comparison plot between raw and filtered EEG signals.

## Exercise 2: Power Spectrum Analysis (FFT)
**Objective:** Compute and plot the power spectrum of an EEG signal.
- **Libraries:** `numpy`, `matplotlib`
- **Tasks:**
  - Apply Fast Fourier Transform (FFT) to an EEG signal.
  - Plot the power spectrum (frequency vs. power).
- **Expected Output:** Power spectrum plot with prominent EEG frequency bands.

## Exercise 3: EEG Feature Extraction
**Objective:** Extract basic EEG features such as mean, standard deviation, and peak-to-peak amplitude.
- **Libraries:** `numpy`, `pandas`
- **Tasks:**
  - Calculate descriptive statistics for each EEG channel.
  - Store features in a pandas DataFrame.
- **Expected Output:** A table with extracted features for each EEG channel.

## Exercise 4: Signal Filtering with FIR Filters
**Objective:** Filter an EEG signal using a FIR band-pass filter.
- **Libraries:** `scipy`, `matplotlib`
- **Tasks:**
  - Design a band-pass FIR filter.
  - Apply the filter to an EEG signal.
  - Plot the filtered signal.
- **Expected Output:** Filtered EEG signal plot within a specific frequency range (e.g., alpha band).

## Exercise 5: ERP Detection
**Objective:** Identify event-related potentials (ERPs) from simulated EEG data.
- **Libraries:** `numpy`, `matplotlib`
- **Tasks:**
  - Simulate an EEG signal with added ERP components.
  - Detect and visualize ERPs using signal averaging.
- **Expected Output:** Plot highlighting detected ERP components.

## Exercise 6: Heart Rate Variability (HRV) Calculation
**Objective:** Calculate and visualize HRV metrics from ECG data.
- **Libraries:** `numpy`, `scipy`, `matplotlib`
- **Tasks:**
  - Load ECG data.
  - Identify R-peaks and calculate inter-beat intervals (IBIs).
  - Compute HRV metrics (e.g., RMSSD, SDNN).
- **Expected Output:** HRV metrics and IBI plot.

## Exercise 7: Principal Component Analysis (PCA) on EEG Data
**Objective:** Reduce the dimensionality of EEG data using PCA.
- **Libraries:** `numpy`, `scikit-learn`, `matplotlib`
- **Tasks:**
  - Apply PCA on a multi-channel EEG dataset.
  - Visualize the variance explained by principal components.
  - Plot the first two principal components.
- **Expected Output:** Explained variance plot and 2D PCA plot.

## Exercise 8: Classification of Mental States using Machine Learning
**Objective:** Train a machine learning model to classify mental states based on EEG data.
- **Libraries:** `numpy`, `pandas`, `scikit-learn`
- **Tasks:**
  - Load a labeled EEG dataset.
  - Preprocess data (e.g., feature scaling).
  - Train a classifier (e.g., SVM or Random Forest) to predict mental states.
  - Evaluate the model's performance (accuracy, confusion matrix).
- **Expected Output:** Model accuracy score and confusion matrix.

## Exercise 9: Time-Frequency Analysis with Wavelets
**Objective:** Perform time-frequency analysis using wavelet transform on EEG data.
- **Libraries:** `pywt`, `matplotlib`
- **Tasks:**
  - Apply wavelet transform to an EEG signal.
  - Plot the time-frequency decomposition.
- **Expected Output:** Time-frequency heatmap of the EEG signal.

## Exercise 10: Simulating and Analyzing Artificial EEG Data
**Objective:** Generate and analyze artificial EEG data with simulated noise and events.
- **Libraries:** `numpy`, `matplotlib`
- **Tasks:**
  - Simulate multi-channel EEG data with added noise and artifacts.
  - Perform basic signal processing (filtering, feature extraction).
  - Visualize the simulated data and extracted features.
- **Expected Output:** Simulated EEG data plot and feature summary.

## Contact
Feel free to reach out if you have any questions or need clarification on any of the exercises.

These exercises were created by ChatGPT for practicing EEG signal analysis in Python. Enjoy coding and happy learning!
