# Advanced_Lane_Lines_Project
This project was an expansion on the original lane lines project that I did through Udacity's Self Driving Car Nanodegree. 
- A complete description of techniques used and results obtained are described in **Advanced_Lane_Lines_Writeup.pdf**. 

- The code and visualizations for the advanced project are included in **P3.ipynb**. Techniques used in this file include:  
1. Camera calibration using OpenCV.  
2. Distortion correction.  
3. HSV colorspace mapping, s-channel isolation.
4. Canny transform.  
5. Sobel transform.
6. Thresholding and cropping.  
7. Perspective transform.
8. Sliding window search using histograms to detect lane lines in each frame.  
9. Object oriented approach to dynamic lane line tracking from frame to frame.  
10. Polynomial fitting to model and determine curvature.  
11. Drawing detected lane lines on each frame in the video.  
  
- The code and visualizations for the original project are included in **P1.ipynb**. Techniques used in this file include:   
1. Canny transform  
2. Gaussian blur  
3. Hough transform  
4. K-means clustering (from sklearn)  


- The resulting video from the advanced project is in the 'output_videos' folder. The resulting videos from the original project are in the 'test_videos_output' folder.
