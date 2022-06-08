# Real time object detection using YOLO with webCam

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

YOLOv3 uses a few tricks to improve training and increase performance, including: multi-scale predictions, a better backbone classifier, and more. for more details you can go here https://pjreddie.com/darknet/yolo/ 

## Features

- Can detect the object in the image.
- object detection with webcamera is also working.
- change the yolo weight if you want to tradeoff between speed and accuracy.


## Tech


- [python] - code written in 
- [yolov3] - using yolov3 for object detecton 
- [cv] -using cv for webcam as well as for the image input from local dic.
- [darnet framework] - yolo based on darknet
- [jypter notebook] - written in jypter notebook


## Installation


```sh
git clone https://github.com/gatto-gatto/Real-time-object-detection-using-YOLO-taking-input-using-webCam
cd Real-time-object-detection-using-YOLO-taking-input-using-webCam
cd weight 
wget https://pjreddie.com/media/files/yolov3.weights
```
