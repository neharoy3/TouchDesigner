# 🖌️ Handbrush

A real-time hand-tracking painting application built in TouchDesigner. This project utilizes MediaPipe for gesture recognition, allowing users to paint on screen using hand movements, pinch gestures to control brush size, and specific gestures to clear the canvas or switch brush textures.

## 📝 Project Overview

This is my first project in TouchDesigner, developed to explore the intersection of computer vision and interactive art.

**Key Features:**

- **Real-time Hand Tracking:** Uses MediaPipe to track index finger and thumb pinch-midpoints.
- **Gesture Control:**
  - **Pinch:** Adjust brush size dynamically.
  - **Thumbs Up:** Cycle through different brush textures (Video/Noise).
  - **Point Up:** Clear the canvas (Feedback reset).
- **Feedback Loops:** Creates a "painterly" trail effect using feedback displacement.

## 🔗 Sources

📌[Watercolor Hand Tracking Brush in TouchDesigner Tutorial](https://youtu.be/IATX3biLoZg) by Torin Blankensmith

📌Download [Clamp Math Component](https://www.patreon.com/posts/clamp-math-tox-123882886)

📌Download [MediaPipe Plugin for TouchDesigner](https://github.com/torinmb/mediapipe-touchdesigner)

## 📂 File Structure

```text
Handbrush/
├── assets/         # Project textures and background images
├── toxes/          # [MANUALLY ADD THESE FILES HERE]
│   ├── MediaPipe.tox
│   └── ClampMath.tox
├── handbrush.toe   # Main project file
└── README.md       # Project documentation
```
