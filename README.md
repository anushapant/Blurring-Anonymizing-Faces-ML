The goal of this project is to 
(a) detect and blur faces in an image for privacy purposes
(b) identify a person from the blurred image, given a set of “candidates”. 
The underlying motivation is to increase individual privacy with the increase in CCTV surveillance around the world, while also maintaining security. 

The face images were blurred via Gaussian blurring. 
Given these blurred images, two models were trained to identify who the image corresponds to, given a set of candidates. 
The KNN model achieved an accuracy of 90%, while the VGG-19 based one attained 95% accuracy. 
