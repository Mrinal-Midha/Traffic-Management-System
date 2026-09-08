# Traffic-Management-System

A simulated multi-lane traffic-light control system based on vehicle-count detection.

## How it works
- `test1.py`, `test2.py`, `test3.py` — progressive iterations of the traffic-light control logic. `test3.py` is the most complete version, using OpenCV's Haar cascade classifier to detect and count vehicles in video frames, and adjusting green-light duration based on the count.
- `lane1.mp4`–`lane4.mp4` — sample lane footage used as the video source for detection.

## Tech stack
Python, OpenCV (Haar cascade vehicle detection).

## Running locally
```bash
pip install opencv-python
python test3.py
```
Update the hardcoded video/cascade file paths near the top of `test3.py` to point to your own local files before running.

## Status
Simulation/prototype tested on sample footage — not deployed to real hardware or a live traffic system.
