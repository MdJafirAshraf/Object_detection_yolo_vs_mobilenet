# Object_detection_yolo_vs_mobilenet
  Object detection is detect and recognize the object. It is one of the common application in the computer vision problem (like traffic signals, people tracking, vehicle detection, etc...). In this repo I develop the real time object detetion with pre-trained models. These are **YOLO version 3** and **SSD MobileNet version 3**. And I used coco large dataset for detecting labels, that are totaly 80 labels.
  
## YOLO V3
  Yolo is one of the pre-trained model for object detection. It has been used to several object detection applications. It works based on CNN(Convolutional Neural Network).
  - [yolo model](https://pjreddie.com/media/files/yolov3.weights)
  - [yolo config](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
  - [coco names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

## MobileNet V3
  mobilenet is also pre-trained model for object detection. The SSD(Single Shot Detector) object detection model used in Mobilenet. It can be detect the object in fast and optimized for all mobille devices.
 
  - [mobilenet model](http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v3_large_coco_2020_01_14.tar.gz)
  - [mobilenet config](https://gist.github.com/dkurt/54a8e8b51beb3bd3f770b79e56927bd7)
  - [coco names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)
 
 the model and config is also provided in this repo [here](https://github.com/JafirDon/Object_detection_yolo_vs_mobilenet/tree/main/mobilenetv3/ssd_mobilenet_v3_large_coco_2020_01_14).


## Output Video

### YOLO Output Video
![Yolo Output video](https://github.com/JafirDon/Object_detection_yolo_vs_mobilenet/blob/main/OutputVideo-Yolo.gif)

### MobileNet Output Video
![MobileNet Output video](https://github.com/JafirDon/Object_detection_yolo_vs_mobilenet/blob/main/OutputVideo-MobileNet.gif)
