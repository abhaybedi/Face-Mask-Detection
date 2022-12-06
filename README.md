# Face-Mask-Detection

Face mask detection has a range of applications from capturing the movement of the face to facial recognition which at first requires the face to be detected with very good precision. 
Face detection is more relevant today as it is not only used on images, but also in video applications like real-time surveillance and face detection in videos.

Process of Face Mask Detection with Machine Learning:
Step 1: Extract face data for training.
Step 2: Train the classifier to classify faces in mask or labels without a mask.
Step 3: Detect faces while testing data using SSD face detector.
Step 4: Using the trained classifier, classify the detected faces.

SSD FACE DETECTOR:
Single Shot Multibox Detector- is a technique used to detect objects in images using a single deep neural network.
It is used for the detection of objects in an image. Using a basic architecture of the VGG-16 architecture, the SSD can outperform other object detectors such as YOLO and Faster R-CNN in terms of speed and accuracy

Why ssd over r-cnn and yolo:
By victimization SSD, we tend to solely have to be compelled to take one single shot to sight multiple objects inside the image, whereas regional proposal network (RPN) primarily based approaches like R-CNN series want 2 shots, one for generating region proposals, one for police work the article of every proposal.
SSD not only uses one grid, but a combination of different sizes to better detect objects at any size.

YOLO struggles to localize objects properly compared with quick R-CNN.YOLO has fewer background errors. quick R-CNN has 13.6% that the highest detections square measure false positive.

SSD, a single-shot detector for multiple classes that’s quicker than the previous progressive for single-shot detectors (YOLO), and considerably a lot of correct, really as correct as slower techniques that perform express region proposals and pooling.


Dataset for the project:
To ensure detection capabilities of our model are as close to perfection as possible, we’ve taken a dataset of over 2340 images(2.5GB) of subjects wearing and not wearing a mask all without a face tag. 
We’ve also taken into consideration that all our subjects belong to different regions/countries to ensure our trained model works well for all face types.
The whole system works well for faces that have spatial dominance. But fails in the case of images where the faces are small and take up less space in the overall image. 



