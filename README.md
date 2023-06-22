## Awesome SLAM



本仓库由[公众号【自动驾驶之心】](https://mp.weixin.qq.com/s?__biz=Mzg2NzUxNTU1OA==&mid=2247542481&idx=1&sn=c6d8609491a128233c3c3b91d68d22a6&chksm=ceb80b18f9cf820e789efd75947633aec9d2f1e8b58c29e5051c05a64b21ae63c244d54886a1&token=11182364&lang=zh_CN#rd) 团队整理，欢迎关注，一览最前沿的技术分享！

自动驾驶之心是国内首个自动驾驶开发者社区！这里有最全面有效的自动驾驶与AI学习路线（感知/定位/融合）和自动驾驶与AI公司内推机会！



## 一、**SLAM领域经典文章汇总** | Papers about SLAM

### 1.经典文章汇总 | Summary of classic articles 

From SLAM to Situational Awareness: Challenges and Survey(2021)

Keyframe-based monocular SLAM：design, survey, and future directions(2018) 

RGB-Depth SLAM Review(2018) 

Past, Present, and Future of Simultaneous Localization And Mapping: Towards the Robust-Perception Age(2017) 

The Revisiting Problem in Simultaneous Localization and Mapping: A Survey on Visual Loop Closure Detection(2022) 

Advances in inference and representation for simultaneous localization and mapping(2021)

### 2.**SLAM 算法在各种硬件平台上的实现和性能综述**

Hardware implementation of SLAM algorithms: a survey  on implementation approaches and platforms

### 3.深度学习惯性定位综述 2023.03

Deep Learning for Inertial Positioning: A Survey

### 4.Active SLAM: A Review On Last Decade 2023

Active SLAM: A Review On Last Decade



## 二、**视觉SLAM** | Visual SLAM  

### 1.**视觉SLAM最新调研综述** | Survey

Visual SLAM: What are the Current Trends and What to Expect?

### 2.视觉SLAM 里程碑工作汇总 | Visual SLAM milestone work

MonoSLAM Real-time single camera SLAM(PAMI 2007) 

Parallel tracking and mapping for small ar workspaces (2007ISMAR) 

DTAM: Dense tracking and mapping in real-time 

3D mapping with an RGB-D camera(2013 TRO) 

SLAM++ Simultaneous Localisation and Mapping at the Level of Objects(CVPR 2013) 

SVO Fast semi-direct monocular visual odometry(ICRA 2014) 7. LSD-SLAM Large-scale direct monocular SLAM

ORB-SLAM a versatile and accurate monocular SLAM system（TOR 2015） 

Orb-slam2 An open-source slam system for monocular, stereo, and rgb-d cameras（TRO 2017） 

Orb-slam3 An accurate open-source library for visual, visual–inertial, and multimap slam（TRO 2021）

CNN-SLAM Real-time dense monocular SLAM with learned depth prediction（CVPR 2017） 

Direct_Sparse_Odometry

### 3. **单目SLAM结合NeRF提升几何和光度精度**

NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields

### 4. **视觉SLAM基于深度学习的回环检测方法汇总**

### Loopback detection method based on deep learning

Role of Deep Learning in Loop Closure Detection for Visual（2021综述） 

Comparison of camera-based and 3D LiDAR-based loop closures across weather conditions(2020) 

Compressed holistic convnet representations for detecting loop closures in dynamic environments(2020) 

Condition-Invariant Multi-View Place Recognition(2019) 

Loop Closure Detection Based on Multi-Scale Deep Feature Fusion（2019） 

Lightweight unsupervised deep loop closure(2018) 

Single-View Place Recognition under Seasonal Changes(2018) 

### 5. **视觉SLAM特征处理常用算子**

### Visual SLAM feature processing common operators

A comparative analysis of sift, surf, kaze, akaze, orb, and brisk(2018) 

Image matching using SIFT, SURF, BRIEF and ORB performance comparison for distorted images（2017） 

Features from accelerated segment test (fast)（2014） 

ORB An efficient alternative to SIFT or SURF（2011） 

Brief Binary robust independent elementary features（2010） 

Surf Speeded up robust features（2006） 

Distinctive image features from scale-invariant key-points（2004）

### 6. **V-SLAM综述**

Visual-SLAM Classical Framework and Key Techniques:  A Review

### 7. **视觉SLAM的研究现状综述 2023.2**

A review of visual SLAM methods for autonomous driving vehicles

### 8. **自主导航最新综述**

A Comprehensive Review on Autonomous Navigation

### 9. 基于事件的视觉SLAM综述2023.04

Event-based Simultaneous Localization and Mapping: A Comprehensive Survey

[[Link]](https://github.com/kun150kun/ESLAM-survey)



## 三、**激光SLAM** | Lidar SLAM

### 1.**激光SLAM综述两篇** Survey

A Comparative Survey of LiDAR-SLAM and LiDAR based Sensor Technologies 

A Comparative Analysis of LiDAR SLAM-based Indoor Navigation for Autonomous Vehicles

### 2.**自动驾驶中的LiDAR SLAM技术**

Lidar SLAM for Autonomous Driving Vehicles

### 3.**PFilter**

PFilter:  Building  Persistent  Maps  through  Feature  Filtering  for  Fastand  Accurate  LiDAR-based  SLAM

### 4.**激光融合多传感器SLAM** 

### Laser fusion multi-sensor SLAM

A Review of Multi-Sensor Fusion SLAM Systems Based on 3D LIDAR

A Review of Visual-LiDAR Fusion based Simultaneous Localization and Mapping

LI-SLAM  Fusing  LiDAR  and  Infrared  Camera  for  Simultaneous Localization and Mapping

A new EKF SLAM algorithm of lidar-based AGV fused with bearing information

A Simultaneous Localization and Mapping (SLAM) Framework for 2.5D Map Building Based on Low-Cost LiDAR and Vision Fusion

MCS-SLAM Multi-Cues Multi-Sensors Fusion SLAM

### 5.**纯激光SLAM经典算法文章汇总（一）**

Localization and Mapping for UGV in Dynamic Scenes with Dynamic Objects Eliminated 

When Geometry is not Enough:Using Reflector Markers in Lidar SLAM 

3D LiDAR SLAM Integration with GPS/INS for UAVs in Urban GPS-Degraded Environments 

An Integrated GNSS/INS/LiDAR-SLAM Positioning Method for Highly Accurate Forest Stem Mapping 

SuMa++: Efficient LiDAR-based Semantic SLAM 6. ART-SLAM Accurate Real-Time 6DoF LiDAR SLAM 

Ground-SLAM: Ground Constrained LiDAR SLAM for Structured Multi-Floor Environments 

Elasticity Meets Continuous-Time: Map-Centric Dense 3D LiDAR SLAM

### 6.**激光SLAM 回环检测方向论文汇总（一）**

Real-Time Loop Closure in 2D LIDAR SLAM

OverlapNet Loop Closing for LiDAR-based SLAM

A LiDAR-Visual SLAM Backend with Loop Closure Detection and Graph Optimization

Fast Closed-Loop SLAM based on the fusion of IMU and Lidar

Have I Seen This Place Before A Fast and Robust Loop Detection and Correction Method for 3D Lidar SLAM

LCDNet Deep Loop Closure Detection and Point Cloud Registration for LiDAR SLAM

### 7.**Cartographer glass：基于优化的SLAM算法中检测和包含玻璃物体的算法**

Cartographer glass: 2D Graph SLAM Framework using LiDAR for Glass Environments

### 8.**maplab2.0：方便的SLAM系统集成**

maplab 2.0 – A Modular and Multi-Modal Mapping Framework

[[Code]](https://github.com/ethz-asl/maplab)



## 四、**毫米波SLAM** | Radar SLAM

### 1.**基于毫米波雷达的 SLAM 框架 MAROAM**

MAROAM: Map-based Radar SLAM through Two-step Feature Selection



## 五、**代码大全** | Code

### 1.**SLAM参考视频**

[[Link]](https://github.com/engcang/SLAM-application#-video-lego-loam-vs-lio-sam-vs-lvi-sam)

### 2.**视觉SLAM** | Visual SLAM

ORB-SLAM2

[[Code]](https://github.com/raulmur/ORB_SLAM2)

ORB-SLAM3

[[Code]](https://github.com/UZ-SLAMLab/ORB_SLAM3)

###3.视觉惯性SLAM

VINS-Mono

[[Code]](https://github.com/HKUST-Aerial-Robotics/VINS-Mono)

VINS-Fusion

[[Code]](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion)

### 4.激光SLAM | Lidar SLAM

LOAM

[[Code]](https://github.com/laboshinl/loam_velodyne)

Lego-LOAM

[[Code]](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM)

A-LOAM

[[Code]](https://github.com/HKUST-Aerial-Robotics/A-LOAM)

M-LOAM（多激光雷达）

[[Code]](https://github.com/gogojjh/M-LOAM)

LIO-SAM（激光惯性）

[[Code]](https://github.com/TixiaoShan/LIO-SAM)

LVI-SAM（激光惯性视觉）

[[Code]](https://github.com/TixiaoShan/LVI-SAM)

FAST-LIO（激光惯性）

[[Code]](https://github.com/hku-mars/FAST_LIO)

FAST-LIO2（激光惯性）

[[Code]](https://github.com/hku-mars/ikd-Tree)

R2LIVE（激光视觉惯性）

[[Code]](https://github.com/hku-mars/r2live)

R3LIVE（激光视觉惯性）

[[Code]](https://github.com/hku-mars/r3live)

R3LIVE++（激光视觉惯性）

[[Code]](https://github.com/hku-mars/r3live)

