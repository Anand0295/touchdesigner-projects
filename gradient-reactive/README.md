# Gradient Reactive

A TouchDesigner experiment exploring dynamic color gradients that respond to audio input and user interaction.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DPRFAYBir8B/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) featuring fluid gradient animations.

## Visual Effect

- Smooth, flowing gradients that shift across the canvas
- Multiple color stops that animate independently
- Gradient angles rotate and evolve over time
- Color hues respond to audio frequencies
- Additive blending creates luminous overlapping regions

## Interaction

- Audio input drives gradient intensity and color shifts
- Mouse position controls gradient direction and speed
- Real-time manipulation of color stops
- MIDI controllers can map to individual gradient parameters

## Creative Coding Focus

- **GLSL Color Mixing**: Advanced gradient generation in shaders
- **Audio Analysis**: FFT-based frequency-to-color mapping
- **Ramp TOPs**: Dynamic gradient construction and manipulation
- **Color Theory**: HSV/HSL color space transformations
- **Noise Functions**: Perlin noise for organic gradient movement

## Technical Approach

- Custom GLSL fragment shaders for smooth gradients
- Audio Analysis CHOPs for reactive parameters
- Ramp TOP for color stop manipulation
- Composite TOPs with blend modes for layering
- Feedback loops for trailing gradient effects
