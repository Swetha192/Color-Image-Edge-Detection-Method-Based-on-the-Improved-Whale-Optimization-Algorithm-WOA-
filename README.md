# Color Image Edge Detection Method Based on the Improved Whale Optimization Algorithm (WOA)
Overview:
   This project presents an advanced edge detection technique for color images using an improved version of the Whale Optimization Algorithm (WOA). Traditional edge detection methods often struggle with noise and color complexity. To address this, we enhance WOA to achieve more accurate and robust edge detection results.Instead of using fixed thresholds like traditional methods, this project searches for the *best threshold values* to improve edge clarity and reduce noise
  
# Features: 
- Edge detection using OpenCV (Canny)
- Threshold optimization using search-based method
- Improved edge quality compared to fixed thresholds
- Visualization of results using Matplotlib
- Fitness tracking across iterations

# Technologies Used:
- Python
- NumPy
- OpenCV
- Matplotlib

# Methodology:

The proposed method works as follows:

1.Input a color image
2.Preprocess the image (noise reduction, normalization)
3.Apply the improved WOA to determine optimal edge thresholds
4.Perform edge detection using optimized parameters
5.Generate final edge-detected output

The improvement in WOA focuses on:
 
 Enhanced convergence speed
 Avoidance of local minima
 Adaptive parameter tuning
 
# Optimization Idea

The algorithm evaluates edge quality using:
Fitness = Sum of edges - (0.4 × Noise)
This helps:
- Maximize edge clarity  
- Minimize noise
# Results
- **Normal Canny Output:** Uses fixed thresholds  
- **Optimized Output:** Better edges with less noise  
Also includes:
- Fitness vs Iterations graph  

# How to Run
1. Install dependencies:
pip install opencv-python numpy matplotlib

  

