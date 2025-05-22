# Hydra ROV Control Software

This is a prototype GUI control software for the Hydra ROV (Remotely Operated Vehicle), developed using Python and PyQt6. It includes real-time video feed display panels, joystick-based movement controls, robotic arm manipulation, and grip functions. It communicates with a Raspberry Pi over a socket connection.

## Features

- 📷 Live video feed integration from the Raspberry Pi camera.
- 🎮 Joystick support using Pygame for real-time control.
- ⚙️ Robotic arm control using GUI buttons and joystick.
- 🚀 Thruster directional controls.
- ✊ Grip open/close functionality.
- 🔌 TCP socket connection to Raspberry Pi for sending control commands.

## Interface Overview

- **Left Panel**: Displays raw video feed from the Raspberry Pi.
- **Right Panel**: Placeholder for processed image.
- **Center Panel**: Control buttons for robotic arm and thrusters.
- **Bottom Center**: Grip open/close toggle.

## Dependencies

Install the following Python packages before running:

pip install pyqt6 pygame opencv-python
