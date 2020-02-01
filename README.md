# Count-Objects-Face-Detection-Edge-Detection

The interface gives 3 choices: Count objects, face detection or detection of edges.
The Object Count uses OpenCV library to detect the number of objects in any input image. 
A black and white filter is applied to the image and a dilation filter is applied to the image after a Gaussian blur. 
The filtered output is then used to generate contours over the parts where the result image changes values abruptly. 
Next, the number of contours is counted. 
The input image, greyscale image, the filtered output and the number of objects detected are then shown in a GUI using matplotlib library.
The face detection uses the 'haarcascade_frontalface_default.xml' file as the supporting face detection parameters.
Also, 3 different filters namely Laplacian, Sobel and canny are used for detection of edges. The user can use any one as per need.
