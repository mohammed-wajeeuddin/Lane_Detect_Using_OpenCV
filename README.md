# 🛣️ Lane Detection Using OpenCV – Final Project

This project implements a **real-time lane detection system** using Python and OpenCV. The goal is to process video frames to identify and highlight lane lines, an essential step for advanced driver assistance systems (ADAS) and autonomous vehicles.

#: Jupyter notebook containing the complete implementation of the lane detection pipeline, from video input processing to lane marking overlay.

## 🎯 Objectives

- Process input video to detect lane lines
- Apply computer vision techniques:
  - Grayscale conversion
  - Gaussian blur
  - Canny edge detection
  - Region of interest (ROI) masking
  - Hough Line Transformation
- Overlay detected lanes onto video frames

## 🧰 Tools & Libraries

- Python
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## 🎥 Features

- Frame-by-frame video processing
- Edge and line detection using Canny and Hough algorithms
- ROI masking to focus on lane-relevant areas
- Lane line overlay for visualization

## 🚀 How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Upload a road video (MP4 format recommended)
3. Run all cells to process the video and visualize the output with lane markings

## 📌 Potential Enhancements

- Lane curvature detection and smoothing
- Lane departure warning system
- Real-time camera input integration
- Support for curved roads using polynomial fitting

## 📬 Author

**Wajeeuddin Mohammed**  
📧 wajeeuddin21012000@gmail.com  
🎓 M.S. Data Science | Golden Gate University

---

> *This project demonstrates practical computer vision applications in traffic and autonomous systems.*
