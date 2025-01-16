# Human Pose Estimation using OpenCV

## Overview
A simple and efficient system to detect human body keypoints (e.g., shoulders, elbows, knees) using OpenCV and TensorFlow. It processes images and videos, rendering a skeleton overlay, and includes a web-based app for real-time interaction.

---

## Features
- Detects and visualizes human body keypoints.
- Works with static images and video streams.
- Real-time interaction using a Streamlit web app.
- Lightweight and easy to deploy.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SiddharthMali/Human-Pose-Estimation.git
   cd Human-Pose-Estimation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run estimation_app.py
   ```

---

## Usage
1. **For Images:**
   ```bash
   python pose_estimation.py --image_path <path_to_image>
   ```

2. **For Videos:**
   ```bash
   python pose_estimation_Video.py --video_path <path_to_video>
   ```

3. **For Real-Time Interaction:**
   Run the Streamlit app and open the local URL in a browser.

---

## Project Structure
```
Human-Pose-Estimation/
├── estimation_app.py        # Streamlit app
├── pose_estimation.py       # Image processing
├── pose_estimation_Video.py # Video processing
├── requirements.txt         # Dependencies
├── README.md                # Project info
└── assets/                  # Sample images/videos
```

---

## Example Output
### Static Image:
![Example](Human-Pose-Estimation-OpenCV-main/OutPut-image.png)

### Another Example:
![Output Example](Human-Pose-Estimation-OpenCV-main/another output.PNG)

---

## References
1. [OpenCV Documentation](https://docs.opencv.org/)
2. [TensorFlow Models](https://www.tensorflow.org/)
3. [MediaPipe Pose Estimation](https://google.github.io/mediapipe/solutions/pose.html)

---

## Author
**Siddharth Mali**

Contributions and feedback are welcome!

 
 
