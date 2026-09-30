<div align="center">

# 🚁 Drone Flight Training Simulator

### A Physics-Based 3D Quadcopter Training Simulator

**Learn to fly. Master precision. Complete the course.**

Built for the **RoboDrone Challenge** using Python and the Ursina game engine.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![Engine](https://img.shields.io/badge/Engine-Ursina%20%2F%20Panda3D-orange)
![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?logo=windows&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Hackathon%20Project-blueviolet)

</div>

---

## 📌 Overview

**Drone Flight Training Simulator** is a physics-based 3D quadcopter simulator designed to provide a safe virtual environment for learning and practising drone flight.

The simulator combines a force-based flight model with a procedurally generated voxel environment, allowing users to practise:

- Throttle control
- Hovering
- Pitch, roll and yaw
- Precision flying
- Ring-course navigation
- Landing
- Timed missions
- Freestyle flight using ACRO mode

The project was developed for the **RoboDrone Challenge** using **Python** and the **Ursina** game engine, which uses Panda3D for rendering.

---

## 🎯 Project Objectives

The simulator was designed with the following objectives:

- Provide a safe environment for learning basic drone control
- Simulate essential quadcopter flight behaviour
- Allow users to practise precision flying
- Introduce different flight modes
- Provide structured training through numbered checkpoints
- Simulate landing and crash conditions
- Create an interactive 3D environment
- Provide performance-based scoring and timed missions

---

## ✨ Key Features

### 🚁 Flight & Control

| Feature | Description |
|---|---|
| 6-Axis Quadcopter | Supports throttle, pitch, roll and yaw control |
| ANGLE Mode | Self-levelling flight mode for controlled flying |
| ACRO Mode | Rate-based flight mode supporting freestyle manoeuvres |
| Altitude Assist | Helps maintain a stable altitude |
| Soft-Stick Input | Smoothly ramps keyboard input |
| Gamepad Support | Experimental controller support |
| Attitude Indicator | Displays drone pitch and roll |

---

### 🎮 Training & Gameplay

| Feature | Description |
|---|---|
| Numbered Ring Course | Fly through rings 1 to 8 in the correct order |
| Guide Path | Provides a visual route through the course |
| Ring Feedback | Audio and visual feedback when a ring is cleared |
| Wrong-Order Detection | Warns the player when a ring is skipped |
| Landing Pads | Provides designated landing areas |
| Timed Mission | Complete the course within the available time |
| Persistent Records | Stores best score and best mission time |
| Battery System | Battery drains according to throttle usage |
| Crash Detection | Detects hard landings and collisions |

---

### 🌍 3D Environment

The simulator uses a procedurally generated voxel environment.

Features include:

- Grass, dirt, stone and snow terrain
- Hills and varying terrain heights
- Trees
- Buildings
- Roads
- Clouds
- Day and night environment
- Stars and fog
- Multiple camera perspectives
- Minimap
- Alternative neon environment

The terrain is generated programmatically rather than being loaded from a pre-built map.

---

### 🔊 Procedural Audio

The simulator generates its sound effects programmatically.

The audio system includes:

- Drone motor sound
- Wind sound
- Ring completion sounds
- Mission completion fanfare
- Landing sound
- Crash sound
- Low-battery warnings
- Background music

No external audio files are required for the simulator's core sound system.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Core programming language |
| **Ursina Engine** | 3D game and simulation framework |
| **Panda3D** | Rendering engine used by Ursina |
| **PyInstaller** | Windows executable generation |
| **Procedural Generation** | Terrain and environment generation |
| **Physics Simulation** | Drone movement and collision behaviour |

---

# 🚀 Getting Started

## 📋 Requirements

To run the simulator from source, you need:

- Windows 10 or Windows 11
- Python 3.10 or newer
- A graphics system with OpenGL support
- Required Python packages listed in `requirements.txt`

The source project can also run on Linux/macOS according to the project documentation.

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/SREEDHAR-VIJAY/DRONE-SIMULATOR.git
