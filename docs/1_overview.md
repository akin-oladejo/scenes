# Project: Real-Time Multi-Person Instance Segmentation (YOLOv8-Seg)

## 1. Project Goal

To develop a high-performance, real-time computer vision application capable of performing instance segmentation on all detected persons within a live video stream or pre-recorded video file. The output must clearly and distinctly segment every individual, providing a pixel-level mask for each person instance.

## 2. Core Technologies

| Component   | Purpose  | Detail   |
| ----------- | ---------------------- | -------------------------- |
Model | Instance Segmentation  | YOLOv8-Seg (e.g., yolov8n-seg.pt or yolov8m-seg.pt)                          |
| Language    | Primary Implementation | Python                                                                       |
| Libraries   | Vision/Processing      | Ultralytics, OpenCV (cv2), NumPy                                             |
| Input       | Source Data            | Video File (.mp4, .avi) or Webcam Stream                                     |
| Output      | Godot Scene Render          | Real-time display with colored masks in 3d scene |

## 3. Key Objectives

1. Successfully set up the Python environment with GPU support (if available).

2. Integrate the YOLOv8-Seg model and load it for inference.

3. Create a robust video processing loop that reads frames sequentially.

4. Perform inference on each frame to obtain masks for all people.

5. Visualize the results by applying the unique segmentation masks to a stylized environment within godot

6. Maintain high frame rate (FPS) suitable for "real-time" performance.