# GMM-to-determine-foreground-of-a-video
Use GMM to determine foreground of a video

This experiment focuses on using a Gaussian Mixture Model (GMM) to separate the foreground from the background in a video. GMM is a probabilistic model that can adapt to dynamic scenes and is widely used for background subtraction in video processing.

## 🧪 Tasks

### ✅ Task 1: Generate Background Model using GMM (K=3)
- Use a Gaussian Mixture Model with **K = 3** components to model the background of the given video.
- Process a set of initial frames to build the background model.

### ✅ Task 2: Use Background Model to Determine Foreground
- Apply the background model to each frame of the video.
- Subtract the background and extract the foreground regions (i.e., moving objects).
- Display or save the results showing foreground detection in each frame.

---

## 🛠️ Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `opencv-python` (`cv2`)
  - `scikit-learn` (for GMM implementation)
  - `matplotlib` (for visualization, optional)

---
