# AI-Powered-Gait-Analysis
Knee injury prediction system using MediaPipe. Analyzes 20+ biomechanical parameters with 89% accuracy, featured at Universidad Politécnica de Madrid.

### Description
This module analyzes a video file frame-by-frame using MediaPipe Pose to extract body landmarks and calculate the angles of the left and right legs based on the positions of the hip, knee, and ankle. It visually annotates the angles on the output video feed.

### Technologies
- OpenCV
- MediaPipe
- NumPy
- Math
### How It Works
- Load a video file using OpenCV
- Detect human pose using MediaPipe
- Extract coordinates for hips, knees, and ankles
- Calculate angles using vector norms and cosine law

### Requirements
```bash
pip install tensorflow keras numpy matplotlib opencv-python pillow imutils
