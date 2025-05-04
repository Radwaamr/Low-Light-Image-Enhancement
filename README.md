# Low Light Image Enhancement

This project focuses on enhancing low-light images to make them appear brighter and more vibrant, using a self-contained approach based on OpenCV and Python.

## 📌 Features

- Increases brightness using pixel-wise adjustment
- Boosts contrast using CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Enhances color saturation for more vivid output
- Compares results visually with original and high-light reference images

## 🧠 Method Overview

1. **Brightness Adjustment**  
   Multiplies pixel intensities to brighten the image.

2. **Contrast Enhancement**  
   Applies CLAHE on the L-channel in LAB color space.

3. **Color Saturation Boost**  
   Modifies the saturation channel in HSV color space.

4. **Visualization**  
   Side-by-side comparison of low-light, enhanced, and high-light images using `matplotlib`.
   
## 📁 Dataset

The dataset used is the [LOL dataset](https://daooshee.github.io/BMVC2018website/), containing paired low-light and normal-light images.

> ⚠️ The dataset is compressed (`lol_dataset.zip`) to save space.
