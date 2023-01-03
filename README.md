# Bloodcell_detection---yolov5

![feature-image](https://news.harvard.edu/wp-content/uploads/2015/10/red_blood_cells_605.jpg)

Using Yolov5 to train on Blood-cell dataset

# About Yolov5
You can read this model in this link: https://github.com/ultralytics/yolov5.git

# About Dataset
We use dataset from this link : https://github.com/draaslan/blood-cell-detection-dataset.git

# # Note: This labels file are Kitti format, so you must convert them into Yolov5 foramt
  You just care about 5 parameter in file lables.txt: *labels *x_min *y_min *x_max *y_max
  Then convert it into Yolov5 format: *labels *x_center *y_center *weight *height
 
# Method
 1. Preprocessor
 2. Using Yolov5 from link : https://github.com/ultralytics/yolov5.git
