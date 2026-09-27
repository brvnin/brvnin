<!--
  ================================================================
  BRVNIN // DARK NOIR SPECIFICATION FILE
  Classification: CONFIDENTIAL // RAW SIGNAL
  ================================================================
-->

<div align="center">

<!-- Dark Noir Graphic Header: Animated Cyber Emblem & Scanline Matrix -->
<svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" style="background: #0d1117; border-radius: 6px; border: 1px solid #21262d;">
  <defs>
    <!-- CRT Grid Pattern -->
    <pattern id="crtGrid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#161b22" stroke-width="1"/>
    </pattern>
    <!-- Glow Filters -->
    <filter id="noirGlowWhite" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur" />
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="noirGlowSubtle">
      <feGaussianBlur stdDeviation="1" result="blur" />
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background Grid -->
  <rect width="800" height="200" fill="#000000" />
  <rect width="800" height="200" fill="url(#crtGrid)" opacity="0.6"/>

  <!-- Scanning Sweep Beam Animation -->
  <rect x="0" y="0" width="800" height="2" fill="#ffffff" opacity="0.15">
    <animate attributeName="y" dur="4s" repeatCount="indefinite" values="0;200;0" />
  </rect>

  <!-- Central Graphic: Cyber Skull & Circuit Core -->
  <g transform="translate(400, 95)" filter="url(#noirGlowWhite)">
    <!-- Outer Hexagon Frame -->
    <polygon points="0,-65 56,-32 56,32 0,65 -56,32 -56,-32" fill="none" stroke="#30363d" stroke-width="2"/>
    <polygon points="0,-58 50,-29 50,29 0,58 -50,29 -50,-29" fill="none" stroke="#8b949e" stroke-width="1" stroke-dasharray="4,2"/>

    <!-- Orbital Radar Ring -->
    <circle cx="0" cy="0" r="75" fill="none" stroke="#21262d" stroke-width="1.5" stroke-dasharray="10, 30, 5, 30">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="0" r="85" fill="none" stroke="#161b22" stroke-width="1" stroke-dasharray="4, 15">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="15s" repeatCount="indefinite"/>
    </circle>

    <!-- Stylized Dark Skull Vector -->
    <!-- Cranium -->
    <path d="M -22 -15 C -25 -40, 25 -40, 22 -15 C 26 0, 20 15, 14 18 L 14 26 L -14 26 L -14 18 C -20 15, -26 0, -22 -15 Z" fill="#0d1117" stroke="#ffffff" stroke-width="2"/>
    <!-- Eye Sockets (Glowing) -->
    <circle cx="-9" cy="-5" r="5" fill="#ffffff" filter="url(#noirGlowWhite)">
      <animate attributeName="opacity" dur="2.5s" repeatCount="indefinite" values="1;0.2;1;0.9;0.3;1" />
    </circle>
    <circle cx="9" cy="-5" r="5" fill="#ffffff" filter="url(#noirGlowWhite)">
      <animate attributeName="opacity" dur="2.5s" repeatCount="indefinite" values="1;0.2;1;0.9;0.3;1" />
    </circle>
    <!-- Nasal Cavity -->
    <polygon points="0,5 -3,11 3,11" fill="#8b949e"/>
    <!-- Teeth Grid -->
    <line x1="-9" y1="21" x2="-9" y2="26" stroke="#ffffff" stroke-width="1.5"/>
    <line x1="-3" y1="21" x2="-3" y2="26" stroke="#ffffff" stroke-width="1.5"/>
    <line x1="3" y1="21" x2="3" y2="26" stroke="#ffffff" stroke-width="1.5"/>
    <line x1="9" y1="21" x2="9" y2="26" stroke="#ffffff" stroke-width="1.5"/>
  </g>

  <!-- Left & Right Nodes Data Lines -->
  <!-- Left Side Circuit -->
  <path d="M 50 95 L 220 95 L 260 95" fill="none" stroke="#30363d" stroke-width="1.5"/>
  <circle cx="50" cy="95" r="4" fill="#8b949e"/>
  <circle cx="140" cy="95" r="2" fill="#ffffff">
    <animate attributeName="cx" dur="2s" repeatCount="indefinite" values="50;340" />
  </circle>

  <!-- Right Side Circuit -->
  <path d="M 750 95 L 580 95 L 540 95" fill="none" stroke="#30363d" stroke-width="1.5"/>
  <circle cx="750" cy="95" r="4" fill="#8b949e"/>
  <circle cx="750" cy="95" r="2" fill="#ffffff">
    <animate attributeName="cx" dur="2s" repeatCount="indefinite" values="750;460" />
  </circle>

  <!-- Corner Tech Markers -->
  <text x="25" y="35" fill="#484f58" font-family="monospace" font-size="10" letter-spacing="2">[ CORE_ID: 0x4080 ]</text>
  <text x="775" y="35" text-anchor="end" fill="#484f58" font-family="monospace" font-size="10" letter-spacing="2">[ MEMORY_STATE: LOCKED ]</text>
  <text x="25" y="175" fill="#30363d" font-family="monospace" font-size="9">0000 0001 0111 0000 0100 0000 1000 0000</text>
  <text x="775" y="175" text-anchor="end" fill="#30363d" font-family="monospace" font-size="9">// NOIR NOISE GENERATOR</text>
