# Shader Moiré Lines 🌊✨
Did you ever stare at wavy patterns moving across a screen and wonder—how is that even possible?
  
**This project brings the mesmerizing moiré effect to life using TouchDesigner and animated shader lines!**
Inspired by [this Instagram reel](https://www.instagram.com/reel/DFclaRKTW63/), this experiment explores interactive, real-time generative art driven by classic moiré interference. It's visually trippy, hypnotic, and a fantastic introduction to both shaders and motion graphics.

---

## ✨ What is it?
- **Real-time shader animation** creating intersecting, animated lines
- Interactive and endlessly customizable moiré patterns as you tweak parameters
- No actual "drawing"—just smart use of GLSL (or TouchDesigner's nodes) and math for art
- Perfect for backgrounds, VJ sets, or creative coding playgrounds

---

## 🛠 How does it work?
1. **Shader Magic**:  
   - Render layered or intersecting lines using simple mathematical functions in a GLSL TOP (or built-in nodes)
2. **Animate!**:  
   - Animate lines by shifting frequency, amplitude, or offset variables over time
3. **Moiré Patterns**:  
   - Overlay two or more waves/grids, controlling angles and speeds—watch interference magic appear!
4. **Interactivity**:  
   - Add controls for speed, direction, or color to make the visuals dance to your taste

---

## 🎯 Why you'll love this
- **Instant ambient visuals**—perfect as a screensaver or for live projection art
- Learn core shader logic or generative art principles, but play it all in real-time
- Meditative, hypnotic, and surprisingly minimal code
- *Great entry point* for TouchDesigner users who want to try shaders or sound-reactive graphics

---

## 🚀 Getting Started
- Clone/download this folder and open the `.toe` file in TouchDesigner

## 🚀 Step-by-Step Setup

1. **Install TouchDesigner**
   - Download the latest free/non-commercial version from [https://derivative.ca/download](https://derivative.ca/download).
   - Install and launch TouchDesigner on your computer.

2. **Clone or Download This Project**
   - From this repo, click the green "Code" button → Download ZIP (or use git clone if you prefer).
   - Unzip and open the `shader-moire-lines` folder.

3. **Open the Project**
   - Open TouchDesigner, then open the `.toe` file in this folder (if present), or create a new project to follow along.

4. **Set Up the Moiré Shader**
   - Add a **GLSL TOP** (or use nodes if GLSL is unfamiliar).
   - To create classic moiré lines: in GLSL TOP, use sine/cosine functions to draw horizontal or diagonal lines based on UV coordinates.
   - Example GLSL logic:
     - `float lines = sin(uv.y * freq1 + offset1) + sin(uv.x * freq2 + offset2);`
     - Feed time or parameters for offset1, offset2 to animate the effect.
   - Overlay two sets of lines at different angles, frequencies, or with animation for the trippy interfering look.

5. **Add Animation and Controls**
   - Animate offsets or frequencies using TouchDesigner's **Constant CHOP** and **Math CHOP**, exporting as uniforms to your shader.
   - If node-based: stack multiple **Pattern TOPs** or **Ramp TOPs** at different orientations, animate their transforms, then blend/multiply them.

6. **Color, Glow, & Output**
   - Tweak your shader to add color cycling (e.g., using HSV to RGB conversion in code).
   - For glow or trails, add an **Edge TOP**, **Blur TOP**, or compositing effects.
   - Connect to **Null TOP** and then to an **Out TOP** for previewing.

7. **Experiment!**
   - The best results come from tweaking: try different frequencies, angular relationships, and animation speeds. Moiré is all about interference, so experiment!

8. **Save & Share**
   - Save your artful patch as a `.toe` file in this folder. Add screenshots and improvements as you go!

## Troubleshooting
- Shader/top not rendering? Make sure your GPU supports TouchDesigner and GLSL TOP features.
- Stray bands or no effect? Check your line formula, UV range, and blend modes.

This project is fully reproducible—no permissions or human setup required. Enjoy generative shader art!

---

## 💡 Inspiration
- Visuals inspired by the [DFclaRKTW63 Instagram reel](https://www.instagram.com/reel/DFclaRKTW63/)
- Built using creative coding, generative art, and shader/GLSL tricks

---

## 📷 Show Your Results!
Tweak the code, find wild new waves, and tag [@yourhandle]—or share a Pull Request with your own shader remixes!

---

**Bring hypnotic moiré waves to every screen.**  
Enjoy the trippy ride! 🌀re
