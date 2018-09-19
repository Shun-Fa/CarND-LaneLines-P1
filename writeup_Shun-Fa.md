# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of what I learn from the class. 
First, I converted the images as the below setps I did.
(1)grayscale
(2)canny edages
(3)region masking
(4)hough transform
In order to draw a single line on the left and right lanes, I am using the method which creating 2 lime image and meage them then to reach draw pipe line at left side and right side.


### 2. Identify potential shortcomings with your current pipeline

1. The pipeline drawing insdie my code isn't efficiency, especially it is creating the video. 
2. The pipeline drawing isn't able to draw the line in 100% correct. 

### 3. Suggest possible improvements to your pipeline
1. Due to this is base on the gray image, the image source has to be more accurate.Maybe we can add the "white balance" function to setup/calibrate the image source at the image sensor level.
2. Possible to use G-sensor to detect the motion of car let the mask region can be adjust according to that.

### 4. Personal skill improvment
1. I should improve my coding skill due to I am new to coding and had did the try to use "define" function let entire codes can be more efficiency. 
2. I still need to study and understrand those algorithm and tuning parameters insdie the funciton. 
