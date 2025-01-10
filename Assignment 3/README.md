# CS-GY-6613 / CS370 Assignment 3
## Submission by: Naman Vashishta (NV2375 N11740506)

This repository contains the code and documentation for **Assignment 3** of CS-GY-6613. In this assignment, you will work on sports analytics by applying object detection and tracking techniques to track soccer players and the ball using Kalman filters and object detection algorithms.

## Assignment Tasks

### Task 1: Faster RCNN
- **Objective**: Implement object detection using Faster RCNN.
- **Details**: You do not need to implement the Faster-RCNN detector from scratch, but you should incorporate the source code and demonstrate how the Faster-RCNN algorithm works. The steps of Faster-RCNN should be explained clearly in markdown cells with visualizations of the output at each stage.
- **Key Steps**:
  - Preprocess the video frames.
  - Use a pretrained model (trained on the COCO dataset) for object detection. You can use a pretrained backbone like **ResNet**.
  - Ensure all steps of the algorithm are explained with appropriate visualizations.
  - The object classes to detect are **person** and **ball**, both included in the COCO dataset.
  - Provide explanations of each block of the Faster-RCNN process, as shown in the provided videos.

### Task 2: Deep-SORT
- **Objective**: Implement the **Deep-SORT** (Simple Online and Realtime Tracking) algorithm for multi-object tracking.
- **Details**: The tracking should work in conjunction with the object detector from Task 1, tracking both soccer players and the ball in the video.
- **Key Steps**:
  - Understand the Deep-SORT algorithm by reading the referenced papers and watching the explanatory videos.
  - Draw the architecture of the tracking solution using a diagram tool compatible with GitHub rendering (e.g., **Excalidraw**).
  - Write a summary of the key components of the Deep-SORT architecture, including the equations of the Kalman filter and an explanation of the **Hungarian Algorithm**.
  - Implement the Deep-SORT algorithm that works with the object detector from Task 1.
  - Track the soccer ball and players in the video and superimpose bounding boxes on the video frames.
  - Submit the video showing the bounding boxes for the soccer players and the ball.

### Requirements
- **Faster RCNN**: Use a pretrained model (trained on COCO) for object detection.
- **Deep-SORT**: Implement Deep-SORT for multi-object tracking with the Kalman filter and Hungarian Algorithm.
- **Video Processing**: Process the video frames and annotate the bounding boxes for detected objects.
- **Pytube**: For downloading YouTube videos to use for testing the object detection and tracking system.

### Directory Structure
- `Assignment3/`: Contains all code and notebooks for Assignment 3.
  - `Task1_FasterRCNN/`: Code and explanations for Faster-RCNN implementation.
  - `Task2_DeepSORT/`: Code and explanations for Deep-SORT tracking implementation.
  - `test_video.mp4`: The video file used for testing and submission.
- `README.md`: This file, providing an overview of the assignment.

## Submission Instructions
- Submit a video that demonstrates the results of the object detection and tracking, with bounding boxes superimposed on the test video.
- Include the notebook with all steps and explanations for Faster-RCNN and Deep-SORT.
- Ensure that all equations, key concepts, and algorithmic steps are clearly documented in markdown cells.

## Contact
For any questions or clarifications, feel free to contact me at `NV2375@nyu.edu`.

