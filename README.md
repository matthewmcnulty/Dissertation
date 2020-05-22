# Instance Segmentation of Wildfires using Mask Region-Based Convolutional Neural Network

Climate Change (CC) is bringing about extreme weather and catastrophe events throughout all corners of the world. The effects of CC have exacerbated the necessary conditions that fuel large scale wildland fires. However, the burning of their carbon stores also plays a major role in the vicious feedback cycle. These catastrophe events threaten the local biodiversity and nearby human life. Manually tracking the progression of these wildfires is often difficult for firefighters, leading to large uncontrolled outbreaks. This thesis aims to develop a Computer Vision (CV) algorithm for an Unmanned Aerial Vehicle (UAV) camera that can autonomously detect wildfires in real-time. 

Rather than only using bounding boxes to detect wildfires, this dissertation took this one step further by investigating the applicability of instance segmentation to wildfires. This alternative object detection technique can delineate the approximate pixel boundaries of the actual fire. The advantage of instance segmentation is that it can provide the coordinates of wildfires, whereas simple bounding boxes cannot. The state-of-the-art instance segmentation algorithm Mask R-CNN was used to tackle the problem. This algorithm was trained on real images of fires in open environments. Many of the parameters were tuned to achieve the optimal model for effective wildfire instance segmentation. The applicability of algorithm was then tested on aerial images of wildfire fronts taken from a drone. Top-down perspectives showcased impressive results by highlighting the exact ground location of the wildfire. However, further experimentation is required to provide similar ability under variations in angle and distance. 
