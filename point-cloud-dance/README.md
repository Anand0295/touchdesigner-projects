# Point Cloud Dance

A TouchDesigner experiment creating choreographed particle systems that move and flow like a swarm, forming abstract 3D sculptures.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DD2eUZBNwWo/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) showcasing dynamic point cloud animations.

## Visual Effect

- Thousands of particles arranged in 3D space
- Points move in coordinated swarm-like patterns
- Particles respond to force fields and attractors
- Color variations based on velocity and position
- Depth-based opacity creates volumetric feel

## Interaction

- Mouse position creates attraction/repulsion forces
- Audio frequencies generate turbulence in the point cloud
- Camera navigation allows exploration of 3D space
- MIDI controllers can influence particle behavior parameters

## Creative Coding Focus

- **GPU Particles**: Compute shaders for efficient particle systems
- **Force Simulation**: Physics-based particle movement
- **Instancing**: Rendering thousands of points efficiently
- **Noise Fields**: 3D Perlin noise for organic movement
- **Camera Control**: 3D navigation and perspective manipulation

## Technical Approach

- Compute shader TOPs for particle updates
- CHOP networks for force field calculations
- Geometry instancing for point rendering
- Custom GLSL for particle appearance
- Audio analysis for reactive behavior
