## 3D Object Detection: An Overview
This repository provides an up-to-date list of 3D Object Detection works. 
 
=============================
# Table of contents
1. [Lidar based 3D Object Detection](#1)  
    1.1 [Point Cloud based](#1.1)  
    1.2 [Voxel based](#1.2)  
    1.3 [Range Image based](#1.3)  
    1.4 [Detection and Tracking](#1.4)  
    1.5 [Graph based](#1.5)  
    1.6 [Ground Plane Detection](#1.6)  
2. [Camera based 3D Object Detection](#2)  
	2.1 [xxxxxx](#2.1)  
	2.2  [xxxxxx](#2.2)  
	2.3  [xxxxx](#2.3)   
3. [Fusion based 3D Object Detection](#3)  
	3.1 [xxxxx](#3.1)  
	3.2 [xxxxx](#3.2)  
	3.3 [xxxxx](#3.3)  


----------------------------------
# 1. Lidar based 3D Object Detection <a name="1"></a>  
## 1.1 Point Cloud based<a name="1.1"></a>
  - SE-SSD: Self-Ensembling Single-Stage Object Detector From Point Cloud; [[Paper]](https://arxiv.org/pdf/2104.09804.pdf) [[Code]](https://github.com/Vegeta2020/SE-SSD) 
  - Voxel R-CNN:Towards High Performance Voxel-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2012.15712.pdf) [[Code]](https://github.com/djiajunustc/Voxel-R-CNN)
  - 3DSSD: Point-based 3D Single Stage Object Detector; [[Paper]](https://arxiv.org/pdf/2002.10187.pdf) [[Code]](https://github.com/dvlab-research/3DSSD)
  - SASA: Semantics-Augmented Set Abstraction for Point-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2201.01976.pdf) [[Code]]( https://github.com/blakechen97/SASA)
  -  Not All Points Are Equal: Learning Highly Efficient Point-based Detectors for 3D LiDAR Point Clouds; [[Paper]](https://arxiv.org/pdf/2203.11139.pdf) [[Code]](https://github.com/yifanzhang713/IA-SSD)
  - Focal Sparse Convolutional Networks for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2204.12463) [[Code]](https://github.com/dvlab-research/FocalsConv)
  - LiDAR Distillation: Bridging the Beam-Induced Domain Gap for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2203.14956.pdf) [[Code]](https://github.com/weiyithu/LiDAR-Distillation)
  - Point Density-Aware Voxels for LiDAR 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2203.05662.pdf) [[Code]](https://github.com/TRAILab/PDV)
  - OccAM’s Laser: Occlusion-based Attribution Maps for 3D Object Detectors on LiDAR Data; [[Paper]](https://arxiv.org/pdf/2203.05662.pdf) [[Code]](https://github.com/dschinagl/occam)
  - Pillar-based Object Detection for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2007.10323.pdf) [[Code]](https://github.com/WangYueFt/pillar-od) 
  - Behind the Curtain: Learning Occluded Shapes for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2112.02205.pdf) [[Code]](https://github.com/Xharlie/BtcDet) 
  - An LSTM Approach to Temporal3D Object Detection in LiDAR P oint Clouds; [[Paper]](https://arxiv.org/pdf/2007.12392.pdf) [[Code]](https://github.com/google-research/google-research/tree/master/tf3d) 
  - A VERSATILE MULTI-VIEW FRAMEWORK FOR LIDAR-BASED 3D OBJECT DETECTION WITH GUIDANCE FROM PANOPTIC SEGMENTATION [[Paper]](https://arxiv.org/pdf/2203.02133.pdf) 
  - Point2Seq: Detecting 3D Objects as Sequences; [[Paper]](https://arxiv.org/pdf/2203.13394.pdf) 
  - Super Fast and Accurate 3D Object Detection based on 3D LiDAR Point Clouds; [[Code]](https://github.com/maudzung/SFA3D) 
  - Identifying Unknown Instances for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/1910.11296.pdf) 
  - Deep Multi-Sensor Lane Detection; [[Paper]](https://arxiv.org/pdf/1905.01555.pdf) 
  - Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting with a Single Convolutional Net; [[Paper]](https://arxiv.org/pdf/2012.12395.pdf) 
  - PIXOR: Real-time 3D Object Detection from Point Clouds; [[Paper]](https://arxiv.org/pdf/1902.06326.pdf) 
  - Efficient Convolutions for Real-Time Semantic Segmentation of 3D Point Clouds; [[Paper]](https://www.cs.toronto.edu/~urtasun/publications/zhang_etal_3dv18.pdf) 
  - Open-set 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2112.01135.pdf) 
  - ORDER: Open World Object Detectionon Road Scenes; [[Paper]](https://ml4ad.github.io/files/papers2021/ORDER:%20Open%20World%20Object%20Detection%20on%20Road%20Scenes.pdf) 
  
 


## 1.2 Voxel based<a name="1.2"></a>  
  - Voxel based 3D object detections  

## 1.3 Range Image based<a name="1.3"></a>  
  - RangeSeg: Range-Aware Real Time Segmentation of 3D LiDAR Point Clouds; [[Paper]](https://arxiv.org/pdf/2205.01570.pdf)  
  - To the Point: Efficient 3D Object Detection in the Range Image with Graph Convolution Kernels; [[Paper]](https://arxiv.org/pdf/2106.13381.pdf) 
  - RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2106.13365.pdf) 
  - RangeDet: In Defense of Range View for LiDAR-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2106.13365.pdf) 
  - RangeRCNN: Towards Fast and Accurate 3D Object Detection with Range Image Representation; [[Paper]](https://arxiv.org/pdf/2009.00206.pdf) 
  - Range Conditioned Dilated Convolutions for Scale Invariant 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2204.06577.pdf) 

## 1.4 Detection and Tracking<a name="1.4"></a>    
  - Exploring Simple 3D Multi-Object Tracking for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2108.10312.pdf) [[Code]](https://github.com/qcraftai/simtrack)
  - You Don't Only Look Once: Constructing Spatial-Temporal Memory for Integrated 3D Object Detection and Tracking;  [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Sun_You_Dont_Only_Look_Once_Constructing_Spatial-Temporal_Memory_for_Integrated_ICCV_2021_paper.pdf) [[Code]](https://github.com/zju3dv/UDOLO)
  - Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds; [[Paper]](https://arxiv.org/pdf/2203.01730.pdf) [[Code]](https://github.com/Ghostish/Open3DSOT)
  - TPCN: Temporal Point Cloud Networks for Motion Forecasting; [[Paper]](https://arxiv.org/pdf/2103.03067.pdf)
  - PointTrackNet: An End-to-End Network for 3-D Object Detection and Tracking from Point Clouds; [[Paper]](https://arxiv.org/pdf/2002.11559.pdf) 
 ## 1.5 Graph based<a name="1.5"></a>  
  - Grid-GCN for Fast and Scalable Point Cloud Learning; [[Paper]](https://arxiv.org/pdf/1912.02984.pdf) [[Code]](https://github.com/Xharlie/Grid-GCN)
  - Point-GNN: Graph Neural Network for 3D Object Detection in a Point Cloud; [[Paper]](https://arxiv.org/pdf/2003.01251v1.pdf) [[Code]](https://github.com/WeijingShi/Point-GNN)
  - Dynamic Graph CNN for Learning on Point Clouds; [[Paper]](https://arxiv.org/pdf/1801.07829.pdf) [[Code]](https://github.com/WangYueFt/dgcnn)

## 1.6 Ground Plane Detection<a name="1.6"></a>    
  - GndNet: Fast Ground Plane Estimation and Point Cloud Segmentation for Autonomous Vehicles; [[Paper]](https://hal.inria.fr/hal-02927350/document) [[Code]](https://github.com/anshulpaigwar/GndNet)
  - How to Build a Curb Dataset with LiDAR Data for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2110.03968.pdf) [[Dataset]](https://download.mindspore.cn/)
  - CurbScan: Curb Detection and Tracking Using Multi-Sensor Fusion; [[Paper]](https://arxiv.org/pdf/2010.04837.pdf) [[Dataset]](https://download.mindspore.cn/)
  - Lidar-histogram for fast road and obstacle detection; [[Paper]](https://ieeexplore.ieee.org/document/7989159)




  
