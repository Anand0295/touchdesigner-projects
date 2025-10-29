# Mesh Morph

A TouchDesigner experiment exploring 3D mesh deformations and transformations using displacement techniques and vertex animation.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DKz6E8SR1jb/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) featuring organic mesh deformations.

## Visual Effect

- 3D meshes that smoothly deform and morph between shapes
- Vertex displacement creates wave-like and organic movements
- Surface textures respond to deformation
- Smooth interpolation between multiple target states
- Dynamic lighting reveals surface topology changes

## Interaction

- Mouse position controls deformation intensity and direction
- Audio input drives vertex displacement amplitude
- Time-based animations create autonomous morphing cycles
- MIDI controllers can adjust deformation parameters in real-time

## Creative Coding Focus

- **Vertex Shaders**: GPU-based vertex displacement
- **SOP Networks**: Geometry manipulation and deformation
- **Noise Displacement**: Using noise functions for organic movement
- **Blend Shapes**: Morphing between multiple mesh states
- **Normal Mapping**: Dynamic surface detail generation

## Technical Approach

- Custom GLSL vertex shaders for displacement
- SOP-based geometry operations
- CHOP data for vertex animation control
- Texture-based displacement mapping
- Camera and lighting setup for dramatic effect
