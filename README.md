⚡ Apple GPTK 4 Lab & Benchmark Simulator

An interactive, real-time visual sandbox and benchmark suite simulating the performance translation layer of Apple Game Porting Toolkit 4 (GPTK 4) and Metal 4.

Created & Maintained by Danilo Otupacca.

✨ Features

🎮 Architectural Pipeline Sandbox: Tweak translation pipeline bottlenecks live:

Shader Compilation: JIT vs. AOT Ahead-of-Time caching

Memory Model: Buffer Copy vs. Zero-Copy Unified Memory Architecture (UMA)

Geometry Shaders: CPU Fallback vs. Native Metal 4 Mesh Shader pipeline

Upscaling & Frame Gen: Spatial & Temporal MetalFX + Optical Flow Frame Interpolation

Thread Sync: Software barriers vs. Hardware ARM64 x86 TSO memory mapping

📈 Real-Time Render Simulation: Interactive HTML5 Canvas wireframe render stream paired with live frame-time latency charts (ms) and stutter risk meters.

📊 Benchmark Explorer: Direct comparison between GPTK 3 and GPTK 4 across Apple Silicon chips (M2, M3 Pro, M4 Max) and demanding DirectX 12 titles (Cyberpunk 2077, 007 First Light, Battlefield 6).

🇮🇹/🇬🇧 Dual Language Support: Complete bilingual interface toggle (Italian & English).

🛠️ Tech Stack

Frontend: Single-file Vanilla JavaScript (ES6+), HTML5 Canvas

Styling: Tailwind CSS & FontAwesome 6

Charts: Chart.js

🚀 Quick Start

No build tools or Node.js environment required! Simply open index.html in any modern web browser:

# Clone the repository
git clone https://github.com/your-username/gptk4-lab-simulator.git

# Navigate to directory
cd gptk4-lab-simulator

# Open index.html in your browser
open index.html


⚖️ License & Copyright

Distributed under the MIT License. See LICENSE for details.

Copyright (c) 2026 Danilo Otupacca
