# surena-humanoid-online-navigation
Real-time navigation and mapping framework for the SURENA humanoid robot using RTAB-Map and ROS.
*Case Study Using RTAB-Map on SURENA V*

This repository contains the implementation and simulation results of our work presented at **The 33rd Annual International Conference of the Iranian Society of Mechanical Engineers (ISME 2025)**.

**Paper title**: Real-Time Navigation and Mapping for Humanoid Robots: A Case Study Using RTAB-Map on SURENA V  
**Authors**: Sara Rahmati Kookandeh, Aghil Yousefi-Koma

## 📝 Abstract
We present a robust navigation framework for humanoid robots integrating RTAB-Map-based SLAM with advanced path-planning techniques. Using the SURENA V robot simulated in ROS + Choreonoid environments, our system enables autonomous locomotion in complex, dynamic settings.

## 📂 Repository Contents
- `/src`: Code for SLAM, path planning, and motion control.
- `/config`: Calibration data and robot models.
- `/simulation_results`: Output maps, screenshots, and videos from simulations.
- `/paper`: Our ISME2025 conference paper and presentation.

## 🚀 Simulation Setup
1. **Requirements**:
   - ROS Noetic / Humble
   - Choreonoid Simulator
   - RTAB-Map ROS Package
2. **Run Simulation**:
   ```bash
   roslaunch launch/main_navigation.launch
