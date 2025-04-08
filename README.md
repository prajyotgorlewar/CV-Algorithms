# 🧠 Feature Detection and Matching using OpenCV

This repository demonstrates the implementation of classic computer vision techniques using OpenCV in Python, including:

- ✅ Harris Corner Detection
- ✅ Shi-Tomasi Corner Detection
- ✅ Keypoint Matching with ORB
- ✅ RANSAC-based Outlier Removal and Homography Estimation

---

## 📁 Files

- `main.ipynb`: Jupyter notebook containing all implementations with visualizations.
- `image1.jpg`, `image2.jpg` & `image3.jpg`: Sample input images used for testing (you can replace these with your own).

---

## 📌 Features Implemented

### 1. Harris Corner Detection
Detects corners based on the eigenvalues of the image gradient matrix.

> 📍 Corners are marked in **green** on the image.

---

### 2. Shi-Tomasi Corner Detection
An improved version of Harris that selects corners with the strongest quality measure.

> 📍 Corners are marked in **cyan** circles on the image.

---

### 3. ORB Keypoint Matching + RANSAC
- Detects keypoints and descriptors using ORB.
- Matches them using Brute-Force matcher.
- Applies RANSAC to filter out outliers and estimate a homography.

> 📍 Inlier matches are visualized with **colored lines**.

---

## 🔧 Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib

Install dependencies using:

```bash
pip install opencv-python numpy matplotlib
