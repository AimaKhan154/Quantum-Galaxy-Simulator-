🚀 Quantum Shaper — Interactive 3D Particle System

An advanced real-time 3D particle visualization system powered by gesture recognition.
Quantum Shaper allows users to manipulate thousands of particles in 3D space using hand movements detected through a webcam.

This project combines computer graphics, real-time rendering, and computer vision to create an immersive interactive experience.

📌 Overview

Quantum Shaper renders a dynamic particle system that morphs into multiple mathematically generated shapes. Users control the system using intuitive hand gestures such as movement, pinch, and hand expansion.

The application integrates GPU-accelerated rendering with real-time gesture detection to deliver smooth and responsive interaction.

✨ Features

🎇 Real-time 3D particle rendering (6000+ particles)

🖐️ Hand gesture recognition via webcam

🔄 Smooth morphing between multiple complex shapes

🌌 Procedural starfield background

🎨 Dynamic color transitions

⚡ GPU-accelerated rendering using WebGL

🧠 Organic “breathing” particle animation

📱 Responsive full-screen canvas

🧬 Available Particle Shapes

Nebula Sphere

Spiral Galaxy

Double Helix (DNA)

Quantum Cube

Cyber Heart

Torus Field

Supernova Burst

Each shape is generated using mathematical algorithms and smoothly interpolated for seamless transitions.

🕹️ Gesture Controls
Gesture	Action
✋ Move Hand	Rotate and reposition particle system
👌 Pinch	Switch to next shape
👐 Open Hand	Expand particle structure
✊ Close Hand	Compress particle structure
🛠️ Technologies Used

HTML5

CSS3

JavaScript (ES6)

Three.js (WebGL 3D Rendering)
<img width="1908" height="876" alt="Screenshot 2026-02-20 194202" src="https://github.com/user-attachments/assets/799f2b1d-19ce-4fa4-af14-b441787b76b2" />
<img width="1908" height="876" alt="Screenshot 2026-02-20 194202" src="https://github.com/user-attachments/assets/266a8094-6dbd-4c84-9050-fb29949b2b2c" />

MediaPipe Hands (Computer Vision)

WebGL

🏗️ System Architecture
1️⃣ Rendering Engine

Uses Three.js with BufferGeometry to efficiently render thousands of particles using GPU acceleration.

2️⃣ Shape Generator

Implements mathematical models to generate 3D coordinates for different particle structures.

3️⃣ Animation Engine

Uses interpolation (LERP) and procedural noise functions for smooth morphing and organic movement.

4️⃣ Gesture Recognition

MediaPipe detects hand landmarks and converts them into interaction controls.

5️⃣ Interaction Controller

Maps hand position and gestures into particle transformations in real time.

