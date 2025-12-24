# Black-Hole---Blender-Simulation
Rendered in Blender Cycles using path-traced lighting with high bounce depth, combined with shader-based gravitational lensing approximations.

# Black Hole Simulation in Blender

Physically-inspired black hole visualization built in Blender using
shader-based gravitational lensing, volumetrics, and relativistic illusion techniques.

## Preview


## Features
- Event horizon simulation
- Accretion disk with emission falloff
- Gravitational lensing (shader-based)
- HDRI-controlled starfield distortion
- Cycles optimized (GPU)

## Tech Stack
- Blender 4.x
- Cycles (GPU)
- Shader Nodes (No external plugins)
- Optional Python for automation

## How It Works (High-Level)
This is **not a true GR ray-tracer**.
It uses:
- Radial UV distortion
- Fresnel + Noise for spacetime curvature illusion
- Emission + Volume Scatter for accretion disk
- World shader lensing for background stars

Details: see `/docs/theory.md`

## Setup
1. Install Blender 4.x
2. Open `src/blackhole.blend`
3. Switch to Cycles → GPU
4. Render

## Performance
- RTX 4050 Laptop: ~5–6 hrs for 240 frames @ 24fps
- Heavy use of volumetrics and transmission

See `/docs/performance.md`

## Limitations
- Not physically accurate GR
- Visual simulation only
- No Kerr metric math implemented

## Future Work
- True ray-marching lensing
- Python-driven camera ray deflection
- Kerr black hole spin simulation

## License
MIT
