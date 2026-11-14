# Digital Image Processing: Image Enhancement and Noise Reduction

This project explores fundamental digital image processing techniques for improving image quality, enhancing contrast, and reducing noise. Developed as part of my B.Tech Computer Science coursework, it demonstrates the application of spatial-domain filtering and histogram-based enhancement methods using Python.

## Project Overview

Digital images can be affected by poor contrast, uneven intensity distributions, and noise during acquisition or transmission. This project implements and studies different image processing techniques to address these challenges.

The notebook demonstrates how different enhancement and filtering methods affect image quality and compares their behaviour under different image conditions.

## Techniques Implemented

### 1. Image Noise Simulation
- Created low-contrast image variations to study image enhancement.
- Introduced salt-and-pepper noise to evaluate denoising techniques.

### 2. Spatial Filtering and Noise Reduction
Implemented and explored the following filters:

- Arithmetic Mean Filter
- Geometric Mean Filter
- Harmonic Mean Filter
- Median Filter
- Adaptive Noise Reduction Filter

These methods demonstrate different approaches to suppressing noise while preserving image information.

### 3. Image Enhancement
- Contrast Stretching
- Histogram Equalization

These techniques improve image contrast and intensity distribution, making image details more distinguishable.

## Technology Stack

- **Language:** Python
- **Libraries:** NumPy, Matplotlib, and image-processing libraries used in the notebook
- **Environment:** Jupyter Notebook

## Repository Structure

```text
Digital_Image_processing_BTech_Project/
│
├── dip_project.ipynb    # Implementation and experiments
└── README.md            # Project documentation
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/jahnavireddy-27/Digital_Image_processing_BTech_Project.git
cd Digital_Image_processing_BTech_Project
```

### 2. Set up the environment

Install Jupyter Notebook and the Python libraries required by the notebook.

```bash
pip install jupyter numpy matplotlib opencv-python
```

### 3. Run the notebook

```bash
jupyter notebook dip_project.ipynb
```

Run the notebook cells sequentially to reproduce the image processing experiments.

## Learning Outcomes

Through this project, I explored:

- Fundamental concepts of digital image enhancement and restoration.
- Differences between spatial filtering techniques for noise reduction.
- The effects of various filters on noisy images.
- Contrast enhancement through intensity transformations and histogram equalization.
- Practical implementation and visual comparison of image processing algorithms.

## Project Scope

This is an academic implementation intended to demonstrate foundational digital image processing concepts. The experiments focus on understanding and comparing classical image processing techniques rather than developing a production-ready image restoration system.

## Author

**Jahnavi Gongal Reddy**

B.Tech in Computer Science and Engineering  
SRM University–AP




