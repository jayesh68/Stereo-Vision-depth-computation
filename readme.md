<div align="center">
<h1>Application of Stereo Vision Concepts to compute Depth</h1>
</div>

<h1>Project Objectives</h1>
The objectives as part of this project are to identify the similarities between two images captured from different viewpoints by using different techniques such as:
<ol>
<li>Calibration: To identify similar keypoints and compute the descriptors using SIFT which would eventually be used to obtain a matching set of features. This can be used to obtain the fundamental and essential matrix to estimate the camera pose by Triangulation. </li>
<li>Rectification: To ensure that the epipolar lines of the two images are horizontal by using the Fundamental Matrix and Perspective Transformation</li>
<li>Correspondence: To represent the image based on disparity by performing Single Squared Differences (SSD) between the two images</li>
<li>Depth Computation: To represent the image based on depth using the disparity map.
</ol>
  
<h1>Calibration to obtain matching features</h1>
<p float="left">
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/Matching%20features_screenshot_24.04.2021.png" />
</p>
  

<h1>Rectification</h1>
<h2>Before Rectification</h2>
<p float="left">
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/eplines1.png" width="300" height="300" />
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/epilines2.png" width="300" height="300"/>
</p>

<h2>Post Rectification</h2>
<p float="left">
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/rect31.png" width="300" height="300" />
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/rect32.png" width="300" height="300"/>
</p>

<h1>Correspondence</h1>
<p align="center">
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/disparity_heatmap.png" width="300" height="300"/>
</p>

<h1>Depth Computation</h1>
<p align="center">
<img src="https://github.com/jayesh68/Stereo-Vision-depth-computation/blob/main/Depth_heatmap.png" width="300" height="300"/>
</p>

<h1>Link to view the project results</h1>
<ul>
<li>https://drive.google.com/drive/u/1/folders/1Vcu5PJhNyyuwyRqADPB10XExcMqjDu4b</li>
</ul>
