# Multi-Object Detection and Tracking using VisDrone

This project implements a multi-object detection and tracking system using YOLOv5 and DeepSORT on the VisDrone dataset.

## Workflow

1. Download and preprocess VisDrone dataset
2. Train YOLOv5 at 640 resolution
3. Fine-tune YOLOv5 at 1280 resolution
4. Track objects in video using DeepSORT
5. Evaluate using mAP@0.5 and FPS

## Files

* `multi_object_tracking_visdrone.ipynb` : full implementation notebook
* `best.pt` : trained model weights
* `final_output.mp4` : tracked output video

## Metrics

* Detection evaluation using mAP@0.5
* Tracking evaluation using FPS
