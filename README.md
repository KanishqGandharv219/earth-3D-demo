# Majestic Earth 3D — Spectacular Edition

### 🌐 [Live Interactive Demo](https://KanishqGandharv219.github.io/earth-3D-demo/)

A stunning, photorealistic 3D Earth visualization built with Three.js. This project features high-fidelity textures, custom GLSL shaders, and realistic planetary physics.

## Features

- **Full Texture Pipeline**: Day & night cycles, normal mapping for terrain elevation, and specular mapping for reflective oceans.
- **Atmospheric Effects**: Custom shader-based atmospheric glow and a dedicated cloud layer with dynamic drift.
- **Realistic Physics**: Oblate spheroid shape (WGS84 flattening) and accurate axial tilt (23.44°).
- **Interactive Controls**: Full camera orbit, zoom, and real-time adjustment of sun position, atmosphere intensity, and rotation speed.
- **Star Field**: Procedurally generated twinkling star background.
- **Premium UI**: Glassmorphism HUD with FPS monitor and intuitive planetary controls.

## Tech Stack

- [Three.js](https://threejs.org/) (WebGL Framework)
- [lil-gui](https://georgealways.com/lil-gui/) (User Interface)
- GLSL (Custom Shaders)
- HTML5 / CSS3 (Vanilla)

## Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/KanishqGandharv219/earth-3D-demo.git
   ```
2. Open `index.html` using a local server (e.g., VS Code **Live Server** extension) to avoid CORS issues with textures.

### Live Demo
The project is hosted on GitHub Pages:
[View Live Demo](https://KanishqGandharv219.github.io/earth-3D-demo/)

## Controls
- **Left Click + Drag**: Rotate Earth
- **Right Click + Drag**: Pan Camera
- **Scroll**: Zoom In/Out
- **GUI (Top Right)**: Detailed control over all planetary and environmental parameters.

---
Created with ❤️ for spectacular visualizations.
