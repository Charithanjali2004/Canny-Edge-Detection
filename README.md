# Canny-Edge-Detection
# AIM
Loaded a nature image in grayscale

Applied Canny edge detection with 3 different parameter settings

Compared results side by side

Created interactive mode with sliders for real-time tuning

Saved edge detection outputs as image files
# Software Requirement:
Python 3.6 or higher
## Libraries:

OpenCV (cv2)
NumPy
Matplotlib
## Hardware:
Any computer (basic specs work fine)
## Input:
One image file named nature.png in the same folder
## Output:
Three edge detection result images (JPG format)
# Algorithm
## Step 1: Input Image

Read the input image and convert it to grayscale if necessary.

## Step 2: Noise Reduction

Apply a Gaussian filter to remove noise and smooth the image.

## Step 3: Gradient Computation

Calculate the gradient magnitude and direction using Sobel operators.

## Step 4: Non-Maximum Suppression

Thin the edges by retaining only the local maximum gradient values.

## Step 5: Double Thresholding

Apply high and low threshold values to classify pixels as:

Strong edges
Weak edges
Non-edges
## Step 6: Edge Tracking by Hysteresis

Connect weak edges that are linked to strong edges and remove unwanted weak edges.

## Step 7: Output

Display the final edge-detected image.
# PARAMETERS TESTED
<img width="522" height="197" alt="image" src="https://github.com/user-attachments/assets/2e8974d3-150c-4bae-bd94-580163c10f79" />

# Result
Thus, the edges present in the given image are successfully detected using the Canny Edge Detection.
