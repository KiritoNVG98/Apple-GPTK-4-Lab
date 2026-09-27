# Apple-GPTK-4-Lab
Simulatore Architetturale &amp; Benchmark di Traduzione DirectX 12 → Metal 4
Apple GPTK 4 Lab & Benchmark Simulator

An interactive web application designed to simulate, analyze, and visualize DirectX 12 to Metal 4 real-time graphics translation under Apple Game Porting Toolkit 4 (GPTK 4) on Apple Silicon architectures.

🇮🇹 Descrizione del Progetto

Apple GPTK 4 Lab è uno strumento interattivo progettato per esplorare le innovazioni architetturali di GPTK 4 e Metal 4. Permette di simulare l'impatto prestazionale delle singole fasi della pipeline di traduzione real-time da DirectX 12 a Metal e di confrontare i benchmark dei principali giochi su vari SoC Apple Silicon (serie M2, M3 e M4).

Funzionalità Principali

Sandbox Architetturale: Modella e simula il tempo di frame, l'overdue della CPU, lo stuttering e l'uso della memoria in base alle tecnologie abilitate:

Compilazione Shader JIT vs AOT

Gestione Memoria Buffer Copy vs Zero-Copy UMA

Emulazione Mesh Shaders vs Metal 4 Hardware pipeline

Integrazione MetalFX (Spatial, Temporal e Frame Generation)

Sincronizzazione Thread CPU (x86 TSO su ARM64)

Simulazione Render Stream In Tempo Reale: Canvas grafico dinamico con tracciamento della fluidità del frame time.

Benchmark Explorer: Confronto interattivo delle prestazioni tra GPTK 3 e GPTK 4 su risoluzioni 1080p, 1440p e 4K.

Supporto Multilingua: Interfaccia completa in Italiano ed Inglese.

🇬🇧 Project Overview

Apple GPTK 4 Lab provides an interactive testbed to benchmark and understand DirectX 12 to Metal 4 translation bottlenecks on Apple Silicon.

🛠️ Tecno Stack / Technologies

HTML5 / Canvas API

Tailwind CSS (via CDN)

JavaScript (ES6+)

Chart.js

FontAwesome 6

🚀 Avvio Rapido / Quick Start

Non è richiesta alcuna installazione di pacchetti o server di build.

Clona il repository:

git clone https://github.com/username/gptk4-lab-simulator.git


Apri il file index.html direttamente in qualsiasi browser moderno (Safari, Chrome, Firefox, Edge).

📜 Licenza e Copyright

Questo progetto è distribuito sotto licenza MIT.

Copyright (c) 2026 Danilo Otupacca. Tutti i diritti riservati.

Per maggiori dettagli consulta il file LICENSE.
