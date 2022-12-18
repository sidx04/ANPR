# Number Plate Recognition
Number Plate Recognition using Python for Team AutoZ.  
## Dependenices used: 
 + OpenCV
 + Numpy
 + EasyOCR
 + Matplotlib

## Workflow:
### 1. Reading the image in grayscale
Used OpenCV to read images in greyscale.
### 2. Edge detection 
Filtered the image and detected edges.
### 3. Contour search and Masking
Mapped the edge points and contours, detected the number plate section and mapped an array with the plotted points (pixels).
Focused on the number plate after locating from contours.
### 4.  Leveraging OCR to read number plate text
Reading text from the cropped number plate image.
### 5. Rendering
Displaying the original image with detected number plate and number plate text.

### Note: 
Only used static images for the project, video input will be worked upon later.
