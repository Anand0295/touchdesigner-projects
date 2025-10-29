# Noise Landscape

A TouchDesigner experiment generating evolving 3D terrain and landscapes using procedural noise functions.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DM9ENeRx9CK/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) showcasing dynamic terrain generation.

## Visual Effect

- 3D terrain that continuously evolves and morphs
- Height maps driven by layered noise functions
- Atmospheric fog and depth effects
- Dynamic lighting creates dramatic shadows
- Color gradients map to elevation changes

## Interaction

- Mouse controls camera position and viewing angle
- Audio input affects terrain height and turbulence
- Time-based animation creates flowing landscapes
- Parameters adjustable for terrain characteristics

## Creative Coding Focus

- **Procedural Generation**: Using noise for terrain height maps
- **GLSL Displacement**: GPU-based geometry deformation
- **Multi-Octave Noise**: Combining noise at different scales
- **Height-Based Coloring**: Mapping colors to elevation
- **3D Camera Navigation**: Implementing flythrough effects

## Technical Approach

- Noise TOPs for height map generation
- Displace SOP for mesh deformation
- Custom GLSL shaders for rendering
- Camera COMP for 3D navigation
- Fog and post-processing for atmosphere