</svg>

  <sub><code>[ SYSTEM STATUS: OPERATIONAL ] // [ CLEARANCE: LEVEL-5 ] // [ LOC: 0x00 ]</code></sub>

  <br/><br/>

  <!-- Dark Noir Animated Typing Signal -->
  <a href="#">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&pause=1200&color=6E7681&center=true&vCenter=true&width=600&lines=Subject%3A+BRVNIN.+Signal+origin%3A+deep+memory.;No+scaffolding.+No+noise.+Direct+hardware+execution.;" alt="Dark Noir Signal" />
  </a>

</div>

<br/>

---

### `[01] // CLASSIFIED_PROFILE`

```yaml
SUBJECT     : brvnin (dj)
STATUS      : Active in the shadows
CORE        : Low-Level Engineering / Binary Dissection / Kernel Space
OPERATING   : Bare Metal / Reverse Engineering / Offensive Tooling

PHILOSOPHY  : "The surface is for strangers. The truth lives behind the metal."
```

<br/>

### `[02] // SYSTEM_CAPABILITIES`

```text
[+] ARCHITECTURE & SYSTEMS
    ├── x86_64 Assembly / Win32 API / NT Internals
    ├── Kernel Drivers & Memory Manipulation
    └── Custom Shellcode & Low-Level Process Control

[+] LANGUAGES & TOOLCHAIN
    ├── C / C++ / Rust
    ├── Python (Automation & Prototyping)
    └── IDA Pro / x64dbg / Ghidra / Windbg
```

<br/>

---

### `[03] // NOIR_TELEMETRY`

<div align="center">

  <!-- Monochromatic Minimalist Stats (Custom Black & Lead Palette) -->
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=brvnin&show_icons=true&bg_color=000000&title_color=ffffff&text_color=8b949e&icon_color=484f58&hide_border=true" alt="Telemetry Stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=brvnin&layout=compact&bg_color=000000&title_color=ffffff&text_color=8b949e&hide_border=true" alt="Languages"/>

</div>

<br/>

---

### `[04] // THE_PULSE (TERMINAL SIGNAL ANIMATION)`

<!-- Custom SVG Dark Noir Radar / Audio Pulse Animation -->
<div align="center">

<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg" style="background: #000000; border-radius: 4px;">
  <defs>
    <linearGradient id="noirGlow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#161616" stop-opacity="0.2"/>
      <stop offset="50%" stop-color="#8b949e" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#161616" stop-opacity="0.2"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="1.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Dark Grid Lines -->
  <line x1="0" y1="60" x2="800" y2="60" stroke="#161b22" stroke-width="1" stroke-dasharray="4,4"/>
  <line x1="400" y1="0" x2="400" y2="120" stroke="#161b22" stroke-width="1" stroke-dasharray="4,4"/>

  <!-- Animated Wave Pulse 1 -->
  <path fill="none" stroke="url(#noirGlow)" stroke-width="2" filter="url(#glow)">
    <animate attributeName="d" 
      dur="4s" 
      repeatCount="indefinite"
      values="
        M 0 60 Q 100 60 200 60 T 400 60 T 600 60 T 800 60;
        M 0 60 Q 100 20 200 100 T 400 30 T 600 90 T 800 60;
        M 0 60 Q 100 90 200 30 T 400 90 T 600 20 T 800 60;
        M 0 60 Q 100 60 200 60 T 400 60 T 600 60 T 800 60
      " />
  </path>

  <!-- Scanning Dot Line -->
  <circle cx="400" cy="60" r="3" fill="#ffffff" filter="url(#glow)">
    <animate attributeName="cx" dur="3s" repeatCount="indefinite" values="0;800;0" />
    <animate attributeName="opacity" dur="3s" repeatCount="indefinite" values="0.2;1;0.2" />
  </circle>

  <!-- Text Overlay in Noir style -->
  <text x="50%" y="95" text-anchor="middle" fill="#484f58" font-family="monospace" font-size="10" letter-spacing="3">
    [ SIGNAL_LOCK // 0x4080 // STANDBY ]
  </text>
</svg>

</div>

<br/>

<div align="center">
  <sub><code>EOF // BRVNIN NEST ARCHITECTURE</code></sub>
</div>
