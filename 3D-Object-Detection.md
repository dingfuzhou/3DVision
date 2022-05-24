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
    1.7 [Fast Object Detection](#1.7)  
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
  - Towards Open-Set Object Detection and Discovery; [[Paper]](https://arxiv.org/pdf/2204.05604.pdf) 
  - 2022 RBGNet: Ray-based Grouping for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2204.02251.pdf) [[Code]](https://github.com/Haiyang-W/RBGNet) 
  - 2019 Deep Hough Voting for 3D Object Detection in Point Clouds; [[Paper]](https://arxiv.org/pdf/1904.09664.pdf) [[Code]](https://github.com/facebookresearch/votenet) 
  - 2019 Fast Point R-CNN; [[Paper]](https://arxiv.org/pdf/1908.02990.pdf)
  

## 1.2 Voxel based<a name="1.2"></a>    
  - 2022 PillarNet: Real-Time and High-Performance Pillar-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2205.07403.pdf)  
  - 2021 PV-RCNN++: Point-Voxel Feature Set Abstraction With Local Vector Representation for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2102.00463.pdf) [[Code]](https://github.com/open-mmlab/OpenPCDet)  
  - 2021 BEVDetNet: Bird’s Eye View LiDAR Point Cloud based Real-time 3D Object Detection for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2104.10780.pdf)   
  - 2021 DV-Det:Efficient 3D Point Cloud Object Detection with Dynamic Voxelization [[Paper]](https://arxiv.org/pdf/2107.12707.pdf)  
  - 2021 Anchor-free 3D Single Stage Detector with Mask-Guided Attention for Point Cloud; [[Paper]](https://arxiv.org/pdf/2108.03634.pdf) [[Code]]( https://github.com/jialeli1/MGAF-3DSSD) 
  - 2021 Improved Pillar with Fine-grained Feature for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2110.06049.pdf)  
  - 2021 FCAF3D: Fully Convolutional Anchor-Free 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2112.00322.pdf) [[Code]]( https://github.com/samsunglabs/fcaf3d)  
  - 2021 PiFeNet: Pillar-Feature Network for Real-Time 3D Pedestrian Detection from Point Cloud; [[Paper]](https://arxiv.org/abs/2112.15458) 
  - 2021 Point Density-Aware Voxels for LiDAR 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2203.05662.pdf) 
  - 2019 STD: Sparse-to-Dense 3D Object Detector for Point Cloud; [[Paper]](https://arxiv.org/pdf/1907.10471.pdf) 
  - 2021 PV-RCNN: Point-Voxel Feature Set Abstraction for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/1912.13192.pdf) 
  - 2021 Center-based 3D Object Detection and Tracking; [[Paper]](https://arxiv.org/pdf/2006.11275.pdf) [[Code]](https://github.com/tianweiy/CenterPoint) 
  - 2020 AFDet: Anchor Free One Stage 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2006.12671.pdf) 
  - 2022 AFDetV2: Rethinking the Necessity of the Second Stage for Object Detection from Point Clouds; [[Paper]](https://www.aaai.org/AAAI22Papers/AAAI-3350.HuY.pdf) 
  - 2020 Dynamic Edge Weights in Graph Neural Networks for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2009.08253.pdf)  
  - 2020 CIA-SSD: Confident IoU-Aware Single-Stage Object Detector From Point Cloud; [[Paper]](https://arxiv.org/pdf/2012.03015.pdf) [[Code]](https://github.com/Vegeta2020/CIA-SSD) 

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
  - AB3DMOT: A Baseline for 3D Multi-Object Tracking and New Evaluation Metrics; [[Paper]](https://arxiv.org/pdf/2008.08063.pdf) [[Code]](https://www.xinshuoweng.com/projects/AB3DMOT/)  


 ## 1.5 Graph based<a name="1.5"></a>  
  - Grid-GCN for Fast and Scalable Point Cloud Learning; [[Paper]](https://arxiv.org/pdf/1912.02984.pdf) [[Code]](https://github.com/Xharlie/Grid-GCN)
  - Point-GNN: Graph Neural Network for 3D Object Detection in a Point Cloud; [[Paper]](https://arxiv.org/pdf/2003.01251v1.pdf) [[Code]](https://github.com/WeijingShi/Point-GNN)
  - Dynamic Graph CNN for Learning on Point Clouds; [[Paper]](https://arxiv.org/pdf/1801.07829.pdf) [[Code]](https://github.com/WangYueFt/dgcnn)  
  - 2021 Probabilistic 3D Multi-Modal, Multi-Object Tracking for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2012.13755.pdf)

## 1.6 Ground Plane Detection<a name="1.6"></a>  
- GndNet: Fast Ground Plane Estimation and Point Cloud Segmentation for Autonomous Vehicles; [[Paper]](https://hal.inria.fr/hal-02927350/document) [[Code]](https://github.com/anshulpaigwar/GndNet)
  - How to Build a Curb Dataset with LiDAR Data for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2110.03968.pdf) [[Dataset]](https://download.mindspore.cn/)
  - CurbScan: Curb Detection and Tracking Using Multi-Sensor Fusion; [[Paper]](https://arxiv.org/pdf/2010.04837.pdf) [[Dataset]](https://download.mindspore.cn/)
  - Lidar-histogram for fast road and obstacle detection; [[Paper]](https://ieeexplore.ieee.org/document/7989159)

## 1.7 Fast Object Detection<a name="1.7"></a>  
- 2022 AFDetV2: Rethinking the Necessity of the Second Stage for Object Detection from Point Clouds; [[Paper]](https://www.aaai.org/AAAI22Papers/AAAI-3350.HuY.pdf) 
- 2022 PillarNet: Real-Time and High-Performance Pillar-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2205.07403.pdf) 
- 2021 Real-Time Anchor-Free Single-Stage 3D Detection with IoU-Awareness; [[Paper]](https://arxiv.org/pdf/2107.14342.pdf)   
- 2020 AFDet: Anchor Free One Stage 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2006.12671.pdf)  
- 2020 CIA-SSD: Confident IoU-Aware Single-Stage Object Detector From Point Cloud; [[Paper]](https://arxiv.org/pdf/2012.03015.pdf) [[Code]](https://github.com/Vegeta2020/CIA-SSD) 
- 2021 1 st Place Solution for Waymo Open Dataset Challenge - 3D Detection and Domain Adaptation; [[Paper]](https://arxiv.org/pdf/2006.15505.pdf) 
- 2021 CenterPoint: Center-based 3D Object Detection and Tracking; [[Paper]](https://arxiv.org/pdf/2006.11275.pdf)  [[Code]](https://github.com/tianweiy/CenterPoint/tree/master) [[TensorRT implementation]](https://github.com/Abraham423/CenterPoint) [[ONNX and TensorRT]](https://github.com/CarkusL/CenterPoint) 
- 2021 CenterPoint++ submission to the Waymo Real-time 3D Detection Challenge; [[Paper]](https://drive.google.com/file/d/1wG1zPc2PyWgBIC-dLSFbxzeZ3FhA708_/view) [[Code]](https://github.com/tianweiy/CenterPoint/tree/new_release) 
- 2021 RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection; [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_RSN_Range_Sparse_Net_for_Efficient_Accurate_LiDAR_3D_Object_CVPR_2021_paper.pdf)  
- 2021 HVPR: Hybrid Voxel-Point Representation for Single-stage 3D Object Detection; [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Noh_HVPR_Hybrid_Voxel-Point_Representation_for_Single-Stage_3D_Object_Detection_CVPR_2021_paper.pdf)
- 2021 SRDAN: Scale-aware and Range-aware Domain Adaptation Network for Cross-dataset 3D Object Detection; [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_SRDAN_Scale-Aware_and_Range-Aware_Domain_Adaptation_Network_for_Cross-Dataset_3D_CVPR_2021_paper.pdf)
- 2021 PointAugmenting: Cross-Modal Augmentation for 3D Object Detection; [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_PointAugmenting_Cross-Modal_Augmentation_for_3D_Object_Detection_CVPR_2021_paper.pdf) 
- 2021 BEVDetNet: Bird’s Eye View LiDAR Point Cloud based Real-time 3D Object Detection for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2104.10780.pdf)  
- 2021 RangeDet: In Defense of Range View for LiDAR-based 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2103.10039.pdf)


