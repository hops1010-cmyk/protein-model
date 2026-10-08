# 3D Protein Molecule Model

A production-ready 3D molecular visualization built with Three.js and GSAP.

## Features
- **Procedural Generation**: Generates a synthetic multi-chain protein structure using parametric math to simulate alpha-helix and beta-sheet folding.
- **Ball-and-Stick Visualization**: Classic molecular representation with CPK-inspired coloring (Carbon, Oxygen, Nitrogen, Hydrogen).
- **GSAP Choreography**: 
  - Cinematic camera reveal.
  - Conformational mutation: Scales up active binding sites to simulate molecular engagement.
  - Macro/Micro rotation sequences.
- **Thermal Kinetics**: Real-time harmonic noise oscillation to simulate microscopic cellular vibrations.

## Tech Stack
- **Three.js**: 3D Rendering & Scene Graph.
- **GSAP (GreenSock)**: Complex animation sequencing.
- **HTML5/CSS3**: UI overlay and layout.

## Quick Start
1. Clone the repository.
2. Open `index.html` in any modern web browser.

## Deploy to Vercel
1. Import the repository in Vercel and keep the project root at the repository root.
2. Use the `Other` framework preset. No install or build command is required.
3. Deploy. Vercel serves `index.html` from the repository root.

The included `vercel.json` sets the static output directory to the repository root.
