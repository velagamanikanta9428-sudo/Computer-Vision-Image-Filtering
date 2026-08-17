# Computer Vision – Image Smoothing Using Averaging Filters

## Overview

This project demonstrates image smoothing (blurring) using averaging filters of different kernel sizes in OpenCV.

The experiment applies:

- 3 × 3 Averaging Filter
- 5 × 5 Averaging Filter
- 7 × 7 Averaging Filter

and compares the results with the original grayscale image.

---

## Objective

To study the effect of averaging filters on image smoothing and noise reduction.

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset / Input

Input image:
- image16.jpg (grayscale image)

---

## Methodology

1. Read the image in grayscale mode.
2. Create averaging kernels:
   - 3×3
   - 5×5
   - 7×7
3. Apply filters using `cv2.filter2D()`.
4. Display original and filtered images.
5. Compare smoothing effects.

---

## Formula

For an averaging filter:

\[
K = \frac{1}{n^2}
\]

Example:

### 3×3 Kernel

\[
\frac{1}{9}
\begin{bmatrix}
1 & 1 & 1 \\
1 & 1 & 1 \\
1 & 1 & 1
\end{bmatrix}
\]

### 5×5 Kernel

\[
\frac{1}{25}
\begin{bmatrix}
1 & \cdots & 1 \\
\vdots & \ddots & \vdots \\
1 & \cdots & 1
\end{bmatrix}
\]

---

## Results

- 3×3 filter preserves more details.
- 5×5 filter produces moderate smoothing.
- 7×7 filter provides stronger blurring and noise reduction.

---

## Output

The notebook displays:

- Original Image
- 3×3 Filtered Image
- 5×5 Filtered Image
- 7×7 Filtered Image

for visual comparison.

---

## Author

Velaga Manikanta Sai

B.Tech – Data Science

Computer Vision Laboratory
