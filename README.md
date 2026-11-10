# 📸 Snapchat Filters Using Python & OpenCV

## 📌 Project Overview

Snapchat Filters is a Python-based computer vision project that applies creative image filters and Snapchat-style face effects using OpenCV.

The project allows users to apply different visual effects to photographs and use real-time webcam filters. It combines image processing, face detection, and facial effects to create an interactive filtering experience inspired by Snapchat.

## ✨ Features

### 1. Basic Image Filters

- **Grayscale:** Converts images into black and white.
- **Sepia:** Creates a classic brown-toned photographic effect.
- **Vintage:** Adds an old-photo effect with noise and vignette.
- **Warm:** Enhances warm colour tones.
- **Cool:** Adds cool colour tones.
- **Vignette:** Darkens image edges while keeping the centre bright.
- **Invert:** Inverts image colours.
- **Colour Pop:** Keeps the detected face in colour while converting the remaining image into grayscale.

### 2. Snapchat-Style Face Filters

- **Cartoon Filter:** Creates a cartoon-style image effect.
- **Beauty Filter:** Applies a beauty enhancement effect.
- **Dog Filter:** Adds dog-themed facial effects.
- **Sunglasses Filter:** Adds sunglasses to the face.
- **Moustache Filter:** Adds a moustache effect.
- **Bunny Filter:** Adds bunny-themed facial effects.
- **Crown Filter:** Adds a crown effect.
- **Big Eyes Filter:** Creates a big-eyes effect.

### 3. Real-Time Webcam Filters

The project also supports applying filters directly to a live webcam feed.

Features include:

- Real-time webcam access using OpenCV.
- Automatic face detection.
- Live face-filter application.
- Mirror mode for selfie-style viewing.
- FPS (Frames Per Second) display.
- Capture and save filtered snapshots.
- Switch between different filters using keyboard shortcuts.

## ⌨️ Keyboard Controls

| Key | Function |
|---|---|
| 0 | No Filter |
| 1 | Grayscale |
| 2 | Sepia |
| 3 | Vintage |
| 4 | Cartoon |
| 5 | Beauty |
| 6 | Dog |
| 7 | Sunglasses |
| 8 | Moustache |
| 9 | Bunny |
| C | Crown |
| B | Big Eyes |
| S | Save Snapshot |
| Q | Quit Application |

## 🛠️ Technologies Used

- **Python** – Main programming language.
- **OpenCV (cv2)** – Image processing, webcam access, and computer vision.
- **NumPy** – Image array manipulation and mathematical operations.
- **Matplotlib** – Image visualization.
- **Jupyter Notebook** – Development and experimentation environment.

## 📂 Project Structure

```text
Snapchat-Filters/
│
├── Snapchat_Filters.ipynb
├── requirements.txt
├── README.md
└── assets/                 # If required by your filters
    └── filter images
```

*Note: Include the assets folder only if your project uses external filter images.*

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd Snapchat-Filters
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Snapchat_Filters.ipynb` and execute the cells in order.

## 🎥 Running the Webcam Application

To start the real-time webcam filter application, execute:

```python
live_filter_webcam()
```

Make sure your webcam is connected and accessible.

**Note:** The webcam functionality requires a local Python environment with camera and display access. It may not work in cloud-based notebook environments.

## 🎯 Project Objective

The main objective of this project is to understand and implement computer vision and image processing techniques using Python and OpenCV.

It demonstrates how image transformations, face detection, and real-time video processing can be combined to create interactive Snapchat-style filters.

## 🚀 Future Enhancements

- Add more creative face filters.
- Improve facial landmark detection.
- Develop a user-friendly graphical interface.
- Add real-time filter intensity controls.
- Support video recording with applied filters.
- Improve real-time processing performance.

## 👩‍💻 Author

**Vaishnavi Bhakre**

GitHub: https://github.com/vaishnavi-techie

## ⭐ Acknowledgement

This project was developed as a practical implementation of Python, OpenCV, and computer vision concepts.

If you find this project interesting, feel free to explore and improve it!