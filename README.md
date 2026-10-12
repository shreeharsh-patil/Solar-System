# SOLARIS — Interactive 3D Solar System

Explore the Solar System through an immersive, interactive 3D experience built with **Three.js**, HTML, CSS, and JavaScript.

SOLARIS brings the Sun, all eight planets, and selected moons to life with animated orbits, procedurally generated surface textures, atmospheric effects, and smooth cinematic camera transitions. Travel between celestial bodies, adjust the pace of the simulation, and discover facts about each world.

## Features

- **Explore the Solar System:** View the Sun and all eight planets in an interactive 3D scene.
- **Animated orbital motion:** Watch planets rotate and revolve, with adjustable simulation speed and pause/play controls.
- **Detailed visuals:** Procedural planetary textures, lighting, atmospheric glows, cloud layers, Saturn's rings, and a starfield.
- **More celestial objects:** Selected moons, an asteroid belt, and a Kuiper belt.
- **Cinematic navigation:** Click a planet or select it from the navigation dock to smoothly fly toward it.
- **Planet facts:** Read descriptions and key statistics in an information panel.
- **Flexible controls:** Show or hide orbit paths, labels, and belts; navigate with mouse, touch, or keyboard.
- **Responsive layout:** Controls adapt to smaller screens.

> **Note:** SOLARIS is an educational visualization, not a precision astronomical simulator. Object sizes, distances, and orbital motion are simplified for clarity and exploration.

## Technologies

- **HTML5** and **CSS3** for the interface
- **JavaScript (ES modules)** for simulation and interaction
- **Three.js** for WebGL-powered 3D rendering and camera controls
- **Procedural texture generation** for planetary surfaces

## Getting Started

The experience is contained in `index.html`, so there is no build process.

1. Clone or download this repository.
2. Run a simple local web server in the project directory, for example:

   ```bash
   python3 -m http.server 8000
   ```

3. Open `http://localhost:8000` in a modern WebGL-capable browser.

An internet connection is required to load Three.js from the CDN referenced in the page.

## Controls

| Action | Control |
| --- | --- |
| Rotate the view | Click and drag |
| Zoom | Mouse wheel or touch gesture |
| Focus on a planet | Click a celestial body or use the bottom dock |
| Browse celestial bodies | Left / Right arrow keys |
| Pause or resume | Spacebar or Pause/Play button |
| Return to overview | Escape or Overview in the dock |
| Adjust simulation speed | Time speed slider |
| Toggle overlays | Orbits, labels, and asteroid belt switches |

## About

**SOLARIS** is a browser-based journey through space that blends scientific facts with polished interactive visuals, making planetary exploration intuitive and engaging.
