# Nex: Spatial Control Platform

**Nex** is a real-time 3D hand gesture recognition and spatial control engine running entirely in the browser. It uses neural landmark tracking via MediaPipe to translate physical hand movements into fluid 3D interactions and particle physics simulations using WebGL.

## Features
- **Real-Time 3D Gesture Tracking:** High-precision neural detection using TensorFlow.js and MediaPipe.
- **WebGL Particle Engine:** 60 FPS fluid canvas simulations reacting to hand coordinates.
- **Zero-Latency Processing:** Optimized for minimal latency without requiring external backend processing.
- **Immersive Dark IDE Interface:** Modern, glassmorphism-styled UI with responsive visualizers.

## Tech Stack
- **AI/ML:** TensorFlow.js, MediaPipe (Hands)
- **Graphics:** WebGL, Canvas API
- **Frontend:** Vanilla JS, CSS3 (Glassmorphism), HTML5

## Running Locally
Since it runs entirely in the client-side browser:
1. Clone the repository.
2. Open `index.html` in your modern web browser (Chrome recommended for optimal WebGL performance).
3. Grant camera permissions when prompted to enable gesture tracking.
