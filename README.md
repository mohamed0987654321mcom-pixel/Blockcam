# BlockCam

Build and dig on your real floor through your phone camera.

- Your camera shows your room, and pixel trees and blocks appear on the floor around you.
- Pinch 👌 with your free hand in front of the camera to build or dig, or just tap the screen.
- Dig through the floor to find dirt, stone, coal and gem ore, with bedrock at the bottom.

## Play

Open the GitHub Pages link on your phone, tap **Start**, and allow camera and motion access. The camera only works over `https://`.

Stand in one spot and turn around. The phone's motion sensor keeps the world steady while you turn, but blocks slide if you walk. If blocks drift as you turn, adjust **Camera lens** in ⚙️.

## Built with

- [three.js](https://threejs.org) for the 3D blocks
- [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) for pinch detection

Everything is in a single `index.html` with no build step.
