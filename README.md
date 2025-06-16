Overview:

This project demonstrates multi-agent formation control using the PyMAVLink library to interface with MAVLink-compatible drones (e.g., PX4, ArduPilot). The goal is to control a swarm of drones to achieve and maintain a desired geometric formation (e.g., line, V-shape, square) through coordinated flight commands, using low-level MAVLink messaging.

Objectives:

Establish MAVLink communication with multiple drones via UDP.

Implement position-based and/or velocity-based control strategies to maintain formations.

Use relative or global positioning (e.g., GPS or VICON/optitrack).

Execute coordinated movements like takeoff, translation, rotation, and landing.

Key Features:

1. MAVLink message handling using pymavlink

2. Multi-drone UDP connection setup

3. Command-level control (arming, takeoff, land, setpoints)

4. Local NED / Global positioning commands

5. Formation logic (leader-follower, consensus-based, etc.)

6. Real-time telemetry monitoring

7. Individual drone control (yaw, speed, direction) through separate scripts
