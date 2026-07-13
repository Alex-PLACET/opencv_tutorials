# OpenCV-Python Tutorials

A collection of the official [OpenCV-Python tutorials](https://docs.opencv.org/5.0/tutorials/tutorials.html) converted into interactive Jupyter notebooks — with live code, visualizations, and widgets.

## 📦 Getting Started

### Using Conda (recommended)

```bash
conda env create -f environment.yml
conda activate opencv-tutorial
jupyter lab
```

### Using pip

```bash
pip install -r requirements.txt
jupyter lab
```

Then open any notebook from the list below and run all cells.

## 📚 Tutorials

### 1. Core Operations
- [Basic Ops](notebooks/py_core/py_basic_ops.ipynb) — image loading, display, and basic manipulation
- [Image Arithmetics](notebooks/py_core/py_image_arithmetics.ipynb) — arithmetic and bitwise operations on images
- [Optimization](notebooks/py_core/py_optimization.ipynb) — performance measurement and optimization techniques

### 2. Image Processing
- [Colorspaces](notebooks/py_imgproc/py_colorspaces/py_colorspaces.ipynb) — converting between color spaces (RGB, HSV, LAB, etc.)
- [Thresholding](notebooks/py_imgproc/py_thresholding/py_thresholding.ipynb) — simple, adaptive, and Otsu's thresholding
- [Filtering](notebooks/py_imgproc/py_filtering/py_filtering.ipynb) — 2D convolution, blurring, and image filtering
- [Gradients](notebooks/py_imgproc/py_gradients/py_gradients.ipynb) — Sobel, Scharr, and Laplacian edge detection
- [Canny](notebooks/py_imgproc/py_canny/py_canny.ipynb) — Canny edge detection
- [Morphological Ops](notebooks/py_imgproc/py_morphological_ops/py_morphological_ops.ipynb) — erosion, dilation, opening, closing
- [Geometric Transformations](notebooks/py_imgproc/py_geometric_transformations/py_geometric_transformations.ipynb) — scaling, rotation, affine, and perspective transforms
- [Pyramids](notebooks/py_imgproc/py_pyramids/py_pyramids.ipynb) — image pyramids and blending
- **Contours**
  - [Contours Begin](notebooks/py_imgproc/py_contours/py_contours_begin/py_contours_begin.ipynb) — finding and drawing contours
  - [Contour Features](notebooks/py_imgproc/py_contours/py_contour_features/py_contour_features.ipynb) — moments, area, perimeter, bounding shapes
  - [Contour Properties](notebooks/py_imgproc/py_contours/py_contour_properties/py_contour_properties.ipynb) — solidity, extent, aspect ratio, etc.
  - [Contours Hierarchy](notebooks/py_imgproc/py_contours/py_contours_hierarchy/py_contours_hierarchy.ipynb) — parent-child relationships in contours
  - [Contours More Functions](notebooks/py_imgproc/py_contours/py_contours_more_functions/py_contours_more_functions.ipynb) — convexity defects, point-polygon tests
- **Histograms**
  - [Histogram Begins](notebooks/py_imgproc/py_histograms/py_histogram_begins/py_histogram_begins.ipynb) — computing and plotting histograms
  - [Histogram Equalization](notebooks/py_imgproc/py_histograms/py_histogram_equalization/py_histogram_equalization.ipynb) — global and CLAHE equalization
  - [2D Histogram](notebooks/py_imgproc/py_histograms/py_2d_histogram/py_2d_histogram.ipynb) — 2D color histograms
  - [Histogram Backprojection](notebooks/py_imgproc/py_histograms/py_histogram_backprojection/py_histogram_backprojection.ipynb) — object localization via backprojection
- [Template Matching](notebooks/py_imgproc/py_template_matching/py_template_matching.ipynb) — sliding window template matching
- [Houghlines](notebooks/py_imgproc/py_houghlines/py_houghlines.ipynb) — line detection with Hough transform
- [Houghcircles](notebooks/py_imgproc/py_houghcircles/py_houghcircles.ipynb) — circle detection with Hough transform
- [Grabcut](notebooks/py_imgproc/py_grabcut/py_grabcut.ipynb) — interactive foreground extraction
- [Watershed](notebooks/py_imgproc/py_watershed/py_watershed.ipynb) — marker-based watershed segmentation
- [Fourier Transform](notebooks/py_imgproc/py_transforms/py_fourier_transform/py_fourier_transform.ipynb) — DFT for frequency-domain filtering

### 3. Feature Detection & Description
- [Features Meaning](notebooks/py_features/py_features_meaning/py_features_meaning.ipynb) — what are image features?
- [Features Harris](notebooks/py_features/py_features_harris/py_features_harris.ipynb) — Harris corner detection
- [Shi Tomasi](notebooks/py_features/py_shi_tomasi/py_shi_tomasi.ipynb) — good features to track
- [SIFT Intro](notebooks/py_features/py_sift_intro/py_sift_intro.ipynb) — scale-invariant feature transform
- [FAST](notebooks/py_features/py_fast/py_fast.ipynb) — FAST corner detection
- [ORB](notebooks/py_features/py_orb/py_orb.ipynb) — oriented FAST and rotated BRIEF
- [Matcher](notebooks/py_features/py_matcher/py_matcher.ipynb) — brute-force and FLANN feature matching
- [Feature Homography](notebooks/py_features/py_feature_homography/py_feature_homography.ipynb) — homography estimation and object detection

### 4. Video Analysis
- [Background Subtraction](notebooks/py_video/py_bg_subtraction/py_bg_subtraction.ipynb) — MOG2 and KNN background subtraction
- [Lucas Kanade](notebooks/py_video/py_lucas_kanade/py_lucas_kanade.ipynb) — optical flow with Lucas-Kanade method
- [Meanshift](notebooks/py_video/py_meanshift/py_meanshift.ipynb) — mean-shift and CAMShift object tracking

### 5. Camera Calibration & 3D Reconstruction
- [Calibration](notebooks/py_calib3d/py_calibration/py_calibration.ipynb) — camera calibration with checkerboard
- [Pose](notebooks/py_calib3d/py_pose/py_pose.ipynb) — pose estimation from known patterns
- [Epipolar Geometry](notebooks/py_calib3d/py_epipolar_geometry/py_epipolar_geometry.ipynb) — epipolar lines and fundamental matrix
- [Depthmap](notebooks/py_calib3d/py_depthmap/py_depthmap.ipynb) — stereo correspondence and depth map

### 6. Machine Learning
- [K-Means Understanding](notebooks/py_ml/py_kmeans/py_kmeans_understanding/py_kmeans_understanding.ipynb) — theory and intuition behind k-means
- [K-Means in OpenCV](notebooks/py_ml/py_kmeans/py_kmeans_opencv/py_kmeans_opencv.ipynb) — using `cv.kmeans()` for color quantization and data clustering

### 7. Computational Photography
- [HDR](notebooks/py_photo/py_hdr/py_hdr.ipynb) — high dynamic range imaging and tone mapping
- [Inpainting](notebooks/py_photo/py_inpainting/py_inpainting.ipynb) — image restoration with inpainting
- [Non-Local Means](notebooks/py_photo/py_non_local_means/py_non_local_means.ipynb) — NLM denoising algorithm
- [Chromatic Aberration](notebooks/py_photo/py_chromatic_aberration/py_chromatic_aberration.ipynb) — correcting chromatic aberration

## 🔗 References

- [Official OpenCV Tutorials](https://docs.opencv.org/5.0/tutorials/tutorials.html)
- [OpenCV-Python Documentation](https://docs.opencv.org/5.0/)
- [GitHub Repository](https://github.com/Alex-PLACET/opencv_tutorials)

## 📄 License

This project is licensed under the Apache License 2.0 — see [LICENSE](LICENSE) for details.

## 🤝 Contributing

Contributions are welcome! Feel free to open a pull request with improvements, fixes, or additional tutorials at [github.com/Alex-PLACET/opencv_tutorials](https://github.com/Alex-PLACET/opencv_tutorials).