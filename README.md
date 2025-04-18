# Real-time-Pothole-Detection-Using-YOLOv8

Developed a pothole detection system using YOLOv8 model and OpenCV. The model offers two options:
  1. Upload a video and obtain resultant video with detected potholes
  2. Real-time pothole detection through webcam/dashcam

The model was built using the YOLOv8 'medium' model from the Ultralytics library, and was trained over 70 epochs with image size parameter set to 640.

The model achieved the following metric values:
  1. Bounding Box Regression Loss (box_loss): 0.6919
  2. Calssification Loss (cls_loss): 0.4468
  3. Distribution Focal Loss (dfl_loss): 0.9947
  4. Precision: 0.796
  5. Recall: 0.703
  6. Mean Average Precision at 50% IoU (mAP50): 0.788
  7. mAP averaged across IoU thresholds from 0.5 to 0.95: 0.524

Further, the opencv-python module was utilized to design a system that allows the user to upload a video and outputs the video with detected potholes, indicated by bounding boxes. An example can be found in the 'Results' folder.

Finally, a script enabling webcam/dashcam access is also provided, which aids real-time pothole detection and warns the user when a pothole is detected. This can be intergrated in vehicle systems for a better driving experience.
