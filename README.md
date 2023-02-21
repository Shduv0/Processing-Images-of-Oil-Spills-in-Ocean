# Processing-Images-of-Oil-Spills-in-Ocean
This project aims to enhance the images of oil spills in the oceans and to help accurately classify them as having an oil spill or not. The goal of this project is to detect the spills in a timely manner, reducing their impact on the marine ecosystem and the coastal areas.

## Problem Definition
The increasing number of oil spills in the oceans from oil tankers is causing severe harm to the marine ecosystem and the coastal areas. Detecting the spills in a timely manner is crucial in reducing their impact.

## Project Goal
The goal of this project is to enhance the images of oil spills in the oceans using image processing techniques. In the next stage, a Convolutional Neural Network (CNN) will be employed to inform the competent authorities and reduce the impact of oil spills on the marine ecosystem.

## Tools
The project uses Jupyter and OpenCV along with Python libraries like numpy, pandas, and matplotlib.

## Processing Identification
Image enhancement

## Methodology
- Conversion of RGB to Grayscale image
- Transform Image to Gray-Negative
- Smoothing image (Image Blurring) using Guassian filter and
- median Blur, bilateral
- Histogram Equalization
- Adaptive image thresholding using Otsu's thresholding method
#### have experimented with many methodologies, including:
- Color-space , help in Object Tracking
- Canny Edge Detection

## Analysis & Discussion
- The color spaces:
can show whether shadow/highlight detail and color saturation can be retained. And in the first image, the part is not clear, but in the second and third image, the part is clearly visible.
- Histogram Equalization:
it is important in processing images and distributing intensity in images to help in the process of Canny
Edge and Otsu's thersholding.
- The Otsu thresholding:
process is expected to highlight regions in the oil spill, which will aid in the subsequent stage of the project for object extraction using K-Means clustering, the second image produced the optimal outcomes.
- The Canny Edge:
detection method produced remarkable outcomes for all three images that would be utilized in the subsequent phase if a Convolutional Neural Network (CNN) were employed.

## Conclusion
In conclusion,  Each method used is helpful in its own way, but the most valuable one is Otsu's thresholding since it converts the pictures into small dots, which is useful in order to classify in clustering the K-means and CNN.

## References
- Remote Sensing | Free Full-Text | Oil Spill Detection Using Machine
Learning and Infrared Images (mdpi.com)
- https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html
- https://github.com/d-elicio/Oil-Spill-Detection-in-SAR-images
