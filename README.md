1. Perform basic Image Handling and processing operations on the image. • Read an image in python 
and Convert an Image to Grayscale.

2. Perform basic Image Handling and processing operations on the image.• Read an image in python 
and Convert an Image to Blur using GaussianBlur.

3. Perform basic Image Handling and processing operations on the image• Read an image in python 
and Convert an Image to show outline using Canny function.

4. Perform basic Image Handling and processing operations on the image• Read an image in python 
and Dilate an Image using Dilate function.

5. Perform basic Image Handling and processing operations on the image• Read an image in python 
and Erode an Image using erode function.

6. Perform basic video processing operations on the captured video• Read captured video in python 
and display the video, in slow motion and in fast motion.

7. Capture video from web Camera and Display the video, in slow motion and in fast motion 
operations on the captured video.

8. Scaling an image to its Bigger and Smaller sizes.

9. Perform Rotation of an image to clockwise and counter clockwise direction.
ROTATION 90 ALONG DEGREE: 
AIM 
The Aim of the Experiment is to perform Rotation of an image along 90 degree
PROGRAM 
import cv2
path r"C:/Users/Welcome/OneDrive/Pictures/SavedPictures/cat.jpeg"
src = cv2.imread(path)
window_name = 'Image'
image = cv2.rotate(src, cv2.ROTATE_180)
cv2.imshow(window_name, image)
cv2.waitKey(0)
INPUT 
 
OUTPUT 
 
 
ROTATION ALONG 180 DEGREE 
AIM 
The Aim of the Experiment is to perform Rotation of an image along 180 degree
PROGRAM 
import cv2
path = r"C:/Users/divya/OneDrive/Documents/COMPUTER VISION/Girl with a Cat.png"
src = cv2.imread(path)
window_name = 'Image'
image = cv2.rotate(src, cv2.ROTATE_90_COUNTERCLOCKWISE)
# Displaying the image
cv2.imshow(window_name, image)
cv2.waitKey(0)
OUTPUT 
 
 
 
 
ROTATION ALONG 270 DEGREE 
AIM 
The Aim of the Experiment is to perform Rotation of an image along 270 degree
PROGRAM 
import cv2
path = r"C:/Users/Welcome/OneDrive/Pictures/Saved Pictures/cat.jpeg"
src = cv2.imread(path)
window_name = 'Image'
image = cv2.rotate(src, cv2.ROTATE_90_COUNTERCLOCKWISE)
cv2.imshow(window_name, image)
cv2.waitKey(0)


11. Perform Affine Transformation on the image.

12.  Perform Perspective Transformation on the image.

13.  Perform Perspective Transformation on the Video.

14.  Perform transformation using Homography matrix.

15.  Perform transformation using Direct Linear Transformation.

16. Perform Edge detection using canny method.

17.  Perform Edge detection using Sobel Matrix along X axis.

18.  Perform Edge detection using Sobel Matrix along Y axis

19. Perform Edge detection using Sobel Matrix along XY axis.

20. Perform Sharpening of Image using Laplacian mask with negative center coefficient.

21. Perform Sharpening of Image using Laplacian mask implemented with an extension of
diagonal neighbors.

22. Perform Sharpening of Image using Laplacian mask with positive center coefficient.

23. Perform Sharpening of Image using unsharp masking.

24. Perform Sharpening of Image using High-Boost Masks.

25. Perform Sharpening of Image using Gradient masking.

26. Insert water marking to the image using OpenCV.

27. Do Cropping, Copying and pasting image inside another image using OpenCV.

28. Find the boundary of the image using Convolution kernel for the given image.

29.  Morphological operations based on OpenCV using Erosion technique.

30.  Morphological operations based on OpenCV using Dilation technique.

31.  Morphological operations based on OpenCV using Opening technique.

32.  Morphological operations based on OpenCV using Closing technique.

33.  Morphological operations based on OpenCV using Morphological Gradient technique.

34.  Morphological operations based on OpenCV using Top hat technique.

35.  Morphological operations based on OpenCV using Black hat technique.

36.  Recognise watch from the given image by general Object recognition using OpenCV.

37.  Using Opencv play Video in Reverse mode.

38.  Face Detection using Opencv.

39.  Vehicle Detection in a Video frame using OpenCV.

40.  Draw Rectangular shape and extract objects.
