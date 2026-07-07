# 🏎️ 3D Vector Racing & Spatial AI Pathfinding Engine

> 🚀 **Live Interactive Application Environment:** [Launch the 3D Racing Simulation Engine](https://elishevak-00.github.io/3d-racing-simulator/)

## Project Overview
This repository contains a responsive, client-side, browser-native 3D racing simulation engine built using **Three.js (WebGL)** and scratch-programmed physics vector layers. It showcases explicit vector translations, constraint boundaries checking algorithms, and autonomous spatial waypoint targeting mechanics.

---

## 📐 Structural Engineering Systems Architecture

### 1. Vector Physics Engine Rig
Bypasses bulky third-party black-box rigid body physics engines to program absolute translation dynamics from first principles:
- **Heading Resolution:** Uses angular integration vectors to compute independent directional matrices based on instantaneous velocities.
- **Dynamic Forces:** Models real-time forward acceleration parameters, discrete kinetic braking friction vectors, and decaying aerodynamic atmospheric drag.

### 2. Geometry Containment Boundaries Checking
Implements real-time spatial constraints verification processing:
- Translates the coordinate footprint of the track layout into a collection of 2D line vectors.
- Calculates an continuous vector dot-product calculation loops to determine the vehicle's absolute distance relative to the closest point along the center-line spline.
- Dumps directional velocity metrics and applies vector reflections if a coordinate boundaries threshold breach is triggered.

### 3. Waypoint Navigation AI Pathfinding
Autonomous vehicles execute continuous predictive spatial guidance logic loops:
- **Target Tracking:** Operates via target node tracking metrics across a sequence of vector arrays.
- **Error Minimization Calculations:** Employs trigonometric calculation parameters (`Math.atan2`) to determine trajectory variances between the vehicle's current alignment and the next waypoint.
- **Speed Optimization Adaptations:** Dynamically dampens input power parameters if heading errors cross predefined curvature thresholds, ensuring smooth cornering stabilization.
