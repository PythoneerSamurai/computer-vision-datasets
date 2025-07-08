# Introduction
This dataset comprises volleyball court images and their ball object detection annotations.
The dataset has been annotated precisely to train a [yolov8x](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models) model to detect the ball in volleyball matches.
This dataset is part of three datasets (the other two for volleyball players and referee object detection and volleyball court key points regression) used to train yolov8x models for [my project](https://github.com/PythoneerSamurai/computer-vision-projects/tree/master/key-points-regression/yolov8x-supervision-advance-volleyball-analysis).

# Versions
This dataset has two versions, one has RGB images (uploaded on GitHub) and the other has grayscale images.
For the other versions and formats of this dataset visit my [Roboflow account](https://universe.roboflow.com/primaryws/volleyball_ball_object_detection_dataset).
The best yolov8x model (linked above) was trained on the version of this dataset uploaded on my Kaggle.

# Images Source
The images used in this dataset have been extracted from a short 22-second clip of a volleyball match uploaded on [YouTube](https://www.youtube.com/watch?v=BfcL_cxB-9o&t=10s).

# Annotation Platform
The images were annotated on Roboflow Workspace.

# Pre-Processing and Augmentations
The images were preprocessed to 640 pixels in width and height, and one of the versions of this dataset was converted to grayscale.
