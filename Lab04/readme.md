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
 * ### Gigital image representation (pixel,resolution):

    A digital image is a two-dimensional representation of a real-world object, stored as a matrix of pixels.
    Each pixel contains intensity information. The resolution of an image refers to the total number of pixels arranged in rows and columns.

    *  Grayscale image : 2D matrix (height × width)

    * Color image :3D matrix (height × width × channels)
    
 * ### Color models (RGB,Grayscale and Binary)

   #### i. RGB Color Model

    Represents images using Red, Green, and Blue channels.Each pixel is a combination of these three colors.Commonly used in displays, cameras, and digital media.

    Example: (255, 0, 0) → pure red, (0, 255, 0) → pure green.

   #### ii. Grayscale

    Represents images in shades of gray, from black to white.

    * Each pixel has a single intensity value (0 = black, 255 = white).

    * Reduces memory usage compared to RGB.

    * Useful for image processing tasks like edge detection.

   #### iii. Binary (Black & White) Image

    Each pixel has only two possible values: 0 (black) or 1 (white). Often created from grayscale images using thresholding.


---
 ## Procedure
#### Step 1:
We had imported the necessary libraries, cv2 for image processing and numpy for array operations.

#### Step 2:
We had loaded the image from the file and had displayed it in a window using cv2.imshow().

#### Step 3:
We had converted the color image to grayscale using cv2.cvtColor() and had displayed the grayscale image.

#### Step 4:
We had applied thresholding on the grayscale image to had obtained a binary image and had displayed it.

#### Step 5:
We had resized the image, had rotated it, had flipped it, and had cropped a portion for transformation demonstration.

#### Step 6: 
we had defined a specific region of interest, had cropped that area from the original image, and had displayed the cropped ROI.

--- 
## Output
* Original image displayed successfully
* Grayscale and binary images obtained
* Image resized, rotated, and flipped correctly
* Region of interest cropped from the image
---

## Conclusion
In this lab, the fundamentals of digital image processing were explored using Python and OpenCV. Core operations such as loading images, converting color models, performing transformations, and extracting regions of interest (ROI) were successfully implemented. These basic techniques provide a foundation for more advanced image processing and computer vision tasks.