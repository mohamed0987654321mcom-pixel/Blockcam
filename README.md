# BlockCam

Stack pixel blocks in your real room through your phone camera, then smash through the floor and walls.

- Tap the screen, or pinch 👌 with your free hand in front of the camera, to place blocks.
- **⛏️ Dig** breaks through your floor: dirt, then stone with coal and gem ore, with bedrock at the bottom.
- **🔍 Walls** finds walls by itself. Point at the bottom of a wall with some floor in view: it spots the line where the wall meets the floor, shows it in blue, and locks it in after you hold still for a second (or tap to lock it straight away). Then dig through plaster, brick and stone.
- If your wall and floor look too alike for it to see, tap two spots along the bottom of the wall instead.
- **🤲 Palm menu**: turn your free hand palm-up in front of the camera and a row of buttons appears: 🧱 Build, ⛏️ Dig, 🔍 Walls and 🔄 next block. Pinch and hold, slide your hand left or right to move the highlight, and let go to pick.

## Play

Open **https://mohamed0987654321mcom-pixel.github.io/Blockcam/** on your phone, tap **Start**, and allow camera and motion access. The camera only works over `https://`.

Stand in one spot and turn around. The phone's motion sensor keeps everything steady while you turn, but blocks slide if you walk. In ⚙️:

- **Camera lens**: adjust it if blocks drift as you turn.
- **Phone height** and **Ceiling height**: match your room.
- **Clear walls**: use it if a wall drifts away from the real one, then mark it again.

Each launch starts with a fresh room, because the phone can't remember where your walls are between sessions.

## Built with

- [three.js](https://threejs.org) for the 3D blocks
- [MediaPipe Hand Landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) for pinch detection

Everything is in a single `index.html` with no build step.
