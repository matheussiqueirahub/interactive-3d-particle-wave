# Interactive 3D Particle Wave

An interactive 3D particle visualization experiment that responds to hand gestures in real-time. Built with **Three.js** and **MediaPipe Hand Tracking**.

## Overview

This project renders a dynamic field of 28,000 particles that move in a wave pattern. By using your computer's webcam, you can control the visualization using hand gestures. The system detects your hand position and specific gestures to alter the simulation's speed, color, and particle behavior.

## Features

- **Real-time 3D Rendering**: High-performance particle system using Three.js.
- **Hand Gesture Control**: powered by MediaPipe.
- **Interactive Modes**:
  - **Pointer**: Move your hand to rotate the galaxy and disrupt particles.
  - **Fist**: "Furious Mode" - Increases speed, turns red, and causes particle explosions.
  - **Victory**: "Macro Zoom" - Zooms in particles and slows time.
  - **Hang Loose**: "Freeze Time" - Pauses the wave animation.
  - **Open Hand**: "Zen Mode" - Calming blue colors and slow, smooth motion.

## Technologies Used

- **HTML5/CSS3**
- **JavaScript (ES6 Modules)**
- **Three.js** (3D Rendering Engine)
- **MediaPipe Hands** (Computer Vision)

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/matheussiqueirahub/interactive-3d-particle-wave.git
   ```
2. Open the project folder.
3. Open `index.html` in your web browser.
   - *Note*: For webcam access to work correctly, you may need to serve the file via a local server (like VS Code Live Server) or ensure your browser allows camera access for local files.

## Credits

Created by **Matheus Siqueira**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
