# 🛩️ Mission Animation for UAV

This repository includes a set of Python scripts developed to simulate and animate UAV (Unmanned Aerial Vehicle) missions. The main goal is to visualize and test autonomous drone behavior in virtual environments such as **Gazebo** and **Mission Planner**.

## 🎯 About the Project

The project was built during my time with the **Artun UAV Team** for the purpose of simulating task animations and testing mission logic before physical deployment.

Each script is a versioned attempt to improve path logic, animation flow, and real-time testing support between two fixed poles.

## Objectives

- Define fixed poles as mission coordinates (lat/lon)
- Animate autonomous UAV movement between poles
- Test logic using **Gazebo**, **Mission Planner**, and **SITL**
- Implement and visualize circular and linear missions

## Tech Stack & Libraries

- **Python 3**
- DroneKit
- pymavlink
- dronekit-sitl
- Gazebo
- Mission Planner
- argparse, math, time, sys

