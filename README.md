# Football Player Tracking and Analysis ⚽

## Project Overview

Football Player Tracking and Analysis is a computer vision project developed using Python, YOLO (Ultralytics), and OpenCV. The project detects and tracks players in football videos, assigns tracking IDs, records player positions, and analyzes movement trajectories, estimated speeds, and detection counts. The results are presented through tracking data, graphs, and an analytics dashboard.

## Project Objective

The main objective of this project is to detect and track players in a football video using computer vision techniques. It records player positions and tracking IDs, stores tracking information in CSV files, and visualizes movement patterns and detection statistics through graphs and an analytics dashboard.

## Technologies Used

- Python
- YOLO (Ultralytics)
- OpenCV
- Pandas and NumPy
- Matplotlib
- Google Colab

## Features

- Player detection and object tracking with tracking IDs
- Bounding boxes displayed around detected players
- Tracking data exported to CSV files
- Player movement trajectory visualization
- Estimated movement speed analysis
- Detection count analysis
- Analytics dashboard with graphs

## Project Files

- `Football_Player_Tracking_Analysis (1).ipynb` — Google Colab notebook containing the project code
- `player_tracking_data (1).csv` — Detailed player tracking records
- `player_tracking_summary.csv` — Summary of tracking IDs and estimated speeds
- `football_analytics_dashboard (2).png` — Analytics dashboard with graphs
- `football_tracked.mp4` — Processed football video showing detected players with bounding boxes and tracking IDs

## Project Workflow

1. Upload the football video to Google Colab.
2. Load the YOLO model for object detection.
3. Detect players in each video frame.
4. Track detected objects across frames and assign tracking IDs.
5. Record player positions, timestamps, and detection confidence scores.
6. Export the tracking data to CSV files.
7. Analyze movement patterns and estimated speeds.
8. Generate graphs and an analytics dashboard.
9. Save the processed video with bounding boxes and tracking IDs.

## 🎥 Tracked Football Video

Watch or download the processed football video showing player detection, bounding boxes, and tracking IDs.

[▶️ Open Football Tracking Video](https://github.com/Keerthika137/Football-Player-Tracking-Analysis/raw/48e4314f42c556ac89da60a4f3534d28d8f0337d/football_tracked.mp4)

## Analytics Dashboard

The dashboard presents visual summaries of player tracking data, detection counts, and estimated movement speeds.

![Football Analytics Dashboard](football_analytics_dashboard%20%282%29.png)

## Future Improvements

- Improve player detection and tracking accuracy
- Implement team classification
- Analyze individual player performance
- Explore tactical movement patterns
- Integrate ball detection and tracking

## Note on Estimated Speed

Estimated movement speeds are measured in pixels per second. These values do not represent actual speeds in km/h. Real-world speed estimation requires camera calibration and information about the playing field.

## Author

**Keerthika G.**
