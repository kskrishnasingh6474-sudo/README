# SOLAR-XR — Project Details

## Overview

SOLAR-XR is an interactive 3D space explorer concept in which hand gestures act as controls for exploring a 3D universe.

The project explores how real-time computer vision can support natural human-computer interaction without depending entirely on a keyboard or mouse.

## Interaction pipeline

1. Capture webcam input.
2. Use MediaPipe Hand Landmarker to detect hand landmarks.
3. Interpret landmark positions, distances, and ratios with custom rule-based logic.
4. Map recognized gestures to actions in the 3D environment.
5. Update the visual scene in real time.

## Gesture set described

- Open palm
- Fist
- Pinch
- Pointing
- Peace sign

## 3D experience described

- Particle-based planetary models
- Orbital systems
- Sun visualization
- Earth's internal layers
- Milky Way visualization
- Object selection
- Rotation and zoom
- Exploded views

## Technology stack

| Area | Technology |
|---|---|
| Hand tracking | MediaPipe Hand Landmarker |
| Gesture recognition | Custom rule-based logic |
| 3D rendering | Three.js |
| Browser graphics | WebGL / WebGPU |
| Input | Webcam |

## Demo

https://lnkd.in/dnU8eeky

## Scope and status

This is a curiosity-driven engineering experiment, not a production AI product.

**Important repository status:** This document records the implementation as described by the project author. The original source-code folder has not yet been identified, so the application code, dependency manifest, and runnable setup instructions are not included in this repository yet.

Do not treat the feature list as independently verified source-code documentation until the original project files are added and checked.


## Source attribution

Copied with permission from https://github.com/RAO10311/SOLAR-XR (author: RAO10311).
