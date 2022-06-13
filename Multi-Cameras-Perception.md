## SOTA Techniques of Perception with Multiples Cameras

This repository provides an up-to-date list of techniques used for autolabeling project. 
 
=============================
# Table of contents
1.  [DataSets and Benchmarks](#1)  
    1.1 [3D ObjectS Detection](#1.1)  
    1.2 [Lane Segmentation](#1.2)
    1.3 [Auxiliary Tasks](#1.3)   
2. [3D Obstacles Detection](#2)  
    2.1 [Bird's-Eye-View Based](#2.1)  
    2.2 [Multi-Modals Fusion](#2.2)    
3. [Road Markers Detection](#3)  
    3.1 [Lanes Segmentation](#3.1)  
    3.2 [Lights and other Signs Detection](#3.2)  

----------------------------------
# 1. DataSets and Benchmarks <a name="1"></a>  
## 1.1 3D ObjectS Detection<a name="1.1"></a>
  - nuscenes a multimodal dataset for autonomous driving; [[Paper]](https://arxiv.org/pdf/1903.11027.pdf) [[Project]](https://www.nuscenes.org/) 
  - Argoverse: 3D Tracking and Forecasting with Rich Maps; [[Paper]](https://arxiv.org/pdf/1911.02620.pdf) [[Project]](https://www.argoverse.org/) 
  - Data - Lyft's Level 5; [[Paper]](https://arxiv.org/pdf/2006.14480.pdf) [[Project]](https://level-5.global/data/)
  - Scalability in Perception for Autonomous Driving: Waymo Open Dataset; [[Paper]](https://arxiv.org/pdf/1912.04838.pdf) [[Project]](https://waymo.com/open/) 
  
## 1.2 Lane Segmentation<a name="1.2"></a>  
 - PersFormer: 3D Lane Detection via Perspective Transformer and the OpenLane Benchmark; [[Paper]](https://arxiv.org/pdf/2203.11089.pdf) [[Project]](https://github.com/OpenPerceptionX/PersFormer_3DLane) [[Datasets]](https://github.com/OpenPerceptionX/OpenLane)  
 - Spatial As Deep: Spatial CNN for Traffic Scene Understanding; [[Paper]](https://arxiv.org/pdf/1712.06080.pdf) [[Project]](https://xingangpan.github.io/projects/CULane.html)  
 - tusimple benchmark; [[Project]](https://github.com/TuSimple/tusimple-benchmark/tree/master/doc/lane_detection)   
 - ONCE-3DLanes: Building Monocular 3D Lane Detection; [[Paper]](https://arxiv.org/pdf/2205.00301.pdf) [[Project]](https://once-3dlanes.github.io/)  
## 1.3 Auxiliary Tasks <a name="1.3"></a> 
 - Is Pseudo-Lidar needed for Monocular 3D Object detection? ; [[Paper]](https://arxiv.org/pdf/2108.06417.pdf) [[Project]](https://github.com/TRI-ML/dd3d)  
 - Categorical Depth Distribution Network for Monocular 3D Object Detection;[[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Reading_Categorical_Depth_Distribution_Network_for_Monocular_3D_Object_Detection_CVPR_2021_paper.pdf) [[Project]](https://github.com/TRAILab/CaDDN)  

# 2 3D Obstacles Detection <a name="2"></a>   
## 2.1 Bird's-Eye-View Based<a name="2.1"></a> 
  - 2022 BEVerse: Unified Perception and Prediction in Birds-Eye-View for Vision-Centric Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2205.09743.pdf) [[Project]](https://github.com/zhangyp15/BEVerse)
  - 2022 CVPR Cross-view Transformers for real-time Map-view Semantic Segmentation; [[Paper]](http://www.philkr.net/media/zhou2022crossview.pdf) [[Project]](https://github.com/bradyz/cross_view_transformers)  
  - 2021 BEVDet: High-Performance Multi-Camera 3D Object Detection in Bird-Eye-View; [[Paper]](https://arxiv.org/pdf/2112.11790.pdf) [[Project]](https://github.com/HuangJunJie2017/BEVDet) 
  - 2022 BEVDet4D: Exploit Temporal Cues in Multi-camera 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2203.17054.pdf) [[Project]](https://github.com/HuangJunJie2017/BEVDet) 
  - 2022 BEVFormer: Learning Bird’s-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers; [[Paper]](https://arxiv.org/pdf/2203.17270.pdf) [[Project]](https://github.com/zhiqi-li/BEVFormer)
  - 2022 PETR: Position Embedding Transformation for Multi-View 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2203.05625.pdf) [[Project]](https://github.com/megvii-research/PETR)  
  - 2022 PETRv2: A Unified Framework for 3D Perception from Multi-Camera Images; [[Paper]](https://arxiv.org/pdf/2206.01256.pdf) [[Project]](https://github.com/megvii-research/PETR)  
  - 2022 M2BEV: Multi-Camera Joint 3D Detection and Segmentation with Unified Bird’s-Eye View Representation; [[Paper]](https://arxiv.org/pdf/2204.05088.pdf) [[Project]](https://xieenze.github.io/projects/m2bev/) 
  - HFT: Lifting Perspective Representations via Hybrid Feature Transformation; [[Paper]](https://arxiv.org/pdf/2204.05068.pdf) [[Project]](https://github.com/JiayuZou2020/HFT) 
  - PersFormer: 3D Lane Detection via Perspective Transformer and the OpenLane Benchmark; [[Paper]](https://arxiv.org/pdf/2203.11089.pdf) [[Project]](https://github.com/OpenPerceptionX/PersFormer_3DLane) [[Datasets]](https://github.com/OpenPerceptionX/OpenLane)
  - BEVSegFormer: Bird’s Eye View Semantic Segmentation From Arbitrary Camera Rigs; [[Paper]](https://arxiv.org/pdf/2203.04050.pdf)
  - FIERY: Future Instance Prediction in Bird's-Eye View from Surround Monocular Cameras; [[Paper]](https://arxiv.org/pdf/2104.10490.pdf)[[Project]](https://github.com/wayveai/fiery) 
  - HDMapNet: An Online HD Map Construction and Evaluation Framework; [[Paper]](https://arxiv.org/pdf/2107.06307.pdf) [[Project]](https://github.com/Tsinghua-MARS-Lab/HDMapNet)  
  - End-to-end Birds-eye-view Flow Estimation for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2008.01179.pdf)  
  - Bird's-Eye-View Panoptic Segmentation Using Monocular Frontal View Images; [[Project]](http://panoptic-bev.cs.uni-freiburg.de/#main)  [[Code]](https://github.com/robot-learning-freiburg/PanopticBEV)  
  - BEV-MODNet: Monocular Camera based Bird’s Eye View Moving Object Detection for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2107.04937.pdf)  [[Project]](https://sites.google.com/view/bev-modnet)  
  - StretchBEV: Stretching Future Instance Prediction Spatially and Temporally; [[Paper]](https://arxiv.org/pdf/2203.13641.pdf)  [[Project]](https://sites.google.com/view/bev-modnet)  
  - GitNet: Geometric Prior-based Transformation for Birds-Eye-View Segmentation ; [[Paper]](https://arxiv.org/pdf/2204.07733.pdf) 
  - Translating Images into Maps; [[Paper]](https://arxiv.org/pdf/2110.00966.pdf) 
  - Structured Bird’s-Eye-View Traffic Scene Understanding from Onboard Images; [[Paper]](https://arxiv.org/pdf/2110.01997.pdf) [[Project]](https://github.com/ybarancan/STSU)  
  - MPPNet: Multi-Frame Feature Intertwining with Proxy Points for 3D Temporal Object Detection; [[Paper]](https://arxiv.org/pdf/2205.05979.pdf)  
  - CVPR 2021 Projecting Your View Attentively: Monocular Road Scene Layout Estimation via Cross-view Transformation; [[Paper]](https://arxiv.org/pdf/2112.11790.pdf) 
  - ICCV 2021 NEAT: Neural Attention Fields for End-to-End Autonomous Driving;   [[Paper]]( [[Paper]](https://arxiv.org/pdf/2112.11790.pdf)) [[Project]](https://github.com/autonomousvision/neat)

## 2.2 Multi-Modals Fusion<a name="2.2"></a>   
   - 2022 MVFuseNet: Improving End-to-End Object Detection and Motion Forecasting through Multi-View Fusion of LiDAR Data; [[Paper]](https://arxiv.org/pdf/2104.10772.pdf)  
   - Exploiting Temporal Relations on Radar Perception for Autonomous Driving; [[Paper]](https://arxiv.org/pdf/2204.01184.pdf)  
   - 2022 BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird’s-Eye View Representation; [[Paper]](https://arxiv.org/pdf/2205.13542.pdf)  [[Project]](https://bevfusion.mit.edu/)  
   - 2022 BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework; [[Paper]](https://arxiv.org/abs/2205.13790) [[Project]](https://github.com/ADLab-AutoDrive/BEVFusion) 
   - 2022 Unifying Voxel-based Representation with Transformer for 3D Object Detection; [[Paper]](https://arxiv.org/pdf/2206.00630.pdf) [[Project]](https://github.com/dvlab-research/UVTR) 
    
# 3 Road Markers Detection <a name="3"></a>   
## 3.1 Lanes Segmentation<a name="3.1"></a>   
## 3.2 Lights and other Signs Detection<a name="3.2"></a>   


 
