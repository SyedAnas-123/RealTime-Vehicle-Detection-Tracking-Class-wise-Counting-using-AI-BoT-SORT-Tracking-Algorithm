Title :
Real-Time Object Detection, Tracking & Vehicle Counting 🎥🚗

Overview :
A demonstration of detecting, tracking, and counting vehicles and people in traffic video using YOLOv11 + BoT-SORT + OpenCV.

Description :
This project performs real-time vehicle and pedestrian detection using YOLOv11 (pretrained on COCO), tracks each object using BoT-SORT, computes center points to detect crossing a predefined line, and yields class‑wise counts without double counting.

Key Features :

🚘 Vehicle detection: cars, buses, motorbikes, trucks

🧍‍♂‍ Person detection and counting, including bikes with multiple riders

🎯 Unique ID-based tracking across frames (via BoT‑SORT)

📍 Center point computation for crossing events

🔴 Red line threshold counting logic in OpenCV

🧮 Class-wise dynamic count tracking with Python dictionaries


Dependencies :
- Python 3.x  
- ultralytics (YOLOv11)  
- OpenCV  
- BoT-SORT tracking  
- Other standard libraries: numpy, cv2, collections


Usage :
1. Place your input video (e.g.,  ‘traffic.mp4’)
2. Run detection and tracking (YOLOv11 + BoT‑SORT)
3. Output saved as annotated video with counts in specified output folder


Applications :
- Smart traffic control  
- Urban planning & traffic analysis  
- Security and surveillance  
- Automated traffic counting and monitoring


https://github.com/SyedAnas-123/RealTime-Vehicle-Detection-Tracking-Class-wise-Counting-using-AI-BoT-SORT-Tracking-Algorithm/blob/main/Screenshot%202025-07-30%20004913.png?raw=true
