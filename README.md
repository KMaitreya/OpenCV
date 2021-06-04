# OpenCV

The images are taken from a folder called /images. The folder is included.Other folders such as /files and /videos hahve also been included.

1)opencv-1 (Changing the colour profile of an image):
Using functions of opencv i have changed the colour profiles of an image from BGR to RGB, HSV and Grayscale. THe images are read using imread() and displayed using mathplotlib library.

2)opencv-2 (Edge detection):
In this program opencv library has been used to detect all the edges in an image, the Canny() has been used, before that the image has been converted to grayscale, for bettwe edge detection.

3)opencv-3 (Erosion and Dilation)
Erosion and dilation of edges has been performed on the canny image from the previous program, erode() and dilate() has been used, a ones matrix has been passed to the function which shows the degree to which erosion and dilation of an image has to take place.

4)opencv-4 (Noise reduction and removal)
Using opencv functions we have demonsrated the reduction of noise from the given image. The level of noise reduction will be based on the values passed to the function.

5)opencv-5 (Drawing and writing on an image)
Using opencv fucntion we have drawn a circle, a rectangle and a line on a complete black image made out of a zeroes numpy array. We have also written a text on that image. parameetrs of the function used are explained in the jupyter notebook.

6)opencv-6 (colour detection)
Using open cv function we can detect various colours in an image. We used upper and lower bound for each colour to separate it from the image.

7)opencv-7 (face detection)
In this notebook we have used cascade classifier to detect the face. The original image has to be onverted into a grayscale for cascade classifier to work, we have used a green rectangle to denote the detected face. The coordinates of the rectangle come as an output of the detectMultiScale().

8)opencv-9 (ball tracking)
In this notebook we have used open cv fucntions to track the movemnt of a ball. Firstly the ball has been detected and then using contours it's center has been found after which the movement of the ball has been detected each time the ball and correspondlingly the center moves.
