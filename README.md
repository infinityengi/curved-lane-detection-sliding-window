# Lane Detection using Sliding Window for Curved Lanes

This repository implements a lane detection algorithm designed to detect curved lanes on the road using a sliding window approach. The method uses image processing techniques to identify lane lines within a predefined Region of Interest (ROI), which helps focus the detection on the relevant road area and improves performance and accuracy.

## Features
- Sliding window technique to detect lane pixels for curved lanes
- ROI mask creation with customizable polygon vertices
- Debug mode for detailed internal state outputs
- Modular Python code using OpenCV and NumPy

## Installation

```bash
pip install -r requirements.txt
