# Car Detection Using Drone

## Overview
Detects cars in images using MobileNetSSD, suitable for traffic monitoring, autonomous driving, and security applications.

## Dataset
Images collected from drones: [Kaggle Dataset](https://www.kaggle.com/datasets/pear2jam/cars-drone-detection)

## Approach
- **Preprocessing:** Resize and normalize images.  
- **Model:** MobileNetSSD pre-trained on COCO, fine-tuned on car dataset.  
- **Evaluation:** Metrics include Precision (92.5%), Recall (90%), mAP (91.2%).  

## Libraries
TensorFlow, OpenCV, Matplotlib, Pillow, NumPy

## Usage
```bash
git clone <repo_link>
pip install -r requirements.txt
python detect_cars.py --image_dir path/to/images
