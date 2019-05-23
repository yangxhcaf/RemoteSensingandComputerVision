# Reading List

## Atmospheric Sciences
1. [Atmospheric Science](http://cup.aos.wisc.edu/453/2016/readings/Atmospheric_Science-Wallace_Hobbs.pdf) by JONH M. WALLACE and PETER V. HOBBS


## Remote Sensing

## Computer Vision
### Machine Learning Basics
1. [神经网络与深度学习](https://github.com/nndl/nndl.github.io)
2. [Generating Videos with Scene Dynamics/GAN](https://github.com/chrimerss/RemoteSensingandComputerVision/blob/master/ComputerVision/Generating_Videos_with_Scene_Dynamics.pdf)

### Numerical Methods
#### Optical Flow
Methods:

>Lucas-Kanade method:  it tracks the corner with Shi-Tomasi algorithm and calculate (u,v) by solving 9 equations and then estimate the 3x3 patch movement;

~~~~
cv2.calcOpticalFlowPyrLK
~~~~

>Gunner Farneback's algorithm (Dense): It computes the optical flow for all the points in the frame;

~~~~
cv2.calcOpticalFlowFarneback
~~~~

1. [Optical flow models as an open benchmark for radar-based precipitation nowcasting](https://github.com/chrimerss/RemoteSensingandComputerVision/blob/master/NumericalMethods/OpticalFlow/Optical_flow_mdoels_as_an_open_benchmark_for_radar-based_precipitation_nowcasting.pdf)
    >Codes available on github: [optical flow](https://github.com/hydrogo/rainymotion)
2. [Novel Video Prediction for Large-scale Scene using
Optical Flow](https://github.com/chrimerss/RemoteSensingandComputerVision/blob/master/NumericalMethods/OpticalFlow/new_video_predction_for_large_scale_scene_using_optical_flow.pdf)
3. [Two Frame Motion Estimation Based on Polynomial Expansion](https://github.com/chrimerss/RemoteSensingandComputerVision/blob/master/NumericalMethods/OpticalFlow/Two_Frame_Motion_Estimation_Based_on_Polynomial_Expansion.pdf)
4. [my radar project demo](https://github.com/chrimerss/)

# Updates
- [x] optical flow models as an open benchmark for radar-based precipitation nowcasting (2019.5.16)
- [x] Novel Video Prediction for Large-scale Scene using Optical Flow (2019.5.16)
- [x] Generating Videos with Scene Dynamics/GAN (2019.5.16)
- [x] 神经网络与深度学习 (2019.5.22)
- [ ] Two Frame Motion Estimation Based on Polynomial Expansion
