# Bloodcell_detection---yolov5

![feature-image](https://news.harvard.edu/wp-content/uploads/2015/10/red_blood_cells_605.jpg)

Using Yolov5 to train on Blood-cell dataset

# About Yolov5
You can read this model in this link: https://github.com/ultralytics/yolov5.git

# About Dataset
We use dataset from this link : https://github.com/draaslan/blood-cell-detection-dataset.git

![feature-image]('[blob:https://www.messenger.com/72d5cb5b-cf82-4db0-9215-e594595a50ae](https://scontent.xx.fbcdn.net/v/t1.15752-9/323584072_551687796623804_2430966581456413941_n.png?_nc_cat=108&ccb=1-7&_nc_sid=aee45a&_nc_ohc=Zgx6jfBT53kAX_eqdpT&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AdQplo-7onvXkWArB7RmdZgd4ArsK7tdxczUC2cTd_goCA&oe=63DBD35B)')

# # Note: This labels file are Kitti format, so you must convert them into Yolov5 foramt
  You just care about 5 parameter in file lables.txt: *labels *x_min *y_min *x_max *y_max
  Then convert it into Yolov5 format: *labels *x_center *y_center *weight *height
 
# Method
 1. Preprocessor
 2. Using Yolov5 from link : https://github.com/ultralytics/yolov5.git
