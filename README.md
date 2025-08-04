# Security System Using OpenCV

This is a minor project developed to explore and understand the fundamentals of **Computer Vision** using **OpenCV**. It simulates a basic real-time security system that automatically starts recording video when a face or body is detected via webcam input.

---

## Features

- Real-time face and full-body detection using Haar Cascades  
- Automatically starts recording when a person is detected  
- Continues recording for a few seconds after detection stops  
- Saves video files with timestamped filenames  
- Outputs stored in a `recordings/` folder  

---

## Tech Stack

| Tool/Library | Purpose |
|--------------|---------|
| Python       | Core programming language |
| OpenCV       | Face & body detection, video processing |
| Haar Cascades | Pre-trained models for object detection |

---

## How It Works

1. Webcam feed is analyzed frame-by-frame.
2. If a face or body is detected:
   - A new video file is created.
   - Recording starts immediately.
3. If detection stops:
   - Recording continues for 5 seconds.
   - Then the video is saved and recording stops.
4. The system keeps monitoring in real time.

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aadesh006/Security-System-Using-OpenCV.git