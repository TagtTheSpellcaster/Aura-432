# Aura 432 — Ambient Music Generator

[![Version](https://img.shields.io/badge/version-1.3-blue.svg?style=for-the-badge)](https://github.com/tagtthespellcaster/Aura-432)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Aura_432-brightgreen.svg?style=for-the-badge&logo=github)](https://tagtthespellcaster.github.io/Aura-432/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Enabled-orange.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

Aura 432 is a single-file, zero-dependency, real-time generative ambient soundscape generator and audio visualizer calibrated precisely to the 432 Hz tuning standard (A4 = 432 Hz).

Designed for deep relaxation, focus, meditation, and sleep, Aura 432 synthesizes evolving drone pads, randomized harmonic arpeggios, organic rain and wind textures, binaural beats, and chord progressions directly inside your browser.

Live Demo: https://tagtthespellcaster.github.io/Aura-432/

---

## Features

- 432 Hz Master Tuning: All scales, notes, FM synthesis modulators, and resonant frequencies are calculated using A4 = 432 Hz as the fundamental harmonic pitch.
- Generative Ambient Engine: Algorithmic melody generator with adjustable tempo, density, octave range, and musical scales:
  - Pentatonic Minor
  - Aeolian (Natural Minor)
  - Dorian
  - Lydian
  - Raga Bhupali
- Evolving Drone & Synth Engine: Multi-oscillator FM/Additive synth layers with long, organic attack and decay envelopes.
- Harmonic & Chord Layer: Evolving chord progressions (Maj7, min9, sus2, add9) with smooth morphing and crystalline FM bell/chime counterpoint melodies.
- Nature Sound Synthesis: Real-time synthesized brown/pink noise generators simulating gentle wind and rain.
- Binaural Beats & Solfeggio Frequencies: Sub-audible pitch differentials for brainwave entrainment alongside Solfeggio frequency overlays (174 Hz, 432 Hz, 528 Hz, 639 Hz).
- Interactive Audio Visualizer: HTML5 Canvas particle system and sinuous wave visualizer reacting dynamically to real-time Web Audio API frequency analysis.
- Single File & Offline Ready: Complete application contained within a single index.html file using vanilla JavaScript, Web Audio API, and Tailwind CSS.

---

## User Guide

### 1. Starting Audio
Due to browser autoplay restrictions, click the "Start Audio" button at the top of the interface to initialize the Web Audio API context.

### 2. Main Controls
- Master Volume: Controls the overall output level of the application.
- Preset Selection: Select pre-configured soundscapes such as Deep Meditation, Rainy Focus, Cosmic Drift, or Solfeggio Healing to instantly load balanced parameter sets.

### 3. Generative Melody Engine
- Scale Selector: Choose the musical scale used for random melody generation (Pentatonic Minor, Aeolian, Dorian, Lydian, Raga Bhupali).
- Density & Tempo: Adjust how frequently melodic notes are triggered and the base pulse speed.
- Octave Range: Set the pitch range for generated notes.

### 4. Harmonic & Chord Layer
- Chord Progression: Select the active harmonic progression (Atmospheric I-V-vi-IV, Modal Drift, Warm Sus2 Cycle, Harmonic Minor, Ambient Ether).
- Morph Speed: Adjust how slowly chords transition into one another.
- Chord Volume: Set the volume of the underlying pad chords.
- Bell / Chime Volume: Adjust the level of high-frequency FM bell counterpoint notes.

### 5. Sound Layers & Nature FX
- Drone Synth: Adjust the volume and cutoff frequency of the continuous low-end pad.
- Rain & Wind FX: Use individual volume sliders to blend synthesized nature noise.

### 6. Binaural Beats & Solfeggio Frequencies
- Binaural Beat: Select target brainwave states (Delta 2 Hz, Theta 6 Hz, Alpha 10 Hz, Beta 18 Hz) and adjust the mix level. Headphones are required for binaural entrainment.
- Solfeggio Tone: Overlay pure reference tones tuned to historical Solfeggio frequencies (174 Hz, 432 Hz, 528 Hz, 639 Hz).

---

## Tech Stack

- Audio Engine: Web Audio API (AudioContext, OscillatorNode, BiquadFilterNode, GainNode, ConvolverNode, AnalyserNode)
- Visualizer: HTML5 2D Canvas API
- Styling: Tailwind CSS
- Deployment: GitHub Pages

---

## Quick Start

Since Aura 432 is completely self-contained in a single file, running it locally requires no installation or build step.

### 1. Clone the Repository
```bash
git clone [https://github.com/tagtthespellcaster/Aura-432.git](https://github.com/tagtthespellcaster/Aura-432.git)
cd Aura-432
