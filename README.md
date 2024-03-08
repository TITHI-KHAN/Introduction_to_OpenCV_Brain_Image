# Introduction_to_OpenCV_Brain_Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/e1d0c6f1-546a-47d7-8fa4-968d79b03e5c)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/b7d2572f-b480-4b4e-b95c-f43d6da037a7)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/abcf9b57-6483-4f91-952f-31e2c995bbd6)

**OpenCV** is a library of programming functions mainly for real-time computer vision. Originally developed by Intel, it was later supported by Willow Garage, then Itseez. Ref: Wikipedia

## Installation

### Prerequisites

    - Python 3.x
    - pip (Python package installer)

### Installing OpenCV

To install OpenCV for Python, use pip:

**pip install opencv-python**

For full package (including contrib modules):

**pip install opencv-python-contrib**

# Basic Operations

## Reading, Writing, and Displaying Images

### Reading an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/2a267b8b-b040-4730-8203-4d721bbe58d3)

### Displaying an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/19030190-f778-4ba7-99d9-b3cc91dce6ca)

### Writing an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/4305d6d7-c297-47a2-b634-2633aafadac8)

# Basic Image Processing

## Converting to Grayscale

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/4abb19f5-df50-451a-b368-4d93717004a5)

## Resizing Images

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/5819562c-8a41-4631-a5ef-14775c211e4c)

## Drawing on Images

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/d20ca787-6017-4984-8956-1a640fa4286f)

# Advanced Image Processing

## Edge Detection

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/f0cd552d-f28a-4f2c-84f0-d3f1a831e45c)

## Image Thresholding

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/ea2aa150-79bb-461c-a185-e92a4e7f3057)

## Contour Detection

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/36598768-c9a8-4a2a-bc71-4de8ef8aad19)


## Code Explanation

This code demonstrates image processing techniques using the OpenCV library and matplotlib for visualization. Let's break down each part:

1. **Edge Detection with Contours**:

   - The code reads an image (`Image.png`) using OpenCV, converts it to grayscale, applies Gaussian blur, and performs edge detection using the Canny edge detector.

   - Contours are then detected using `findContours` method, and they are drawn onto a separate image.

   - The original image, edge image, and contour image are plotted side by side using matplotlib.

3. **Thresholding with Contours**:

   - This part is similar to the first one but involves thresholding the grayscale image to create a binary image using Otsu's thresholding method (`cv2.THRESH_OTSU`).

   - Contours are detected again, and the contour image is created and plotted alongside the original, grayscale, and binary images.

5. **Hierarchy of Contours**:

   - Another variation of contour detection is showcased here. This time, contours are detected with the `cv2.RETR_TREE` retrieval mode, which retrieves all the contours and reconstructs a full hierarchy of nested contours.

    - Similar to previous parts, the original, grayscale, binary, and contour images are plotted.

7. **Metadata Extraction for Image**:

    - This section extracts metadata such as file size, dimensions, and color depth from the image using OpenCV and OS libraries.

9. **DICOM Metadata Extraction**:

   - It uses the `pydicom` library to read DICOM data from a file (`0.dcm`) and extracts metadata such as tag name and value.

Overall, the code provides a comprehensive demonstration of various image processing techniques and metadata extraction methods using OpenCV and other libraries in Python.

# Simple Project Example: Face Detection

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/ace27144-700d-406f-9835-4d0f75dda18d)

## 1. Reading and Displaying an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/a1aeed47-357c-408e-946d-5311f4e21bfe)


![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/2cfe664a-b34d-48fb-9260-405b1ac90492)


## 2. Converting an Image to Grayscale

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/06ece77d-57c8-4e1d-9de0-667ed00b8cb5)

## 3. Blurring an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/639206db-5444-4c5b-b367-e0b62edef8cf)

## 4. Edge Detection

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/5f5cd3ac-c09b-4f9b-a489-eae11ccc6a24)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/a44b60de-122a-4ef0-8d6c-f9871dcaec40)

## 5. Image Thresholding

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/cadafdc9-2a39-4050-a91e-2834249459a6)

## 6. Resizing Images

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/02aceaad-030b-4d8d-a404-383163f1d8ec)

## 7. Rotating an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/442aee6c-1eed-4fd8-8195-e253d78394a7)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/d7a68b10-f16b-44bf-b15c-faf3daf3a8eb)


## 8. Drawing Shapes on Images

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/69ff37d5-7b88-41d0-9e7c-3d83e564ef6d)

## 9. Image Translation

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/f61114ea-b7fb-4d23-9789-06936b7944cf)


![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/cfbc409d-d881-4ae9-9f07-77ec81d227f5)


## 10. Finding and Drawing Contours

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/cda266df-aacd-4e12-a270-9f0c72f6b77a)

## 11. Reading and Displaying an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/7e36895c-511c-4ef9-a5a7-52191b7e3976)

## 12. Converting an Image to Grayscale

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/23c75b73-99af-4f7c-bd22-6c5e1059483e)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/1faf0d9b-65b6-487e-930c-e8b3bad19db7)

## 13. Gaussian Blurring

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/03b99688-4c8f-47c1-8fcf-f9a97903613e)

## 14. Edge Detection with Canny

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/c282121c-8a4c-4fd1-979e-38eb5d967e61)

## 15. Thresholding

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/2672db9d-c7e8-4ebc-b027-cda835e24749)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/f968fcfb-5fe7-48b1-bb30-7ddadf2da02e)

## 16. Resizing Images

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/27315456-a264-467d-bb79-b3563c1ee538)

## 17. Rotating an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/dd7adc2d-b416-41a1-8dfc-16cb2c17213e)

## 18. Drawing Shapes and Text on an Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/3921af53-8518-4e53-9146-cad9e8f512a4)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/d443556f-7a9a-43c7-8dc5-2354404a701d)

## 19. Image Translation

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/cc462191-aa78-492e-a12b-acbcb25ff173)

## 20. Finding and Drawing Contours

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/4f3ec2df-da19-4704-9171-5c8e2b0b5994)

# Official OpenCV Documentation

- **OpenCV-Python Tutorials (https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)**: This is the primary source for learning how to use OpenCV with Python. It offers tutorials, code examples, and explanations of core concepts.

- **OpenCV Modules (https://docs.opencv.org/4.x/index.html)**: Provides a complete reference for all OpenCV functions across various modules (image processing, video I/O, machine learning, etc.).

## Additional Resources

- **OpenCV-Python Tutorials Documentation on Read the Docs** (https://readthedocs.org/projects/opencv24-python-tutorials/downloads/pdf/latest/): Downloadable PDF version of the tutorials.

- **Stack Overflow** ([https://stackoverflow.com/]): Great for finding solutions to specific problems and asking questions.

