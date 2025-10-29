# Stipple Glow

A TouchDesigner experiment creating glowing particle systems with stippling and pointillistic effects.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DOq7cCfiMaG/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) featuring luminous dot patterns.

## Visual Effect

- Dense particle fields creating stippled imagery
- Each particle emits a soft glow and bloom effect
- Particles vary in size and brightness
- Layered composition creates depth through opacity
- Smooth animation of particle positions and intensities

## Interaction

- Mouse position influences particle attraction and density
- Audio input modulates glow intensity and color
- Image input can drive particle distribution
- Interactive control over stipple density and size

## Creative Coding Focus

- **GPU Particles**: High-density particle rendering
- **Bloom and Glow**: Post-processing for luminosity
- **Pointillism Algorithm**: Converting images to particle representations
- **Instance Rendering**: Efficient rendering of thousands of glowing points
- **Depth of Field**: Creating focus effects with particle blur

## Technical Approach

- Particle GPU for high-performance particles
- Bloom TOP for glow effects
- Composite operations for additive blending
- CHOP-driven particle parameters
- Custom GLSL for particle appearance and glow
