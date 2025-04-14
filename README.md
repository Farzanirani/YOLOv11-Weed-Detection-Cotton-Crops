# YOLOv11-Weed-Detection

This repository contains the implementation of weed detection and segmentation using YOLOv11n-seg, developed by Farzan Irani as part of an M.Tech project. The project introduces a novel weed density mapping metric and compares YOLOv11n-seg with YOLOv8n-seg.

## Dataset
- Source: Roboflow "M.TECH" collection (https://universe.roboflow.com/ashok-malhotra-y84wx/m.tech/dataset/31)
- Weed classes: 16 species (e.g., Cotton, Goosegrass)

## Implementation
- Framework: Ultralytics
- Training parameters: 100 epochs, batch=4, imgsz=640, etc. (see train_yolov11.py) (This is what I used!!)

## Results
- YOLOv11n-seg: Box mAP@0.5 = 0.8188, Mask mAP@0.5 = 0.8167, Weed Density = 0.3087
- YOLOv8n-seg: Training in progress, results to be updated

## Usage
1. Clone this repository: `git clone https://github.com/yourusername/YOLOv11-Weed-Detection.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the training script: `python train_yolov11.py`

## Acknowledgments
Thanks to Roboflow for the dataset and Ultralytics for the YOLO framework.

## Future Updates
- YOLOv8n-seg results
- Additional visualizations