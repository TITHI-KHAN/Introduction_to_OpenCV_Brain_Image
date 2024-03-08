# Introduction_to_OpenCV_Brain_Image

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/e1d0c6f1-546a-47d7-8fa4-968d79b03e5c)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/b7d2572f-b480-4b4e-b95c-f43d6da037a7)

![image](https://github.com/TITHI-KHAN/Introduction_to_OpenCV_Brain_Image/assets/65033964/abcf9b57-6483-4f91-952f-31e2c995bbd6)

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
