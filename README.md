# Player Re-Identification in Sports Footage

## Overview
This project focuses on identifying and tracking individual players in sports video footage using computer vision techniques. We used a fine-tuned YOLOv11 model for real-time player detection and integrated feature-based tracking to assign consistent IDs to players across different frames and camera angles.

## Technologies Used
- YOLOv11 (Object Detection)
- Deep SORT (Tracking & Re-identification)
- OpenCV (Video Processing)
- Python (Development)
- PyTorch (Model Training)

## How it Works
1. **Video Input** – Accepts single or multi-camera sports video.
2. **Player Detection** – Detects players, referees, and the ball using YOLOv11.
3. **Feature Extraction** – Embeds appearance features of players.
4. **Tracking** – Applies Deep SORT for temporal tracking and consistent ID assignment.
5. **Output** – Displays bounding boxes and player IDs on video frames.

## Results
- Accurate player tracking in real-time (15+ FPS).
- Handles occlusion, fast movements, and camera switches.
- Useful for sports analytics, AR overlays, and automated highlights.

## Applications
- Player analytics and performance evaluation
- Match summarization and replays
- Broadcasting enhancement in live matches

