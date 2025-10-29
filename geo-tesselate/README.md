# Geo Tesselate

A TouchDesigner experiment exploring geometric tessellation patterns that animate and transform through subdivision and displacement.

## Inspiration

Inspired by [this Instagram reel](https://www.instagram.com/reel/DF-v8EQNwTe/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) showcasing intricate tessellated geometry.

## Visual Effect

- Polygons subdivided into intricate tessellation patterns
- Geometric shapes that recursively split and transform
- Each face can rotate, scale, or offset independently
- Color variations create visual hierarchy in the pattern
- Smooth transitions between tessellation states

## Interaction

- Mouse position controls subdivision levels
- Audio input drives rotation and scale of individual elements
- Real-time manipulation of tessellation density
- Pattern complexity responds to user interaction

## Creative Coding Focus

- **Geometry Subdivision**: Recursive mesh refinement
- **SOP Operations**: Advanced geometry manipulation
- **Instancing**: Efficient rendering of repeated elements
- **Fractal Patterns**: Self-similar geometric structures
- **Wireframe Rendering**: Highlighting geometric structure

## Technical Approach

- Subdivide SOP for mesh refinement
- Copy and Transform SOPs for pattern generation
- Custom geometry shaders for tessellation
- CHOP-driven parameter animation
- Edge rendering for wireframe aesthetics
