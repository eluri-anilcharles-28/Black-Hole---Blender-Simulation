# Black-Hole---Blender-Simulation
Rendered in Blender Cycles using path-traced lighting with high bounce depth, combined with shader-based gravitational lensing approximations.

# Black Hole Simulation in Blender

Physically-inspired black hole visualization built in Blender using
shader-based gravitational lensing, volumetrics, and relativistic illusion techniques.


## Features
- Event horizon simulation
- Accretion disk with emission falloff
- Cycles optimized (GPU)

## Tech Stack
- Blender 4.x
- Cycles (GPU)

## Setup
1. Install Blender 4.x
2. Open `blackhole-v1.blend`
3. Switch to Cycles → GPU , colour management - filimic , and light Path - total 128 , Transmission - 128
4. Render

## Performance
- RTX 4050 Laptop: ~5–6 hrs for 240 frames @ 24fps
- Heavy use of volumetrics and transmission


## Limitations
- Not physically accurate GR but it Really Looks Great
- Visual simulation only
- No Kerr metric math implemented

## License
MIT
