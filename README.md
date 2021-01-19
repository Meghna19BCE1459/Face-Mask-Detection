# Face-Mask-Detection
The outbreak of the global pandemic has resulted in the formulation and implementation of strict and stringent laws world wide, of which wearing masks while stepping out of 
our houses is of atmost importance. In order to maintainf and regulate this norm, I decided to develop a face mask detection system which has its foundation base in the language 
of Python and uses libraries and modules like OpenCV, Tensorflow, Keras, etc.
I have made use of the R-CNN algorithm in Deep Learning in order to implement accurate and efficient means of detecting if a person is wearing Face Masks or not.
R CNN uses selective search algorithm to extract the top 2000 region proposals among millions of regions of interest (ROI) proposals from an image and feed it to a CNN model.
The program is first trained using necessary datasets and on running the mask detection program, it captures the frames from the live stream and binds the detected face in the video with 
red box if the person isn't wearing a mask. Else, it will bind the face with a green box. In both cases, the corresponding confidence levels are also displayed.
Region Based Convolutional Neural Networks (R-CNN) are a family of machine learning models for computer vision and specifically object detection.
This can be effectively incorporated in public places and other societal areas to monitor if people are adhering to the norms of wearing masks and proves to be an efficient system.
