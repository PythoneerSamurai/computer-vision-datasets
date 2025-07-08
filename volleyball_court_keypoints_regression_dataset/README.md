# Introduction
This dataset consists of volleyball court images along with their key point annotations.
The dataset has been annotated precisely to train a [yolov8x-pose](https://www.kaggle.com/models/pythonistasamurai/yolov8x_volleyball_analysis_models) model to regress the key points on volleyball courts. The regressed key points will be used to carry out a homography and perspective transformation to produce a radar view of the court.
This dataset is part of three datasets (the other two for volleyball players and referee object detection and volleyball ball object detection) used to train yolov8x models for [my project](https://github.com/PythoneerSamurai/computer-vision-projects/tree/master/key-points-regression/yolov8x-supervision-advance-volleyball-analysis).

# Versions
This dataset has four versions, two of which have eight key points on the court (in RGB and grayscale) and the other two have four key points on the court. The version uploaded on my Kaggle has four distinct key points in grayscale.
For other versions and formats of this dataset visit my [Roboflow account](https://universe.roboflow.com/primaryws/volleyball_court_key_points_regression_dataset).
The best yolov8x-pose model (linked above) was trained on the version of this dataset uploaded on my Kaggle.

# Images Source
The images used in this dataset have been extracted from a short 22-second clip of a volleyball match uploaded on [YouTube](https://www.youtube.com/watch?v=BfcL_cxB-9o&t=10s).

# Annotation Platform
The images were annotated on Roboflow Workspace.

# Pre-Processing and Augmentations
The images were preprocessed to 640 pixels in width and height, and two versions of this dataset were subjected to grayscale.
