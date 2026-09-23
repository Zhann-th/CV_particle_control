# Nex

Hey there. Nex is an experiment with real-time 3D hand gesture recognition in the browser. The idea was to see if I could build a spatial control interface that feels fluid and doesn't rely on a heavy backend. 

It uses MediaPipe to track hand landmarks and translates those movements into a particle physics engine running on WebGL. Everything runs locally in the browser at 60 FPS, so there's zero network latency.

## How it works
- **Tracking:** Uses MediaPipe and TensorFlow.js to read hand coordinates from your webcam.
- **Visuals:** A custom WebGL canvas that reacts to your hand's position in real time.
- **UI:** A simple dark-themed interface built with vanilla JS and CSS.

## Running the project
You don't need a server to run this. Just clone the repo, open `index.html` in Chrome, and allow camera access. 
