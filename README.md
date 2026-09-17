# 🐘 Ganesha Metallic Gold Animation

A Python project that transforms a Ganesha image into a beautiful metallic-gold artwork using OpenCV, NumPy, and Turtle Graphics.

## ✨ Features

- 🔍 Automatic contour detection using OpenCV
- 🎨 Metallic-gold stroke and fill effects
- 🕳️ Smart handling of inner spaces and details
- 🐢 Turtle Graphics visualization
- 🖼️ Image processing and contour rendering
- ⚙️ Customizable colors, threshold, and drawing size

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Turtle Graphics

## ⚙️ How It Works

1. Loads the Ganesha image using OpenCV.
2. Resizes the image for better display.
3. Converts the image to grayscale.
4. Applies binary thresholding.
5. Detects contours and their hierarchy.
6. Identifies outer shapes and inner holes.
7. Uses Turtle Graphics to draw the contours in metallic gold.

## 🚀 How to Run

### Install dependencies

```bash
pip install opencv-python numpy
