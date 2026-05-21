# Fundamentals of Computer Vision

A collection of 4 computer vision projects implemented in Python as part of the Fundamentals of Computer Vision course. All projects use OpenCV, NumPy, and Matplotlib.

## Projects

### Project 1 — Convolution & Linear Filtering
Custom implementation of 2D convolution with configurable kernel, padding, and stride. Linear filters implemented: Laplacian, Sobel (X/Y), Mean, and Gaussian. Includes comparison between custom implementation, SciPy, and OpenCV. Optional: template matching using Normalized Cross-Correlation (NCC).

### Project 2 — Non-Linear Filtering & Morphological Operations
Custom median filter implementation with salt-and-pepper noise testing. Morphological operations implemented from scratch: dilation, erosion, opening, closing, and morphological gradient. Optional: watermarking pipeline combining linear filtering, non-linear filtering, and morphological operations with alpha blending.

### Project 3 — Feature Extraction (Harris & LoG)
Harris Corner Detector implemented from scratch using Sobel gradients, Gaussian smoothing, and eigenvalue-based corner response R = λ₁λ₂ − k(λ₁+λ₂)². LoG Blob Detector using scale-normalized Laplacian of Gaussian across multiple sigma values with scale-space peak detection.

### Project 4 — Color Histograms, Feature Descriptors & BoVW
Normalized color histogram analysis across RGB, HSV, LAB, and YCrCb color spaces with histogram correlation comparison. SIFT and ORB feature extraction with runtime benchmarking. Bag of Visual Words (BoVW) pipeline: SIFT descriptors → K-Means vocabulary → L2-normalized histograms → SVM classifier. Achieved 88% classification accuracy on aquarium vs. desert dataset.

## Stack

Python · OpenCV · NumPy · Matplotlib · SciPy · scikit-learn
