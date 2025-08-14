# Traffic-Signs-Detection
This assignment focuses on developing a Traffic Sign Recognition
system using the latest YOLO (You Only Look Once) versions (8+)
object detection algorithm, which offers both speed and accuracy,
two critical pilla

# DataSet
- Name: Car Detection Dataset 
- Source: https://www.kaggle.com/datasets/pkdarabi/cardetection
- Format: Images + annotations

  # Tools & Environment:
  - Language :Python
  - Libraries: YOLOv: for object detection
  - PyTorch or TensorFlow: as backend for training and inference.
  - OpenCV: for image processing and real-time video
  - Matplotlib/ Seaborn: For performance visualization
  - Annotations Tool: for labeling

  # Steps:
  # 1.Data Preparation:
  - Download the extracted dataset + verify and clean annotations
  # 2.Model SetUp
  - Clone YOLO repositories
  - Modify data.yaml to include custom classes
  - Load pre-trained YOLO weights for transfer learning
  # 3. Trainin & Evaluation:
  - Tested Models: VOLOv5 & YOLOv8
  - Metrics used: mAP(mean Average Precision), Precision/Recall, and IoU(Intersection over Union)
  - Selected YOLOv8 for its higher accuracy
  - Final confidence threshold: 0.25
  # 4. Real-Time Detection
  - Process Video
  - Detect traffic signs and overlay bounding boxes with labes
  - 
 
