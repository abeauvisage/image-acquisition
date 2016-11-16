# image-acquisition
program for acquiring images from one or several bluefox/flir cameras.


DEPENDENCIES:
OpenCV >= 12.4.8  http://opencv.org/downloads.html
Sensoray 2253 driver >= 1.2.14 (for flir cameras) http://www.sensoray.com/products/2253.htm
mvBlueFOX SDK >= 2.17.2 (for MV cameras)  https://www.matrix-vision.com/USB2.0-industrial-camera-mvbluefox.html

INSTALLATION:
- install every dependencies (refer to the links above)
- run makefile

COMPILE:
Path to the header files should be known.
The following libraries should be linked:
-libmvBlueFOX
-libmvDeviceManager
-libmvPropHandling
-libopencv_core
-libopencv_highgui


TODO:
- create makefile for the program to be compiled on linux :)