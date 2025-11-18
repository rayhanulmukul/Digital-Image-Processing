# CSE4162 – Digital Image Processing Laboratory

This repository operationalizes the full experimentation pipeline for **CSE4162 – Digital Image Processing Lab**, aligned with the official departmental laboratory directives. Each module is engineered for repeatable execution, quantitative evaluation, and academic compliance.

---

## Repository Structure

```
Digital-Image-Processing-Lab/
│
├── 01_Spatial_Intensity_Resolution/
├── 02_GrayLevel_Transformations/
├── 03_Noise_and_Spatial_Filtering/
├── 04_FrequencyDomain_Filtering/
├── 05_EdgeDetection_and_Segmentation/
├── 06_Morphological_Operations/
│
└── Question.pdf
```

---

## Lab Question Matrix

### **01 – Spatial & Intensity Resolution Operations**

* Reduce spatial resolution and observe degradation
* Reduce bit-depth stepwise to binary
* Generate histogram and apply single-threshold segmentation

### **02 – Gray Level Transformation Framework**

* Brightness enhancement on selected gray interval
* Power-law vs inverse log transformation comparison
* MSB-based difference image generation

### **03 – Noise Injection & Spatial Filtering**

* Salt & pepper noise addition
* Average vs Median filter PSNR benchmarking
* Multi-mask average filter evaluation (3×3,5×5,7×7)
* Harmonic vs geometric filter comparison

### **04 – Frequency Domain Noise Filtering**

* Gaussian noise injection
* Butterworth vs Gaussian LPF analysis
* Ringing effect demonstration with Ideal LPF
* HPF-based edge detection on clean and noisy images

### **05 – Edge Detection & Segmentation Suite**

* Spatial operator benchmarking (Sobel, Canny, etc.)
* Gray-level segmentation visualization
* Global threshold segmentation
* Adaptive threshold segmentation

### **06 – Morphological Processing Stack**

* Erosion and dilation
* Opening and closing
* Morphological boundary extraction
* Region filling algorithm

---

## Technology Stack

Python / MATLAB, OpenCV, NumPy, SciPy, scikit-image, Matplotlib

---

## Execution

```
cd 0X_Module
python main.py
```

---

## Academic Attribution

Department of Computer Science & Engineering  
University of Rajshahi
