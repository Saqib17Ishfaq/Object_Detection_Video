Real-Time Object Detection with MobileNet SSD and YOLOv3
<!-- Add a demo gif if available -->

A Python-based object detection system that implements both MobileNet SSD and YOLOv3 models for real-time detection from a webcam or static images. The project includes a user interface for model selection, performance visualization, and supports a street scene dataset.

📌 Features
Dual Model Support
Choose between:
    MobileNet SSD (faster, lightweight)
    YOLOv3 (more accurate, slower)
Multiple Input Sources:
    Real-time detection using your webcam
    Static image detection from dataset
Interactive UI:
    Buttons to start/stop detection
    Live accuracy and confidence visualization
Dataset Integration:
    Works with a labeled street scene dataset
    Performance Metrics Displayed
Confidence scores:
    Detection consistency over time
    Model comparison in real time

🧠 Model Information
📦 MobileNet SSD
Lightweight model suitable for real-time applications
Detects 21 classes (PASCAL VOC)
High speed, lower accuracy
Ideal for performance-constrained environments

🎯 YOLOv3
Heavier model with high accuracy
Detects 80 classes (COCO dataset)
More computationally intensive
Better suited for complex scenes with diverse objects

📊 Performance Metrics
The system monitors and displays the following metrics in real time:
Average confidence score per frame
Detection consistency across frames
Comparative visualization between MobileNet SSD and YOLOv3

🔧 Prerequisites
Python ≥ 3.6
OpenCV 4.x
NumPy
Matplotlib
IPython
PyTorch (for future model integration or YOLO extensions)
Jupyter Notebook (for interactive GUI usage)

🚀 Installation
Clone the repository:
  bash
    git clone https://github.com/yourusername/object-detection-project.git
    cd object-detection-project
Install dependencies:
  bash
    pip install -r requirements.txt
    
📈 Future Enhancements
Add support for video file input (MP4, AVI)
Implement custom model training or fine-tuning
Integrate more models (e.g., Faster R-CNN, EfficientDet)
Add object tracking across frames (e.g., using SORT or Deep SORT)
Implement batch processing for multiple static images

📸 Demo
See the demo.gif or run the Jupyter Notebook to preview the detection pipeline.

📂 Dataset
The project works best with urban/street scene images. Ensure your dataset includes:
JPEG/PNG images
Corresponding annotation files (Pascal VOC or YOLO format)

👨‍💻 Author
Muhammad Saqib Ishfaq (Saqib17Ishfaq)
