# Color Object Tracking with OpenCV

A computer vision project that tracks colored objects in video streams using HSV color segmentation and visualizes their motion trajectory.

## Overview

This project detects a target object based on its color, calculates its centroid, and tracks its movement over time.

The tracked trajectory is visualized by drawing the object's path across video frames.

## Features

* HSV color segmentation
* Binary mask generation
* Morphological filtering
* Contour detection
* Object centroid estimation using image moments
* Real-time trajectory visualization

## Pipeline

1. Read video frame
2. Convert BGR image to HSV
3. Apply color thresholding
4. Remove noise using morphological operations
5. Detect contours
6. Select the largest contour
7. Compute object centroid
8. Store object positions
9. Draw trajectory path
10. Display tracking results

## Technologies

* Python
* OpenCV
* NumPy

## Concepts Covered

* Color Spaces (HSV)
* Image Segmentation
* Morphological Operations
* Contour Analysis
* Image Moments
* Object Tracking
* Motion Visualization

## Example Output

The algorithm detects a blue ball and continuously tracks its center position while drawing its motion path.

## Future Improvements

* Multi-color tracking
* Multi-object tracking
* Kalman Filter integration
* Real-time webcam tracking
* Speed estimation
* Direction analysis

## Learning Objectives

This project was built to understand how color-based object tracking works and how object trajectories can be extracted from video sequences using classical computer vision techniques.
