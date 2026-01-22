## Title: fundamental of digital image and basic image operation in python
---
## Objectives:
1. Load and display  digital images

2. Understand and digital image representation
3. Color to grayscale and binary image translation
4. Image tranformation (Resize,Rotate,Flip)
5. Crop the ROI (Region of interest) in an image

---
## Background Theroy
 * ###  Image Acquisition

   Image acquisition refers to the process of capturing an image using a digital device such as a camera, scanner, or sensor and converting it into a digital format that can be processed by a computer. The quality of the acquired image depends on factors such as lighting conditions, sensor resolution, and noise introduced during the capture process.


   ### Pixel Intensity and Dynamic Range

   Each pixel in a digital image represents the brightness or color intensity at a particular location. The dynamic range defines the range of values that a pixel can take. For an 8-bit image, pixel values range from 0 to 255, where 0 represents the lowest intensity (black) and 255 represents the highest intensity (white). A higher dynamic range allows for better contrast and detail in the image.

    
 
---
 ## Procedure

1) We had imported the necessary libraries, cv2 for image processing and numpy for array operations.


2) We had loaded the image from the file and had displayed it in a window using cv2.imshow().

3) We had converted the color image to grayscale using cv2.cvtColor() and had displayed the grayscale image.

4) We had applied thresholding on the grayscale image to had obtained a binary image and had displayed it.

5) We had resized the image, had rotated it, had flipped it, and had cropped a portion for transformation demonstration.
 
6) we had defined a specific region of interest, had cropped that area from the original image, and had displayed the cropped ROI.

--- 
## Output
 1) Original image displayed successfully
 2)  Grayscale and binary images obtained
 3) Image resized, rotated, and flipped correctly
 4) Region of interest cropped from the image
---

## Conclusion
In this lab, the fundamentals of digital image processing were explored using Python and OpenCV. Core operations such as loading images, converting color models, performing transformations, and extracting regions of interest (ROI) were successfully implemented. These basic techniques provide a foundation for more advanced image processing and computer vision tasks.