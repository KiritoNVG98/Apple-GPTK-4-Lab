# ⚡ Apple GPTK 4 Lab & Benchmark Simulator

An interactive, real-time visual sandbox and benchmark suite simulating the DirectX 12 → Metal 4 translation layer of **Apple Game Porting Toolkit 4 (GPTK 4)** on Apple Silicon.

Created & maintained by **Danilo O.**

> 🇮🇹 **Apple GPTK 4 Lab** è uno strumento interattivo per esplorare le innovazioni architetturali di GPTK 4 e Metal 4: simula l'impatto prestazionale delle singole fasi della pipeline di traduzione DirectX 12 → Metal e confronta i benchmark dei principali giochi su vari SoC Apple Silicon (serie M2, M3 e M4). Interfaccia completa in Italiano e Inglese.

---

## 📂 Pages

| File | Description |
| --- | --- |
| [`index.html`](./index.html) | **Lab & Benchmark Simulator** – architectural pipeline sandbox, real-time render stream and benchmark explorer. |
| [`performance-simulator.html`](./performance-simulator.html) | **Performance & Architecture Simulator** – AAA game library with GPTK 3 vs GPTK 4 FPS, side-by-side comparison and Apple Silicon SoC chart. |

## ✨ Features

- 🎮 **Architectural Pipeline Sandbox** – tweak translation pipeline bottlenecks live:
  - Shader compilation: JIT vs. AOT (ahead-of-time caching)
  - Memory model: buffer copy vs. zero-copy Unified Memory Architecture (UMA)
  - Geometry shaders: CPU fallback vs. native Metal 4 mesh shader pipeline
  - Upscaling & frame generation: spatial & temporal MetalFX + optical-flow frame interpolation
  - Thread sync: software barriers vs. hardware x86 TSO memory ordering on ARM64
- 📈 **Real-Time Render Simulation** – HTML5 Canvas wireframe render stream with live frame-time (ms) charts and stutter-risk meters.
- 📊 **Benchmark Explorer** – GPTK 3 vs. GPTK 4 across Apple Silicon chips (M2, M3 Pro, M4 Max) and demanding DirectX 12 titles (Cyberpunk 2077, 007 First Light, Battlefield 6) at 1080p, 1440p and 4K.
- 🇮🇹 / 🇬🇧 **Dual language** – full Italian / English interface toggle.

## 🛠️ Tech Stack

- Single-file vanilla JavaScript (ES6+) & HTML5 Canvas
- Tailwind CSS (CDN) & FontAwesome 6
- Chart.js

## 🚀 Quick Start

No build tools or Node.js required – just open the page in any modern browser (Safari, Chrome, Firefox, Edge). An internet connection is needed to load the CDN libraries.

```bash
# Clone the repository
git clone https://github.com/KiritoNVG98/Apple-GPTK-4-Lab.git

# Enter the directory
cd Apple-GPTK-4-Lab

# Open the simulator (macOS)
open index.html
```

## ⚠️ Disclaimer

This is an independent, educational simulation. Performance figures are modelled estimates, not official measurements. Not affiliated with or endorsed by Apple Inc.

## ⚖️ License

Distributed under the MIT License. See [LICENSE](./LICENSE) for details.

Copyright (c) 2026 Danilo O.
