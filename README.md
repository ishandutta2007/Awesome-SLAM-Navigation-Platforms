# Awesome-SLAM-Navigation-Platforms

# Awesome-SLAM-Navigation-Platforms

# Top SLAM Navigation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Simultaneous Localization and Mapping, Autonomous Navigation & Sensor Fusion*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **SLAM Navigation Platforms**. These tools enable robots and autonomous vehicles to build maps of unknown environments while simultaneously tracking their position within them — the foundational capability for mobile robotics, autonomous driving, and spatial AI.

**Examples** include Nav2 (ROS 2), SLAMcore, Kudan, Kaarta, Cartographer, ORB-SLAM3, RTAB-Map, OpenVSLAM, Artisense, and Inertial Sense (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom sensor fusion, and transparent mapping — ideal for robotics researchers, developers building autonomous systems, and teams avoiding per-robot licensing fees.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Nav2 (ROS 2)](https://docs.nav2.org/)**  
  The production-grade successor to the ROS Navigation Stack, trusted by 300+ companies worldwide. Provides perception, planning, control, localization, and behavior trees for autonomous navigation. While core is open-source, professional support and enterprise deployment services are available.

- **[SLAMcore](https://www.slamcore.com/)**  
  Visual SLAM software for industrial vehicles and drones. Uses stereo cameras with onboard compute to provide real-time location without GPS, beacons, or floor markers. Deployed in 30+ factories and warehouses across Europe and North America, with $40M total funding. Supports Intel RealSense, Luxonis OAK-D, and NVIDIA Jetson platforms.

- **[Kudan](https://www.kudan.io/)**  
  Comprehensive robot navigation stack for commercial deployment of mobile robots and autonomous vehicles. Features robust localization, path planning, obstacle avoidance, semantic segmentation, multi-sensor fusion (camera/LiDAR/IMU/GNSS), and simulation validation. Optimized for challenging environments including dynamic warehouses, mixed indoor-outdoor, and feature-sparse spaces. Supports ROS 2 Jazzy on x86 and ARM. Acquired Artisense in 2023 to strengthen R&D capabilities [citation:8].

- **[Kaarta](https://www.kaarta.com/)**  
  Mobile 3D mapping and real-time position estimation systems. Stencil 2 and Contour handheld scanners process while capturing, generating registered point clouds on the fly. Won Microsoft Indoor Localization Challenge in 2016 and 2017. Software is hardware-agnostic, allowing integration with latest LiDAR and sensors.

- **[Artisense](https://www.artisense.ai/)**  
  Visual SLAM technology for precise positioning in autonomous driving, robotics, and fleet management. Combines visual data with IMU and GNSS for centimeter-accurate localization in challenging environments including tunnels and indoors. Founded 2018, Munich-based, modular hardware and software architecture. Acquired by Kudan, with strong academic ties to TU Munich and Professor Daniel Cremers [citation:8].

- **[Inertial Sense](https://inertialsense.com/)**  
  Autonomy-as-a-service for outdoor robotics vehicles. IMX-5 tactical-grade IMU and LUNA autonomous navigation software platform launched 2021, focused on enabling legacy manufacturers of outdoor commercial vehicles.

- **[Cartographer (Google)](https://github.com/cartographer-project/cartographer)**  
  While open-source, Google provides consulting and support for commercial deployments. Real-time SLAM in 2D and 3D across multiple platforms and sensor configurations [citation:2].

- **[ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)**  
  Academic open-source library with commercial licensing available for proprietary applications. The most complete and accurate visual, visual-inertial, and multi-map SLAM library to date [citation:10].

- **[RTAB-Map](https://github.com/introlab/rtabmap)**  
  Open-source library with commercial support options for enterprise deployments. Real-Time Appearance-Based Mapping library for large-scale and long-term online operation [citation:2][citation:10].

- **[OpenVSLAM](https://github.com/xdspacelab/openvslam)**  
  Open-source framework with 2-clause BSD license, designed for research and development with commercial-friendly terms [citation:2].

## Open-Source GitHub Projects

- **[Nav2](https://github.com/ros-navigation/navigation2)**  
  The leading open-source navigation framework for ROS 2, trusted by 300+ companies worldwide. Provides behavior trees for orchestrating modular servers for planning, control, localization, and behaviors. Supports nearly any robot kinematics, sensor configuration, indoor or outdoor operation. Available across multiple ROS 2 distributions. Apache 2.0 licensed.

- **[Cartographer](https://github.com/cartographer-project/cartographer)**  
  Google's real-time SLAM system for 2D and 3D across multiple platforms and sensor configurations [citation:2]. Uses loop closure for drift-free mapping. Apache 2.0 licensed, maintained by the Cartographer Authors. Foundation for many commercial robot navigation stacks.

- **[ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)**  
  The most complete and accurate visual, visual-inertial, and multi-map SLAM library to date [citation:10]. Supports monocular, stereo, and RGB-D cameras with pin-hole and fisheye lens models. Features Atlas multi-map system for incremental multi-session SLAM, improved-recall place recognition, and MAP estimation during IMU initialization. GPLv3 licensed.

- **[RTAB-Map](https://github.com/introlab/rtabmap)**  
  Real-Time Appearance-Based Mapping library for large-scale and long-term online operation, distributed as open-source since 2013 [citation:2]. Started as appearance-based loop closure detection with memory management, grew to implement SLAM on various robot platforms. Supports LiDAR and visual SLAM.

- **[OpenVSLAM](https://github.com/xdspacelab/openvslam)**  
  Versatile visual SLAM framework designed to be called as a library from third-party programs [citation:2]. Won first place in ACM Multimedia 2019 Open Source Software Competition. Supports perspective, fisheye, and equirectangular cameras — first open-source visual SLAM framework to accept equirectangular imagery. Features map I/O and localization based on prebuilt maps. 2-clause BSD licensed.

- **[Kimera-VIO](https://github.com/MIT-SPARK/Kimera-VIO)**  
  Visual Inertial Odometry with SLAM capabilities and 3D Mesh generation from MIT-SPARK [citation:10]. Part of the Kimera ecosystem for visual-inertial navigation research.

- **[OpenVINS](https://github.com/rpng/open_vins)**  
  Open-source platform for visual-inertial navigation research [citation:10]. Filter-based VIO with extensive estimator options.

- **[LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM)**  
  Lightweight and ground-optimized LiDAR odometry and mapping on variable terrain [citation:2][citation:10]. Widely used for outdoor SLAM applications. Introduced ground segmentation to improve performance in ground-dominant environments [citation:1][citation:14].

- **[LIO-SAM](https://github.com/TixiaoShan/LIO-SAM)**  
  Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping [citation:2][citation:10]. Implements tight coupling of LiDAR and IMU measurements into factor graph optimization for improved pose estimation accuracy [citation:14].

- **[KISS-ICP](https://github.com/PRBonn/kiss-icp)**  
  Keep it Simple, Stupid - ICP algorithm for LiDAR odometry. Significant advancement in 3D SLAM parametrization, demonstrating versatility of adaptive parametrization [citation:14].

- **[GLIM](https://github.com/koide3/glim)**  
  GPU-accelerated LiDAR SLAM built upon HDL Graph SLAM framework for improving performance in large-scale environments [citation:14]. Excels with Livox Mid-360 sensor due to its local optimization module [citation:1].

- **[MOLA-LO](https://github.com/MOLAorg/mola)**  
  Modular system for localization and mapping [citation:14]. MOLA (Modular Optimization framework for LOcalization and mApping) provides a complete SLAM system with ROS 2 integration [citation:20]. The 2D mapper uses GTSAM for factor graph optimization and supports session resumption for multi-session mapping.

- **[DM-VIO](https://github.com/lukasvst/dm-vio)**  
  Delayed Marginalization Visual-Inertial Odometry. Direct method VIO with loop closure capabilities [citation:10].

- **[Basalt](https://gitlab.com/VladyslavUsenko/basalt)**  
  Visual-inertial mapping framework with optimization-based VIO and SLAM capabilities.

- **[OV²SLAM](https://github.com/ov2slam/ov2slam)**  
  Fully Online and Versatile Visual SLAM for Real-Time Applications.

- **[GTSAM](https://github.com/borglab/gtsam)**  
  Library of C++ classes implementing smoothing and mapping (SAM) in robotics and vision using factor graphs and Bayes networks [citation:10]. Foundation for many SLAM back-end optimizations, including MOLA's 2D mapper [citation:20].

- **[slam_toolbox](https://github.com/SteveMacenski/slam_toolbox)**  
  Currently supported ROS 2 SLAM library [citation:18]. Provides 2D SLAM with lifelong mapping capabilities, pose-graph serialization for multi-session mapping, and mature underlying Karto scan matcher [citation:15][citation:18]. Used in ROS 2 navigation stacks with Nav2 [citation:15].

- **[DROID-SLAM in the Wild](https://github.com/)**  
  Adapts DROID-SLAM with differentiable Uncertainty-aware Bundle Adjustment (UBA) that explicitly models per-pixel uncertainty to handle dynamic objects in cluttered real-world scenes [citation:11].

- **[ViSTA-SLAM](https://github.com/zhangganlin/vista-slam)**  
  Real-time monocular visual SLAM system that operates without requiring camera intrinsics, making it broadly applicable across diverse camera setups [citation:3][citation:19]. Uses lightweight symmetric two-view association model as frontend (only 35% the size of comparable methods) [citation:3].

- **[Wheel-GINS](https://github.com/i2Nav-WHU/Wheel-GINS)**  
  GNSS/INS integrated navigation system using a wheel-mounted IMU [citation:13]. Fuses GNSS position measurement with Wheel-IMU via extended Kalman filter to limit long-term error drift and provide continuous state estimation during GNSS outages.

### Additional Strong Open-Source Options

- **[Kimera](https://github.com/MIT-SPARK/Kimera)** — Index repo for Kimera code covering VIO, semantic mapping, and mesh generation [citation:10].
- **[Voxblox](https://github.com/ethz-asl/voxblox)** — Library for flexible voxel-based mapping, focusing on truncated and Euclidean signed distance fields.
- **[Awesome-SLAM-Datasets](https://github.com/youngguncho/awesome-slam-datasets)** — Curated list of datasets for SLAM research [citation:10].
- **[evo](https://github.com/MichaelGrupp/evo)** — Python package for evaluation of odometry and SLAM trajectories [citation:10].
- **[SLAM Resources](https://github.com/)** — Curated lists of vision-based SLAM, visual odometry, open source projects, blogs, and papers [citation:2].
- **[OpenVINS](https://github.com/rpng/open_vins)** — Open-source platform for visual-inertial navigation research [citation:10].
- **[FAST-LIVO2](https://github.com/hku-mars/FAST-LIVO2)** — Fast, Direct LiDAR-Inertial-Visual Odometry [citation:12].
- **[LIMO-Velo](https://github.com/Huguet57/LIMO-Velo)** — Real-time, direct and tightly-coupled LiDAR-Inertial SLAM for high velocities with spinning LiDARs [citation:12].

**Frameworks for building custom systems**: Combine **Nav2** for navigation stack orchestration, **Cartographer** or **ORB-SLAM3** for localization and mapping, **RTAB-Map** for long-term appearance-based loop closure, **Kimera-VIO** for visual-inertial odometry, **slam_toolbox** for 2D ROS 2 mapping with lifelong capabilities [citation:18], and **GTSAM** for factor graph optimization to build a complete self-hosted SLAM navigation stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SLAM navigation platforms must comply with safety regulations, sensor calibration requirements, and applicable robotics standards. Incorrect localization can cause safety hazards in autonomous systems.
- Self-hosted open-source solutions require proper sensor calibration, compute infrastructure, and validation against ground truth before operational deployment.

---

**Made for robotics engineers, autonomous systems developers, SLAM researchers, and teams building navigation platforms.**  
Let's make SLAM navigation more open, accurate, and robot-friendly.
