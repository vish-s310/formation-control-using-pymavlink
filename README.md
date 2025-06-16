Overview

This project demonstrates multi-agent formation control using the PyMAVLink library to interface with MAVLink-compatible drones (e.g., PX4, ArduPilot). The goal is to control a swarm of drones to achieve and maintain a desired geometric formation (e.g., line, V-shape, square) through coordinated flight commands, using low-level MAVLink messaging.

Objectives

Establish MAVLink communication with multiple drones via UDP.

Implement position-based and/or velocity-based control strategies to maintain formations.

Use relative or global positioning (e.g., GPS or VICON/optitrack).

Execute coordinated movements like takeoff, translation, rotation, and landing.

