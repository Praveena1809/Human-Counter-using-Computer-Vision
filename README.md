# Human-Counter-using-Computer-Vision
The People Counter program allows you to count the number of people in a video passing through a Region of Interest, which is created by the user. To use the program, you'll need Python 3 and OpenCV 3.4.

It is built for security footage, and it detects people using HOG + Linear SVM classifier (Histogram of Oriented Gradients for Objection Detection), along with Non-maximum Suppression(NMS); and it then outputs distinct pictures of the detected people using SIFT (Scale-invariant feature transform). The program counts number of people coming in towards the camera as coming 'In' and people going away from the camera as 'Out'.
