# Creative Curiosities ✨

A tactile, sensorial playground engineered specifically for mobile browsers. 

This project was built to explore the raw joy of mobile-first creative coding—proving that you don't need heavyweight game engines, native SDKs, or complex build pipelines to build things that evoke wonder, awe, and playfulness right in the palm of your hand.

Crafted with love for [buildforjoy.dev](https://buildforjoy.dev).

---

## 🌟 The Philosophy: Building for Joy on Mobile

Modern smartphones are packed with incredible hardware—gyroscopes, low-latency audio chips, multi-touch screens, haptic engines, and HD cameras—yet so much of mobile web design treats screens like static desktop paper.

This project was built directly on mobile to learn and push the boundaries of native browser APIs:
- **Zero build steps:** No Node, no bundlers, no dependencies.
- **Single file delivery:** Everything lives inside a single `index.html` file.
- **Sensory inputs first:** Physics, sound synthesis, light exposure, and voice reactions driven entirely by native Web APIs.

---

## 🧪 Included Experiments

1. **Pocket Microcosm**
   * *Inputs:* Gyroscope / Device Orientation (`DeviceOrientationEvent`), Touch
   * *Experience:* Tilt your phone to steer physical currents. Tap to drop nutrient energy pulses that bioluminescent organisms hunt, feed on, and multiply around.

2. **Synesthetic Windchime (Chroma-Synth)**
   * *Inputs:* Camera (`navigator.mediaDevices.getUserMedia`), Web Audio API
   * *Experience:* Points your camera at the world to sample ambient hues in real time, translating everyday color palettes into soft, resonant pentatonic chimes.

3. **Kinetic Typography**
   * *Inputs:* Gravity / Tilt, Pointer Events, Haptic Feedback (`navigator.vibrate`)
   * *Experience:* Drop any word or phrase to turn it into bouncing letter-marbles. Roll them around your screen and scatter them with your fingers.

4. **Whispering Starglobe**
   * *Inputs:* Microphone / AudioContext AnalyserNode, 3D Canvas Projection
   * *Experience:* Speak, hum, or breathe softly into your mic to forge shining constellations onto a rotating 3D celestial sphere.

5. **Solar Cyanotype**
   * *Inputs:* Multi-touch Canvas Drawing, Pixel Manipulation
   * *Experience:* Simulates 19th-century photographic darkrooms. Paint botanical shadow silhouettes onto photosensitive emulsion, then run a chemical water bath to invert it into deep Prussian blue.

---

## 🚀 Live Demo & Deployment

Because features like camera access, microphone input, and device motion require a **Secure Context (HTTPS)**, this project runs best when hosted on GitHub Pages.

### Deploy Your Own:
1. Fork this repository.
2. In your repo, go to **Settings → Pages**.
3. Under **Branch**, select `main` (or `master`) and `/ (root)`.
4. Click **Save**.
5. Visit `https://<your-username>.github.io/<repo-name>/` on your mobile device!

---

## 🛠️ Fork It & Keep Building for Joy

This repository is intentionally designed as an open playground and a learning sandbox. 

Take it. Break it. Add new experiments:
- Map accelerometer shakes to musical percussion.
- Experiment with ambient light sensors (`AmbientLightSensor`).
- Use WebGL shaders or canvas blending modes to simulate watercolor paper.
- Build a pocket pendulum, a generative digital terrarium, or a tactile chime instrument.

Whatever you do, keep creating for the sheer delight of making things.

---

## 📄 License & Disclaimer

Released under the [MIT License](LICENSE).

This tool is provided **"AS IS"**, without warranty of any kind, express or implied. Build freely, remix often, and have fun.
