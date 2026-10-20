# Aura 432 — Ambient Music Generator

[![Version](https://img.shields.io/badge/version-1.1-blue.svg?style=for-the-badge)](https://github.com/tagtthespellcaster/Aura-432)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Aura_432-brightgreen.svg?style=for-the-badge&logo=github)](https://tagtthespellcaster.github.io/Aura-432/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Enabled-orange.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

Aura 432 is a single-file, zero-dependency, real-time generative ambient soundscape generator and audio visualizer calibrated precisely to the **432 Hz** tuning standard (A4 = 432 Hz). 

Designed for deep relaxation, focus, meditation, and sleep, Aura 432 synthesizes evolving drone pads, randomized harmonic arpeggios, organic rain and wind textures, and binaural beats directly inside your browser.

**[Launch Aura 432 Live Demo](https://tagtthespellcaster.github.io/Aura-432/)**

---

## Features

- **432 Hz Master Tuning**: All scales, notes, FM synthesis modulators, and resonant frequencies are calculated using A4 = 432 Hz as the fundamental harmonic pitch.
- **Generative Ambient Engine**: Algorithmic melody generator with adjustable tempo, density, octave range, and musical scales:
  - Pentatonic Minor
  - Aeolian (Natural Minor)
  - Dorian
  - Lydian
  - Raga Bhupali
- **Evolving Drone & Synth Engine**: Multi-oscillator FM/Additive synth layers with long, organic attack and decay envelopes.
- **Nature Sound Synthesis**: Real-time synthesized brown/pink noise generators simulating gentle wind and rain.
- **Binaural Beats & Solfeggio Frequencies**: Sub-audible pitch differentials for brainwave entrainment (Delta, Theta, Alpha, Beta) alongside Solfeggio frequency overlays (174 Hz, 432 Hz, 528 Hz, 639 Hz, etc.).
- **Interactive Audio Visualizer**: HTML5 Canvas particle system and sinuous wave visualizer reacting dynamically to real-time Web Audio API frequency analysis.
- **Single File & Offline Ready**: Complete application contained within a single `index.html` file using vanilla JavaScript, Web Audio API, and Tailwind CSS via CDN.

---

## Tech Stack

- **Audio Engine**: Web Audio API (`AudioContext`, `OscillatorNode`, `BiquadFilterNode`, `GainNode`, `ConvolverNode`, `AnalyserNode`)
- **Visualizer**: HTML5 2D Canvas API
- **Styling**: Tailwind CSS (Utility-First CSS)
- **Deployment**: GitHub Pages (Static Hosting)

---

## Quick Start

Since Aura 432 is completely self-contained in a single file, running it locally requires no installation or build step.

### 1. Clone the Repository
```bash
git clone [https://github.com/tagtthespellcaster/Aura-432.git](https://github.com/tagtthespellcaster/Aura-432.git)
cd Aura-432
