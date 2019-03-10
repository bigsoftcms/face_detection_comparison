# Face Detection Algorithm Comparison

Compare latency and accuracy of face detection algorithms.  
**Click link to watch [demo video]()!**  

### OpenCV DNN Face Detector (Best)  
![](https://github.com/kairess/face_detection_comparison/raw/master/result/result_opencv_dnn.png)

### OpenCV Haar Cascade  
![](https://github.com/kairess/face_detection_comparison/raw/master/result/result_opencv_haar.png)

### Dlib Frontal Face Detector  
![](https://github.com/kairess/face_detection_comparison/raw/master/result/result_dlib.png)

### MTCNN  
![](https://github.com/kairess/face_detection_comparison/raw/master/result/result_mtcnn.png)


## Algorithms

- OpenCV DNN face detector: models/opencv_face_detector_uint8.pb
- Haar cascade: models/haarcascade_frontalface_default.xml
- Dlib frontal face detector
- MTCNN: https://github.com/ipazc/mtcnn

# Test Environment
- MacBook Pro (Retina, 15-inch, Mid 2014)
- Processor: 2.5 GHz Intel Core i7
- Memory: 16GB 1600 MHz DDR3
- Graphic: NVIDIA GeForce GT 750M 2048 MB, Intel Iris Pro 1536 MB

## Dependencies
- Python
- OpenCV
- dlib
- mtcnn https://github.com/ipazc/mtcnn
  - Tensorflow
