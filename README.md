# Self-Driving-Car
A project based on image processing based using CNN and OpenCV
based on Image Processing using Convolutional Neural Networks + OpenCV.

The project aims to build a monocular vision autonomous car prototype using Raspberry Pi as a processing chip interfaced with a camera.It is based on Image Processing using Deep learning + OpenCV,which classifies between the various images.
Raspberry Pi CAM was used for all the real time image input .
Images were simplified using OpenCV - hough transform,canny edge detection to make it easier for our neural network to identify features and colour/region masking to avoid unnecessary striking features to interfere in the model.
Raspberry Pi 3 was used for nominal real time image processing using open CV which is powered by the 12V adapter to avoid input power fluctuations.
The model was trained using KERAS library with 2000 images each for "left, right, straight, sharp left, sharp right,stop" to follow a track.Sample images of the above categories in provided in the sample data section of the repository.
However the Arena for which the model trained to run for has limited features like stop sign ,no entry,steep left/right,front and stop sign. alt text
In the cases where deadlines that are marked by black lines on the arena ,are to be handled IR sensors are arranged in front of the bot to detect them.
The motors were controlled using a microcontroller, Arduino UNO which is serial communicated with raspberry pi.
