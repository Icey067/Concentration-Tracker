# Concentration-Tracker
A real-time Concentration Tracker built with MediaPipe and OpenCV.
It detects face, eyes, and head pose to estimate focus level — useful for online-exam monitoring or attention-tracking demos.

Features
Real-time face & eye detection using MediaPipe Face Mesh
Eye-closure timer (warns if eyes closed > 3 s)
Auto-exit when no face detected > 10 s
Concentration score bar (0-100 %)
Detects noise and gives warning
Setup & Run
Install dependencies
pip install -r requirements.txt
