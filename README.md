# 3D Geometry Lab v2026 - educational geometry visualization tool 2026

> **3D Geometry Lab is a browser-based geometry study tool that blends interactive 3D math visuals, WebGL rendering, and hand-tracked controls to let users investigate shapes and functions in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryan-hillrr9494/3d-geometry-lab-v2026?style=flat-square)](https://github.com/ryan-hillrr9494/3d-geometry-lab-v2026)

---

<p align="center">
  <a href="https://ryan-hillrr9494.github.io/3d-geometry-lab-v2026/">
    <img src="https://img.shields.io/badge/Download-3D%20Geometry%20Lab%20Latest-brightgreen?style=for-the-badge" alt="Download 3D Geometry Lab">
  </a>
</p>

> **[Direct Download - 3D Geometry Lab v2026](https://ryan-hillrr9494.github.io/3d-geometry-lab-v2026/)**

---

[Download Latest Build](https://ryan-hillrr9494.github.io/3d-geometry-lab-v2026/)

---

## Overview

3D Geometry Lab provides an interactive browser workspace for learning and presenting geometry. Using front-end 3D rendering, it displays solids, visual controls, and math-oriented views that make spatial relationships easier to examine from different perspectives.

It is intended for students, teachers, and independent learners who want a practical way to work through geometry and related functions. By combining 3D math visualization, camera-driven hand input, and problem-solving support, it supports exploration, demonstration, and practice in one place.

---

## Features

- Browser-based interactive 3D geometry lab for learning and exploration
- Eight geometric solids ready for inspection
- Mouse orbit controls for turning and examining shapes
- AI-assisted problem-solving panel for guided geometry tasks
- Gesture-based 3D shape interaction for hands-on control
- Camera hand tracking powered by MediaPipe
- 2D function plotting paired with 3D visualization
- Wireframe view and size sliders for finer shape adjustments

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/ryan-hillrr9494/3d-geometry-lab-v2026.git
2. Open the project folder:
   - `cd 3d-geometry-lab`
3. Serve the front-end through a web server or local preview environment.
4. Open the app in a browser and grant camera access if you want to use hand tracking.

If you plan to host it as a static site, upload the built output to your server or GitHub Pages target and then open the published URL.

---

## Usage

Begin by choosing a solid or graph view, then use orbit controls to look at the geometry from multiple angles. The sliders can be used to resize objects, wireframe mode helps expose structure, and the 2D plot area is available for function-based examples.

To use gesture input, enable camera access and complete the on-screen tracking steps so the interface can react to hand movement. The problem-solving panel works alongside the visuals to support step-by-step geometry practice or classroom demonstrations.

---

## Configuration

Configuration lives in the front-end project files. Depending on your setup, the relevant settings may be stored in the main HTML, JavaScript modules, or application constants.

Common values you may want to adjust include:

- Default solid selection
- Plot ranges for 2D graphs
- Camera and hand-tracking settings
- Rendering options for WebGL / Three.js
- UI behavior for sliders and wireframe mode

If you customize the app, remember to account for MediaPipe permissions and browser camera settings when testing gesture features.

---

## Requirements

- A modern web browser with WebGL support
- Access to a browser environment for the front-end
- Camera permission if using hand tracking features
- JavaScript enabled
- Enough local resources for 3D rendering and interactive plotting

---

## FAQ

**Does it run inside the browser?**  
Yes. The project is delivered as a web-based front-end experience.

**Is it suitable for teaching?**  
Yes. It is centered on geometry education and interactive visualization, so it can be used for lessons, demos, and practice sessions.

**Why does it ask for camera access?**  
The camera is used for hand tracking and gesture-controlled interaction.

**Where are the settings changed?**  
Look in the front-end source files for rendering, plotting, and interaction options.

**What if the 3D view renders incorrectly?**  
Check that your browser supports WebGL and that graphics support is enabled. Also make sure the project is being served properly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
