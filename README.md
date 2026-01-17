# Sound Wave Visualization (HTML5 + Web Audio API)

A lightweight, dependency-free audio player and waveform visualizer built with **HTML5 Canvas** and the **Web Audio API**.  
It supports local audio playback, real-time waveform rendering, idle animation, and customizable spectrum styles.

---

## ✨ Features

- 🎵 **Local Audio Playback**
  - Drag & drop audio files or select via file input
  - Supports common formats: `mp3`, `wav`, `m4a`, etc.

- 🌊 **Real-time Waveform Visualization**
  - Time-domain waveform rendered on `<canvas>`
  - Smooth animation using `requestAnimationFrame`

- 💤 **Idle Wave Animation**
  - Displays a subtle animated wave when audio is not playing
  - Visible even on initial page load

- 🎨 **Customizable Spectrum Style**
  - Change waveform **color**, **opacity**, and **line width**
  - One-click reset to default values
  - Dark mode–aware default colors

- 🔊 **Independent Audio Analysis**
  - Volume control does **not** affect waveform analysis
  - Analyzer node is placed before the gain node

- 📱 **Responsive & Retina-ready**
  - Automatically scales for device pixel ratio
  - Adapts to window resizing

---

## 🚀 How to Use

1. Open `sound-visualization.html` in a modern browser  
2. Drag & drop an audio file (or use the file selector)
3. Click **Play** to start playback and visualization
4. Adjust volume or customize waveform style as needed

> ⚠️ Due to browser autoplay policies, audio playback and the AudioContext
> start only after a user interaction (e.g., clicking the Play button).

---

## 🛠️ Tech Stack

- HTML5
- CSS (no framework)
- JavaScript (Vanilla)
- Web Audio API
- Canvas API

---

## 📂 Project Structure

