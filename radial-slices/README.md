# Radial Slices

A TouchDesigner experiment featuring radial segmentation and dynamic slice animations that create kaleidoscopic visual patterns.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DCg56b4xhqw/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) showcasing radial geometric transformations.

## Visual Effect

- Circular canvas divided into rotating wedge-shaped slices
- Each slice can rotate, scale, or offset independently
- Kaleidoscopic mirroring effects across slices
- Color variations per segment create visual rhythm
- Smooth transitions between slice states

## Interaction

- Number of slices controlled by audio input or mouse position
- Rotation speed responds to amplitude or user interaction
- Individual slice parameters can be modulated independently
- Real-time manipulation of slice angles and offsets

## Creative Coding Focus

- **Polar Coordinates**: Converting between Cartesian and polar systems
- **GLSL Fragment Shaders**: Radial UV mapping and slice generation
- **Instancing**: Efficient rendering of multiple slice geometries
- **Audio Reactivity**: FFT analysis driving slice parameters
- **Modulo Operations**: Creating repeating angular patterns

## Technical Approach

- Custom GLSL shaders for radial mapping
- CHOP audio analysis for parameter modulation
- Replicator TOPs for slice generation
- Composite operations for blend modes between slices
- Transform feedback for smooth animations
