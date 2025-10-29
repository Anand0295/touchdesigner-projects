# Webcam Particles 🎉✨
Ever wished your webcam could do something a little… magical?
  
**This project unleashes particle magic straight from your video feed!**
Inspired by [this Instagram reel](https://www.instagram.com/reel/DP87WHziMiI/), this TouchDesigner experiment lets pure white spots from your webcam *emit* dynamic particles in real-time. It's playful, mesmerizing, and the perfect way to get creative with new media art—even if you're just starting out.

---

## ✨ What is it?
- **Live webcam feed** processed in TouchDesigner
- **Bright (white) regions** become emitters for vibrant, animated particles
- All **no-code** TouchDesigner—just connect, tweak, and get instant interactive results
- Beginner-friendly, but open to deep customizations for tinkerers

---

## 🛠 How does it work?
1. **Webcam Input**: Streams your camera using Video Device In TOP
2. **Brightness Masking**: Detects the brightest (white) zones with a Threshold/Luma node
3. **Particle Emission**: Spawns whimsical particles right where brightness hits the screen
4. **Style Your Magic**: Adjust color, speed, glow, and trails to your heart's content

---

## 🎯 Why you'll love this
- **Instant visual fun** for creative coding or streaming
- Learn the basics of TouchDesigner **by playing**
- Makes you (and your room!) the center of art
- *Perfect starter* for generative art, new media, or anyone bored of vanilla webcam calls

---

## 🚀 Getting Started
- Clone/download this folder and open the `.toe` file in TouchDesigner
- [Coming soon] Step-by-step setup and customization guide in the README

---

## 💡 Inspiration
- Technique inspired by the [nyltiek Instagram reel](https://www.instagram.com/reel/DP87WHziMiI/)
- Particle system refined using help from the TouchDesigner and creative coding communities

---

## 📷 Show Your Results!
Got wild or beautiful outputs?  
Share a screenshot, tag [@yourhandle] on Instagram, or submit a Pull Request with improvements!

---

**Let's turn every webcam moment into a burst of art.**  
Happy patching! 🙌

## 🚀 Step-by-Step Setup

1. **Install TouchDesigner**
   - Download the latest non-commercial version of [TouchDesigner](https://derivative.ca/download) (free for most basic projects).
   - Install and launch the software.

2. **Download the Project Files**
   - Click the green "Code" button above and select "Download ZIP" to get this repo.
   - Unzip and enter the `webcam-particles` folder.

3. **Open the Project**
   - Double-click the `.toe` (TouchDesigner project) file (add your patch here when ready—see below if starting from scratch).
   - If you're building from scratch, open TouchDesigner and create a new project.

4. **Set Up Your Webcam Input**
   - Add a **Video Device In TOP** node to bring your webcam into TouchDesigner.
   - Ensure your webcam is selected and visible in the node output.

5. **Isolate White Regions**
   - Add a **Luma Level TOP** or **Threshold TOP** node after your webcam node.
   - Adjust threshold or luma settings so only the white (brightest) areas become visible/white; everything else should be black.

6. **Create the Particle Effect**
   - Add a **Particle SOP** or use the GPU Particle system.
   - Set the threshold/luma node's output as the **emission mask** for the particle system.

7. **Style the Particles**
   - Tweak particle color, size, speed, and behaviors for your desired look.
   - Add a **Trail SOP** for motion blur, or post-processing effects like glow.

8. **Preview and Play**
   - Connect your final output to a **Null TOP** and then to an **Out TOP** for preview.
   - Move bright objects or a white card in front of your webcam—the particles will follow the light!

9. **Save and Share**
   - Save your project as a `.toe` file in this folder.
   - Add screenshots or rendered videos if you want to show off your results.

---

### **Troubleshooting**
- If your webcam feed is black, check the Video Device In settings for camera permissions.
- If no particles appear, lower the threshold so more areas qualify as "bright/white."
