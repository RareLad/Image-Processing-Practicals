# Image Processing Practicals

This repository contains my Image Processing lab practical work
completed using Python and Jupyter Notebook.

The practicals cover basic image manipulation, colour-space conversion,
edge detection, image compression, texture analysis, and image
segmentation.

## Repository Structure

``` text
Image-Processing-Practicals/
├── README.md
├── Practical_File_1_Lab_3_4/
│   ├── Practical_File_1_Lab_3_4.ipynb
│   └── Required image files
└── Practical_File_2_Lab_9_10/
    ├── Practical_File_2_Lab_9_10.ipynb
    └── Required image files
```

## Practical File 1 -- Lab 3 & 4

This notebook contains 10 practical programs:

1.  Reading and displaying an image using OpenCV.
2.  Checking image dimensions and data type.
3.  Converting a colour image into grayscale and saving it.
4.  Opening and displaying an image using Pillow.
5.  Resizing an image to 50% of its original dimensions.
6.  Cropping the central 200 × 200 pixel region.
7.  Rotating an image by 90 degrees clockwise.
8.  Flipping an image horizontally.
9.  Converting an image to HSV and displaying the Hue, Saturation, and
    Value channels.
10. Calculating Mean Squared Error (MSE) between two grayscale images.

## Practical File 2 -- Lab 9 & 10

This notebook contains 9 practical programs:

1.  Sobel edge detection in the X and Y directions.
2.  Edge detection using Sobel and Laplacian operators.
3.  Gradient magnitude, gradient direction, and thresholded Laplacian.
4.  Run-Length Encoding (RLE).
5.  Huffman coding.
6.  JPEG-style image compression using DCT and quantization.
7.  Image statistics, histogram analysis, and Otsu thresholding.
8.  GLCM texture features and K-means segmentation.
9.  Multi-feature K-means image segmentation.

## Tools and Libraries Used

-   **Python** -- programming language used for the practicals.
-   **Jupyter Notebook** -- environment used to write and run the code.
-   **OpenCV (`cv2`)** -- image reading, transformations, filtering, and
    processing.
-   **NumPy** -- numerical and array operations.
-   **Matplotlib** -- displaying images, plots, and histograms.
-   **Pillow (`PIL`)** -- opening and handling images.
-   **scikit-image** -- texture analysis using GLCM features.

## How to Run the Notebooks

1.  Download or clone this repository.

2.  Make sure Python and Jupyter Notebook are installed.

3.  Install the required libraries:

    ``` bash
    pip install opencv-python numpy matplotlib pillow scikit-image
    ```

4.  Open the required practical folder.

5.  Launch Jupyter Notebook and open the `.ipynb` file.

6.  Keep the image files in the same folder as the notebook so that the
    image paths work correctly.

7.  Run the notebook cells in order.

## Note

The image files used by the programs are included in their respective
practical folders. Keep the folder structure unchanged when running the
notebooks.

------------------------------------------------------------------------

**Project:** Image Processing Lab Practicals\
**Format:** Python Jupyter Notebooks
