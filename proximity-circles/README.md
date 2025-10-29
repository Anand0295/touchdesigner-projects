# Proximity Circles

A TouchDesigner experiment exploring interactive circle formations that respond to proximity and movement.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DPpQd4KDJ5W/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) featuring dynamic circular patterns.

## Visual Effect

- Concentric circles that expand and contract based on proximity
- Overlapping circles create moiré-like interference patterns
- Smooth transitions between states create organic movement
- Color gradients shift based on circle interactions

## Interaction

- Mouse/touch position controls primary circle center
- Distance between elements affects circle size and opacity
- Multiple interaction points create complex overlapping patterns
- Real-time response to user movement

## Creative Coding Focus

- **GLSL Shaders**: Distance field calculations for smooth circle rendering
- **Particle Systems**: Managing multiple circle centers and their properties
- **TouchOSC Integration**: Potential for multi-touch control
- **Feedback Loops**: Creating trailing effects and motion blur
- **Math Operations**: Using distance formulas and interpolation for smooth animations

## Technical Approach

- SOP-based geometry generation
- CHOP channels for smooth parameter control
- Custom GLSL fragment shaders for rendering
- TOP feedback for cumulative visual effects
