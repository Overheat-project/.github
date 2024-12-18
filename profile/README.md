# Welcome to the **Overheat Project** 🔥

## Overview

#### TL;DR: Embedded Systems Innovation 🚀 (not really)

The Overheat Project is pushing the boundaries of real-time data collection and visualization on edge devices. We’re combining cutting-edge tech to bring you dynamic, hands-on embedded systems applications, driven by:

- **Raspberry Pi 5** with monocylar camera (because we're out of budget) and `ORB-SLAM3` for precise 3D-map modelling
- **Mobile App** for command control, data visualization, and connection insights via `Bluetooth` (which will be a pain in the ass to debug)
- **Real-Time Visualization** of RSSI, network speeds, and spatial data (not sure, you haven't heard anything)

Join us as we explore the next level of connectivity and data processing on compact, powerful hardware of Cortex-A76 CPU with 8GB of LPDDR4X SDRAM on board.

Stay tuned for updates, and welcome to the journey!

## Our Team

- **Dvorkin Boris Alexandrovich** a.k.a. *worthant*: Lead (DevOps, UI/UX, Software)
- **Bardin Petr Alekseevich**: Embedded, Software, Computer vision
- **Kadilov Mikhail Vladimirovich**: Modelling, testing, UI/UX

## MVP Plan (Proof of Concept)

- [ ] 1. Collect data of a small room/home from camera connected to rpi5
- [ ] 2. Run ORB_SLAM3 on created dataset -> get trajectories
- [ ] 3. Build 2D/3D map, based on p.2 (python, matplotlib)
- [ ] 4. Transfer trajectories on Android Phone

## Project Plan (Only when MVP works)

- [ ] 1. 2 ways: either run ORB_CLAM3 on realtime data from camera, or automate data collection and running orb_slam3 on it
- [ ] 2. Automate transferring generated trajectories from rpi5 to android phone via Bluetooth (python)
- [ ] 3. Automate 3D map generation (java, matplotlib) + backend API (python)
- [ ] 4. Test everything thoroughly
