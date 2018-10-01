# YOLO_Object_Detection

** A single convolutional network simultaneously predicts multiple bounding boxes and class probabilities for those boxes. YOLO trains on full images and directly optimizes detection performance. This unified model has several benefits over traditional methods of object detection. First, YOLO is extremely fast. Since we frame detection as a regression problem we don’t need a complex pipeline. We simply run our neural network on a new image at test time to predict detections. Our base network runs at 45 frames per second with no batch processing on a Titan X GPU and a fast version runs at more than 150 fps. This means we can process streaming video in real-time with less than 25 milliseconds of latency.

#  INPUT VIDEO 
**  https://github.com/amit6604/YOLO_Object_Detection/releases/download/v1.0/teaser.mp4 
**  Raw video, https://www.youtube.com/watch?v=ybGkgYDLqA8
