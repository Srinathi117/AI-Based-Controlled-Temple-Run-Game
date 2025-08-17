# AI-Based-Controlled-Temple-Run-Game
## Overview

This project aims to build a real-time, gesture-controlled game inspired by Temple Run, where the player uses body movements detected via webcam to control the character. Using pose estimation models (e.g., MediaPipe or TensorFlow Lite) to track key body points, the game interprets gestures like jumping, ducking and moving left or right. These detected gestures are sent to the game engine (built using a local HTTP server or MQTT messaging) to simulate player actions in real-time. The goal is to create an interactive, AI-powered gaming experience that blends computer vision and game development.

## Flow chart

Webcam ➜ Pre-trained pose model ➜ Real-time keypoints ➜ Custom logic to recognize gestures ➜ Control the game

## Requirements

- Python 3.x
- TensorFlow / TensorFlow Lite
- OpenCV
- Flask
- Pygame
- Streamlit
- Libraries: pandas,numpy, seaborn, scikit-learn

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Srinathi117/AI-Based-Controlled-Temple-Run-Game.git
