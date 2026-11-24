# Awesome-Real-Time-Kinematics-High-Precision-GPS
# Awesome-Real-Time-Kinematics-High-Precision-GPS

# Top Real-Time Kinematics & High-Precision GPS Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Centimeter-Level RTK/PPK Positioning, NTRIP Base Stations, GNSS Processing & Autonomous Navigation*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Real-Time Kinematics & High-Precision GPS**. These tools enable centimeter-level GNSS positioning, NTRIP correction casting, Post-Processed Kinematics (PPK), Precise Point Positioning (PPP), and sensor-fused navigation for surveying, drones, robotics, and precision agriculture.

**Examples** include Emlid Reach Cloud, Trimble Catalyst, Bad Elf Cloud, Leica Zeno Connect, Septentrio Cloud, Point One Navigation, Swift Navigation, Bad Elf Flex, EOS Positioning, Tersus GNSS, and `rtk-ai/rtk` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted NTRIP casters, RTKLIB positioning engines, open GNSS receivers, and high-precision ROS 2 navigation — ideal for surveyors, UAV engineers, robotics developers, and geodesists.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Emlid Reach Cloud & Caster](https://emlid.com)**  
  Cloud NTRIP correction caster and ReachView 3 survey management platform for centimeter-accurate Emlid GNSS receivers.

- **[Trimble Catalyst & VRS Now](https://trimble.com)**  
  Subscription-based software GNSS positioning service delivering on-demand centimeter accuracy via cloud correction networks.

- **[Bad Elf Cloud & Flex](https://bad-elf.com)**  
  Cloud-connected GNSS management, Flex token provisioning, and GIS field data collection platform for mobile mapping workflows.

- **[Leica Zeno Connect & HxGN SmartNet](https://leica-geosystems.com)**  
  Commercial GNSS middleware and global RTK correction network providing sub-centimeter positioning across mobile GIS applications.

- **[Septentrio Cloud & Agnostic Corrections](https://septentrio.com)**  
  Enterprise multi-frequency GNSS management and cloud correction ecosystem engineered for interference-resilient autonomous positioning.

- **[Point One Navigation (Polaris RTK)](https://pointonenav.com)**  
  High-density continental RTK correction network and sensor-fusion API built for autonomous vehicles, robotics, and precision mapping.

- **[Swift Navigation (Skylark)](https://swiftnav.com)**  
  Cloud-based PPP-RTK precise positioning service delivering lane-level and centimeter-level accuracy for automotive and IoT fleets.

- **[EOS Positioning Systems (Arrow Series)](https://eos-gnss.com)**  
  Commercial high-accuracy GNSS receiver ecosystem integrating seamlessly with cloud RTK networks and ArcGIS field workflows.

- **[Tersus GNSS (Oscar & Caster)](https://tersus-gnss.com)**  
  Commercial RTK surveying hardware and cloud NTRIP correction infrastructure for land surveying, construction, and UAV mapping.


## Open-Source GitHub Projects

- **[rtk-ai/rtk](https://github.com/rtk-ai/rtk)**  
  High-speed open-source Rust CLI proxy and token-compression engine that optimizes terminal output and telemetry pipelines for AI-assisted engineering workflows.

- **[RTKLIB](https://github.com)**  
  The industry-standard open-source program package for standard and precise GNSS positioning, supporting RTK, PPK, PPP, and RTCM 3.x streams.

- **[RTKLIB Explorer (rtklibexplorer / demo5)](https://github.com)**  
  Actively maintained open-source fork of RTKLIB optimized for low-cost multi-constellation receivers (u-blox ZED-F9P, Unicore UM980) with faster ambiguity resolution.

- **[SNIP / BKG Ntrip Client (BNC)](https://bund.de)**  
  Open-source multi-stream NTRIP client and real-time GNSS data monitor developed by Germany's Federal Agency for Cartography and Geodesy (BKG).

- **[rtkbase](https://github.com)**  
  Open-source turn-key software stack for turning a Raspberry Pi and GNSS receiver into a permanent, web-managed RTK base station and NTRIP caster.

- **[CentipedeRTK](https://github.com)**  
  Collaborative open-source network of community-operated RTK base stations providing free, open-access centimeter-level NTRIP corrections.

- **[NTRIP Caster (ntripcaster / YAGA)](https://github.com)**  
  Lightweight open-source NTRIP (Networked Transport of RTCM via Internet Protocol) server for streaming real-time RTCM corrections from base to rover.

- **[Pocket SDR](https://github.com)**  
  Open-source GNSS Software-Defined Radio (SDR) receiver and signal processing toolkit supporting GPS, GLONASS, Galileo, BeiDou, QZSS, and NavIC.

- **[GNSS-SDR](https://github.com)**  
  Open-source global navigation satellite system software-defined receiver built on GNU Radio for custom baseband signal research.

- **[GEODE / gLAB (GNSS-Lab)](https://upc.edu)**  
  Open-source interactive educational and research software suite for processing and analyzing raw RINEX observations and PPP/SPP models.

- **[Rokubun / Jason GNSS](https://github.com)**  
  Open-source Python tools and RINEX utilities for GNSS observation parsing, PPK trajectory processing, and PNT research.

- **[ros2_ublox / ublox_dgnss](https://github.com)**  
  Modern open-source ROS 2 driver for u-blox F9P/F9R receivers supporting RTCM3 correction injection, HPPOSECEF/HPPOSLLH messages, and dead reckoning.

- **[GTSAM](https://github.com)**  
  Open-source C++ factor-graph library widely used to fuse raw RTK-GNSS measurements with IMU, LiDAR, and visual odometry for centimeter-accurate SLAM.

- **[AgOpenGPS](https://github.com)**  
  Leading open-source precision agriculture guidance, auto-steer, and section-control software powered by dual-antenna RTK GPS.

- **[PX4 Autopilot (RTK GPS Stack)](https://github.com)**  
  Open-source flight control software with native RTCM correction forwarding and dual-antenna RTK heading for autonomous drones.

- **[ArduPilot (GNSS / RTK / Moving Baseline)](https://github.com)**  
  Open-source unmanned vehicle autopilot supporting multi-band RTK receivers, NTRIP telemetry injection, and GPS-denied/GNSS fusion.

- **[pygnssutils & pyubx2](https://github.com)**  
  Pure-Python open-source libraries for parsing and generating UBX, NMEA 0183, and RTCM3 binary protocols from high-precision GNSS hardware.

### Additional Strong Open-Source Options

- **[Ginan (Geoscience Australia)](https://github.com)** for open-source Precise Point Positioning (PPP) analysis center software and real-time correction generation.
- **[PRIDE PPP-AR](https://github.com)** for open-source multi-GNSS Precise Point Positioning with Ambiguity Resolution.
- **[Foxglove Studio](https://github.com)** for visualizing live RTK fix status, covariance ellipses, and satellite skyplots in robotics workflows.
- **[Onocoy](https://onocoy.com)** and **[GEODNET](https://geodnet.com)** community-compatible open-source base station configurations for decentralized GNSS reference networks.
- Many community **ESP32 / Arduino RTCM parsers**, **LoRa radio telemetry bridges**, and **RINEX v3/v4 conversion utilities (`convbin` / `gfzrnx`)** for field surveying.

**Frameworks for building custom systems**: Combine **RTKLIB (`demo5`)**, **rtkbase**, **pyubx2 / pyrtcm**, and **GTSAM** with **ROS 2 (`ublox_dgnss`)** or **PX4 / ArduPilot** for autonomous, centimeter-accurate positioning systems.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- High-precision surveying and autonomous vehicle navigation require proper datum transformations (e.g., WGS84/ITRF to local geodetic datums), antenna phase center calibrations (ANTEX), and multipath mitigation.
- Radio telemetry links used for local RTK base-to-rover corrections (UHF/LoRa) must comply with regional spectrum regulations (e.g., WPC in India, FCC, ETSI).

---

**Made for geodesists, land surveyors, drone engineers, robotics builders, and precision agriculture innovators.**  
Let's make centimeter-level positioning more accessible, accurate, and open.
