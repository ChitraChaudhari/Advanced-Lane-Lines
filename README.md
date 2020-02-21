# Advanced Lane Finding

This repository contains code for a project I did as a part of Udacity's Self Driving Car Nano Degree Program. The goal is to write a software pipeline to identify the road lane boundaries in a video.

## The Project

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`. The CAlibration matrix and distortion coefficients are stored in a pickel file in the 'camera_cal' folder.
The images in `test_images` are for testing your pipeline on single frames.    
Examples of the output from each stage of the pipeline are saved in the folder called `output_images`

Project video
Here's a link to my project video result
[](https://youtu.be/_JME_R6wmXE)

Challenge video
Here's a link to my challenge video result
[](https://youtu.be/c69zAN7NcLY )

