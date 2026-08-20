# Assignment 1 – Advanced Pixel-Level Manipulation

## Project Description

This project is part of the **Computer Vision Course** and demonstrates image processing and pixel-level manipulation using Python.

The project works with two images and applies different image processing operations using NumPy, PIL, OpenCV, and Matplotlib. The implementation includes inspecting image properties, direct pixel and array manipulation, array slicing, random cropping and pasting, grayscale conversion, and image sharpening using a custom kernel.

## Project Workflow

The project includes the following steps:

### 1. Loading and Inspecting Images

Two images are downloaded from URLs and loaded using PIL. The images are then converted into RGB format and NumPy arrays.

The project displays information about each image, including:

* Image shape
* Data type
* Minimum pixel value
* Maximum pixel value

The two images are also displayed using Matplotlib.

### 2. Direct Pixel-Level and Array-Level Manipulation

Copies of the original images are created as NumPy arrays.

The project demonstrates:

* Accessing RGB values of individual pixels.
* Inspecting image array dimensions.
* Using array slicing to select a region from an image.

### 3. Random 30×30 Crop and Paste

A `30×30` pixel region is selected from Image 1 using randomly generated coordinates.

The selected region is then pasted into a randomly generated location in Image 2 to create **Image3**.

The crop location, paste location, crop shape, and Image3 shape are displayed as part of the process.

### 4. Grayscale Conversion

Image 1, Image 2, and Image3 are converted from RGB to grayscale using OpenCV's `cv2.cvtColor()` function.

The resulting grayscale images are displayed using Matplotlib.

### 5. Image Sharpening

A custom sharpening kernel is defined using NumPy and applied to the grayscale version of Image3 using OpenCV's `cv2.filter2D()`.

The final result is displayed alongside the grayscale version of Image3 for comparison.

## Technologies Used

* Python
* Google Colab
* NumPy
* OpenCV
* PIL (Pillow)
* Requests
* Matplotlib

## How to Run

The project is implemented as a Jupyter Notebook.

To run the project:

1. Open `Assignment1.ipynb`.
2. Open the notebook in Google Colab.
3. Run the cells sequentially.
4. The notebook downloads the required images from their URLs.
5. Run the image processing operations and view the generated results.

## Repository Structure

```text
Assignment-1-advanced-pixel-level-manipulation-/
│
├── Assignment1.ipynb
└── README.md
```

## Technical Documentation

The complete implementation is available in `Assignment1.ipynb`.

The notebook contains the code and visual results for the image loading, image inspection, pixel-level manipulation, array slicing, random cropping and pasting, grayscale conversion, and sharpening operations described above.

## Version Control

Git and GitHub are used to manage the project and track changes through commits.

The repository is publicly available and contains the assignment notebook and project documentation.

## Training Program

This project was completed as part of the **Computer Vision Course** training program.

## Saudi Digital Academy

Saudi Digital Academy (SDAIA) GitHub account:

https://github.com/SDAIAAcademy

## Course Information

**Course:** Computer Vision

**Assignment:** Assignment 1 – Advanced Pixel-Level Manipulation

## Author

**Rawan Altaweel**

