# Aura 432 — Ambient Music Generator

[![Version](https://img.shields.io/badge/version-1.6-blue.svg?style=for-the-badge)](https://github.com/tagtthespellcaster/Aura-432)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Aura_432-brightgreen.svg?style=for-the-badge&logo=github)](https://tagtthespellcaster.github.io/Aura-432/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Enabled-orange.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![PWA Ready](https://img.shields.io/badge/PWA-Offline_Ready-purple.svg?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

Aura 432 is a zero-dependency, real-time generative ambient soundscape generator, audio visualizer, and Progressive Web App (PWA) calibrated precisely to the 432 Hz tuning standard (A4 = 432 Hz).

Designed for deep relaxation, focus, meditation, sleep, and pain relief, Aura 432 synthesizes evolving drone pads, randomized harmonic arpeggios, organic rain and wind textures, binaural beats, and chord progressions directly inside your browser without external audio samples.

Live Demo: https://tagtthespellcaster.github.io/Aura-432/

---

## What's New in v1.6

- **Full PWA & Offline Support**: Integrated `manifest.json` and `sw.js` (Service Worker) allowing instant installation on desktop and mobile devices, functioning completely offline.
- **Built-in Quick Presets**: Built-in soundscapes tailored for specific mental states (Deep Sleep & Rest, Deep Work & Focus, Creative Flow, Pain & Tension Relief).
- **Preset Management System**: Save and load custom synthesizer states locally via `.json` files.
- **Enhanced Lead Engine**: Multi-timbre Lead Synthesizer featuring Acoustic Handpan, Glass Chime, Soft Flute, Warm Electric Keys, and Plucked Kalimba models.

---

## Features

- **432 Hz Master Tuning**: All scales, notes, FM synthesis modulators, and resonant frequencies are calculated using A4 = 432 Hz as the fundamental harmonic pitch.
- **Generative Ambient Engine**: Algorithmic melody generator with adjustable tempo, density, octave range, and musical scales:
  - Zen Pentatonic
  - Suspended Aeolian (Natural Minor)
  - Astral Dorian
  - Ethereal Lydian
  - Raga Bhupali (Meditative)
- **Melodic Lead Engine**: Independent Lead instrument with custom performance styles (Handpan Concert, Slow Ambient Drift, Syncopated Grooves, Triplet Waves).
- **Harmonic & Chord Layer**: Evolving chord progressions (Celestial Journey, Ethereal Sus, Deep Space Drift, Warm Sunrise) with smooth morphing and crystalline FM bell/chime counterpoint melodies.
- **Nature Sound Synthesis**: Real-time synthesized brown and pink noise generators simulating gentle wind and ocean rain.
- **Binaural Beats & Solfeggio Frequencies**: Sub-audible pitch differentials for brainwave entrainment (Delta 0.5 Hz, Theta 4 Hz, Schumann 7.83 Hz, Alpha 10 Hz) alongside Solfeggio frequency overlays (174 Hz, 432 Hz, 528 Hz, 639 Hz).
- **Interactive Audio Visualizer**: Responsive HTML5 Canvas particle system and sinuous wave visualizer reacting dynamically to real-time Web Audio API frequency analysis.
- **PWA & Offline Installation**: Instant installability as a native-like app on Windows, macOS, Android, and iOS with full offline caching.

---

## User Guide

### 1. Starting Audio
Due to browser autoplay restrictions, click the **"Start Audio"** button or click anywhere on the central visualizer canvas to initialize the Web Audio API context.

### 2. Master & Ambient Acoustics
- **Master Volume**: Controls the overall output gain level.
- **Filter Cutoff**: Adjusts the low-pass master filter threshold (100 Hz – 5000 Hz) to tame bright frequencies.
- **Reverb/Delay Space**: Controls the wet mix level of the spatial cross-delay and reverb network.

### 3. Quick Presets & File Management
- **Quick Built-in Presets**: Choose pre-configured parameter sets from the dropdown menu:
  - *Deep Sleep & Rest* (174 Hz + Delta 0.5 Hz)
  - *Deep Work & Focus* (432 Hz + Schumann 7.83 Hz)
  - *Creative Flow* (528 Hz + Theta 4 Hz)
  - *Pain & Tension Relief* (174 Hz + Alpha 10 Hz)
- **Save Preset**: Exports your current synthesizer parameters into an `.json` file.
- **Load Preset**: Imports a previously saved `.json` preset file to restore all slider settings and parameters instantly.

### 4. Sound Layer Mixer
- **Melodic Lead Engine**: Choose instrument timbres (Handpan, Glass, Flute, Keys, Kalimba), sequence styles, speed, and volume.
- **FM Ambient Pad**: Adjust the underlying generative pad layer volume.
- **Sub-Bass Drone**: Control the 108 Hz / 54 Hz grounding fundamental drone layer.
- **Rain & Wind FX**: Blend synthesized pink and brown noise textures.
- **Solfeggio & Binaural Tones**: Select pure reference frequencies and brainwave target beat rates. Headphones are recommended for binaural entrainment.

---

## Tech Stack

- **Audio Engine**: Web Audio API (`AudioContext`, `OscillatorNode`, `BiquadFilterNode`, `GainNode`, `DelayNode`, `AnalyserNode`, `ChannelMergerNode`)
- **PWA Integration**: Service Worker (`sw.js`), Web App Manifest (`manifest.json`), Offline Caching
- **Visualizer**: HTML5 2D Canvas API
- **Styling**: Tailwind CSS & Lucide Icons
- **Deployment**: GitHub Pages

---

## Quick Start & Installation

### Running Locally
No build tools, Node.js, or package installation required.

```bash
git clone [https://github.com/tagtthespellcaster/Aura-432.git](https://github.com/tagtthespellcaster/Aura-432.git)
cd Aura-432
