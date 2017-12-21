# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goal of this project is to:
* Make a pipeline that finds lane lines on the road


[//]: # (Image References)

[image1]: ./test_images_output/solidWhiteCurve.jpg "solidWhiteCurve"
[image2]: ./test_images_output/solidWhiteRight.jpg "solidWhiteRight"
[image3]: ./test_images_output/solidYellowCurve.jpg "solidYellowCurve"
[image4]: ./test_images_output/solidYellowCurve2.jpg "solidYellowCurve2"
[image5]: ./test_images_output/solidYellowLeft.jpg "solidYellowLeft"
[image6]: ./test_images_output/whiteCarLaneSwitch.jpg "whiteCarLaneSwitch"

---

### Reflection

### 1. Pipeline Description 

This pipeline consisted of 6 steps:
* Converting the images to grayscale
* Applying Gaussian smoothing Module
* Using Canny Edge Detection Module 
* Selecting the region of interest 
* Applying Hough Tranform line detection
* Combining images.

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by getting the lines' slopes

![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]
![alt text][image6]


### 2. Potential shortcomings with the current pipeline


* Image processing could be faster


### 3. Possible improvements to the current pipeline

* Challenge part is not comleted yet and curvy lanes should be worked on
