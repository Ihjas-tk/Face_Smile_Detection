# Real-Time Face And Smile Detection

This is my first project on computer vision. It is based on a research paper by Paul Viola and Michael Jones in 2001.
More popularly known as the Viola James Algorithm, even though it was developed two decades ago it is still widely accepted and provides 
good accuracy for face detection.

## Basic Intuition 

When the program is executed open cv is used to access the webcam of your computer, Then the individual frames are selected, And the algorithm is applied to each frame. The Algorithm utilizes the concept of features Haar-like Features to detect characteristics of the face. After detection,  contour boxes are drawn around the detected features.
For a more in-depth understanding of the algorithm, you can read the research paper [here](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf). 
