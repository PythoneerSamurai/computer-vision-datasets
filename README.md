# Computer Vision Datasets

This repository houses my computer vision datasets. All datasets presently uploaded, and to be uploaded in the future, are high-quality and annotated with precision.
Do star ⭐ the repository if you find my datasets useful.

---

## Datasets Overview

### 1. Volleyball Ball Object Detection Dataset
- **Contents:** Volleyball court images with ball object detection annotations.
- **Purpose:** Optimized for training [YOLOv8x models](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models) to detect the ball in volleyball matches. Can also be downloaded in 9+ formats to train other models from my Roboflow account (see the quick access section).
- **Versions:** RGB (available here) and grayscale variants (available on my Roboflow).
- **Annotation:** Created with Roboflow, images preprocessed to 640x640 pixels.
- **Source:** Frames from a [YouTube clip](https://www.youtube.com/watch?v=BfcL_cxB-9o&t=10s).

[Explore Dataset](volleyball_ball_object_detection_dataset/)  
[Roboflow Universe](https://universe.roboflow.com/primaryws/volleyball_ball_object_detection_dataset)  
[Kaggle Models](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models)

---

### 2. Volleyball Court Keypoints Regression Dataset
- **Contents:** Volleyball court images with annotated keypoints.
- **Purpose:** Designed for training [YOLOv8x-pose models](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models) for court keypoint regression. Can also be used to train other models on Roboflow (see the quick access section).
- **Versions:** Four available, with four or eight keypoints, in RGB and grayscale, all versions present on Roboflow.
- **Annotation:** Done on Roboflow, preprocessed to 640x640 pixels.
- **Source:** [YouTube video](https://www.youtube.com/watch?v=BfcL_cxB-9o&t=10s).

[Explore Dataset](volleyball_court_keypoints_regression_dataset/)  
[Roboflow Universe](https://universe.roboflow.com/primaryws/volleyball_court_key_points_regression_dataset)  
[Kaggle Models](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models)

---

### 3. Volleyball Players and Referee Detection Dataset
- **Contents:** Volleyball court images annotated for player and referee detection.
- **Purpose:** Suited for [YOLOv8x-based](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models) training to detect players and referees.  Can also be downloaded in 9+ formats to train other models from my Roboflow account (see the quick access section).
- **Versions:** Available in one version, with additional formats on Roboflow.
- **Annotation:** Roboflow workspace, images at 640x640 pixels. Augmented by flipping images between -15° and +15°.
- **Source:** [YouTube video](https://www.youtube.com/watch?v=BfcL_cxB-9o&t=10s).

[Explore Dataset](volleyball_players_and_referee_detection_dataset/)  
[Roboflow Universe](https://universe.roboflow.com/primaryws/volleyball_players_and_referee_object_detection_dataset)  
[Kaggle Models](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models)

---

## Quick Access

<p>
  <a href="https://www.kaggle.com/datasets?search=pythonistasamurai"><img src="https://img.shields.io/badge/Kaggle-Download-blue?logo=kaggle" alt="Kaggle"></a>
  <a href="https://universe.roboflow.com/primaryws"><img src="https://img.shields.io/badge/Roboflow-Universe-orange?logo=roboflow" alt="Roboflow"></a>
</p>

---

## Project Structure

- **volleyball_ball_object_detection_dataset/**
  - `README.md`, `README.dataset.txt`, `README.roboflow.txt`, `data.yaml`, `train/`, `valid/`
- **volleyball_court_keypoints_regression_dataset/**
  - `README.md`, `README.dataset.txt`, `README.roboflow.txt`, `data.yaml`, `train/`, `valid/`, `test/`
- **volleyball_players_and_referee_detection_dataset/**
  - `README.md`, `README.dataset.txt`, `README.roboflow.txt`, `data.yaml`, `train/`, `valid/`

---

## Citation

If you use these datasets in your research or projects, please cite this repository and the linked Kaggle/Roboflow sources.

---

## License

See individual dataset folders for specific license information.

---

## Author

- [PythoneerSamurai](https://github.com/PythoneerSamurai)
