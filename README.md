# AprilTag-Detection
Detecting AprilTags using Computer Vision (Transfer Learning)

In this notebook, we try to explore how to detect apriltags in images using a deep learning approach. 
Aprltags are mainly used in the field of robotics and 3D envrionment processing to localize, interprete and analyze the surroundings. 

The regular Apriltag detections uses an algorithm to perform adaptative thresholding and segmentation to detect the tags in a given image (more details in the [official research paper](https://april.eecs.umich.edu/media/pdfs/wang2016iros.pdf). 

In this notebook, we quickly explore how pre-existing CNNs can be fine tuned and used to detect apriltags. 

We first create a training dataset using the apriltag python library (performing the "classical" detection) and then we use the results as training data for our CNN. 

This was a challenge for an intership position and it was done in less than 10 hours of work, including all the "documentation" aspect. 
