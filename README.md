<svg width="900" height="340" viewBox="0 0 900 340" xmlns="http://www.w3.org/2000/svg" font-family="'Press Start 2P','Courier New',monospace">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&amp;display=swap');
      text { image-rendering: pixelated; }

      @keyframes chipBorderPulse {
        0%   { stroke-width: 2; filter: none; }
        4%   { stroke-width: 4; filter: drop-shadow(0 0 6px currentColor); }
        9%   { stroke-width: 2; filter: none; }
        100% { stroke-width: 2; filter: none; }
      }
      @keyframes chipTopPulse {
        0%   { opacity: 1; filter: none; }
        4%   { opacity: 1; filter: drop-shadow(0 0 5px currentColor); }
        9%   { opacity: 1; filter: none; }
        100% { opacity: 1; filter: none; }
      }
      @keyframes chipTextPulse {
        0%   { fill: #eaeaea; }
        4%   { fill: #ffffff; }
        9%   { fill: #eaeaea; }
        100% { fill: #eaeaea; }
      }
      .chip-border { animation: chipBorderPulse 7.7s linear infinite; }
      .chip-top    { animation: chipTopPulse 7.7s linear infinite; }
      .chip-text   { animation: chipTextPulse 7.7s linear infinite; }
    </style>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f0e23"/>
      <stop offset="100%" stop-color="#1b1035"/>
    </linearGradient>
    <pattern id="scan" width="4" height="4" patternUnits="userSpaceOnUse">
      <rect width="4" height="2" fill="#000000" opacity="0.10"/>
    </pattern>
    <pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#ffffff" stroke-opacity="0.035" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- background -->
  <rect width="900" height="340" fill="url(#bg)"/>
  <rect width="900" height="340" fill="url(#grid)"/>

  <!-- pixel border frame -->
  <rect x="6" y="6" width="888" height="328" fill="none" stroke="#ff2e63" stroke-width="4" shape-rendering="crispEdges"/>
  <rect x="12" y="12" width="876" height="316" fill="none" stroke="#08d9d6" stroke-width="2" shape-rendering="crispEdges" stroke-dasharray="6 4"/>

  <!-- corner brackets -->
  <g stroke="#eaff00" stroke-width="3" fill="none" shape-rendering="crispEdges">
    <path d="M 18 40 L 18 18 L 40 18"/>
    <path d="M 860 18 L 882 18 L 882 40"/>
    <path d="M 18 300 L 18 322 L 40 322"/>
    <path d="M 860 322 L 882 322 L 882 300"/>
  </g>

  <!-- floppy disk pixel icon top-right -->
  <g transform="translate(782,34)" shape-rendering="crispEdges">
    <rect x="0" y="0" width="64" height="64" fill="#08d9d6"/>
    <rect x="8" y="0" width="48" height="16" fill="#0f0e23"/>
    <rect x="14" y="4" width="24" height="8" fill="#eaeaea"/>
    <rect x="10" y="22" width="44" height="34" fill="#eaeaea"/>
    <rect x="16" y="28" width="32" height="20" fill="#1b1035"/>
    <rect x="0" y="0" width="64" height="64" fill="none" stroke="#0f0e23" stroke-width="2"/>
    <animateTransform attributeName="transform" type="translate" values="782,34; 782,30; 782,34" dur="2.4s" repeatCount="indefinite" additive="sum"/>
  </g>

  <!-- greeting -->
  <text x="30" y="58" font-size="13" fill="#08d9d6" letter-spacing="1">&gt; SYSTEM.BOOT()</text>

  <!-- name IVAN pixel style -->
  <text x="28" y="102" font-size="44" fill="#eaff00" letter-spacing="4" style="paint-order: stroke; stroke: #ff2e63; stroke-width: 6;">IVAN</text>
  <text x="28" y="102" font-size="44" fill="#eaff00" letter-spacing="4">IVAN</text>

  <!-- subtitle typing line -->
  <text x="30" y="136" font-size="14" fill="#eaeaea" letter-spacing="0.5">&gt; full-stack developer_<tspan fill="#ff2e63">
    <animate attributeName="opacity" values="1;1;0;0;1" keyTimes="0;0.4;0.5;0.9;1" dur="1.1s" repeatCount="indefinite"/>
  </tspan></text>

  <!-- divider -->
  <line x1="22" y1="152" x2="878" y2="152" stroke="#3a3a52" stroke-width="2" stroke-dasharray="8 6" shape-rendering="crispEdges"/>
  <text x="450.0" y="147" font-size="9" fill="#c792ff" text-anchor="middle">[ TECH_STACK.EXE ]</text>

  <!-- tech chips grid -->
  
    <g transform="translate(22.0,160.0)" style="color:#ff2e63">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff2e63" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:0.0s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff2e63" shape-rendering="crispEdges" style="animation-delay:0.0s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:0.0s">Python</text>
    </g>
    <g transform="translate(130.0,160.0)" style="color:#ff2e63">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff2e63" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:0.35s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff2e63" shape-rendering="crispEdges" style="animation-delay:0.35s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:0.35s">HTML</text>
    </g>
    <g transform="translate(238.0,160.0)" style="color:#ff2e63">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff2e63" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:0.7s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff2e63" shape-rendering="crispEdges" style="animation-delay:0.7s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:0.7s">CSS</text>
    </g>
    <g transform="translate(346.0,160.0)" style="color:#ff2e63">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff2e63" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:1.05s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff2e63" shape-rendering="crispEdges" style="animation-delay:1.05s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="8.3" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:1.05s">JavaScript</text>
    </g>
    <g transform="translate(454.0,160.0)" style="color:#ff2e63">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff2e63" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:1.4s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff2e63" shape-rendering="crispEdges" style="animation-delay:1.4s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="8.3" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:1.4s">TypeScript</text>
    </g>
    <g transform="translate(562.0,160.0)" style="color:#08d9d6">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#08d9d6" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:1.75s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#08d9d6" shape-rendering="crispEdges" style="animation-delay:1.75s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:1.75s">React</text>
    </g>
    <g transform="translate(670.0,160.0)" style="color:#08d9d6">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#08d9d6" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:2.1s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#08d9d6" shape-rendering="crispEdges" style="animation-delay:2.1s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:2.1s">Tailwind</text>
    </g>
    <g transform="translate(778.0,160.0)" style="color:#08d9d6">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#08d9d6" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:2.45s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#08d9d6" shape-rendering="crispEdges" style="animation-delay:2.45s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="8.3" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:2.45s">Bootstrap</text>
    </g>
    <g transform="translate(22.0,212.0)" style="color:#08d9d6">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#08d9d6" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:2.8s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#08d9d6" shape-rendering="crispEdges" style="animation-delay:2.8s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:2.8s">jQuery</text>
    </g>
    <g transform="translate(130.0,212.0)" style="color:#eaff00">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#eaff00" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:3.15s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#eaff00" shape-rendering="crispEdges" style="animation-delay:3.15s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:3.15s">Node.js</text>
    </g>
    <g transform="translate(238.0,212.0)" style="color:#eaff00">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#eaff00" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:3.5s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#eaff00" shape-rendering="crispEdges" style="animation-delay:3.5s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:3.5s">Express</text>
    </g>
    <g transform="translate(346.0,212.0)" style="color:#eaff00">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#eaff00" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:3.85s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#eaff00" shape-rendering="crispEdges" style="animation-delay:3.85s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:3.85s">Flask</text>
    </g>
    <g transform="translate(454.0,212.0)" style="color:#6bff6b">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#6bff6b" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:4.2s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#6bff6b" shape-rendering="crispEdges" style="animation-delay:4.2s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:4.2s">MySQL</text>
    </g>
    <g transform="translate(562.0,212.0)" style="color:#6bff6b">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#6bff6b" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:4.55s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#6bff6b" shape-rendering="crispEdges" style="animation-delay:4.55s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:4.55s">Supabase</text>
    </g>
    <g transform="translate(670.0,212.0)" style="color:#6bff6b">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#6bff6b" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:4.9s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#6bff6b" shape-rendering="crispEdges" style="animation-delay:4.9s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="8.3" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:4.9s">PostgreSQL</text>
    </g>
    <g transform="translate(778.0,212.0)" style="color:#ff9f1c">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff9f1c" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:5.25s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff9f1c" shape-rendering="crispEdges" style="animation-delay:5.25s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:5.25s">Docker</text>
    </g>
    <g transform="translate(130.0,264.0)" style="color:#ff9f1c">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff9f1c" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:5.6s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff9f1c" shape-rendering="crispEdges" style="animation-delay:5.6s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:5.6s">Git</text>
    </g>
    <g transform="translate(238.0,264.0)" style="color:#ff9f1c">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#ff9f1c" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:5.95s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#ff9f1c" shape-rendering="crispEdges" style="animation-delay:5.95s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:5.95s">Linux</text>
    </g>
    <g transform="translate(346.0,264.0)" style="color:#c792ff">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#c792ff" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:6.3s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#c792ff" shape-rendering="crispEdges" style="animation-delay:6.3s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:6.3s">GraphQL</text>
    </g>
    <g transform="translate(454.0,264.0)" style="color:#c792ff">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#c792ff" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:6.65s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#c792ff" shape-rendering="crispEdges" style="animation-delay:6.65s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:6.65s">REST API</text>
    </g>
    <g transform="translate(562.0,264.0)" style="color:#c792ff">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#c792ff" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:7.0s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#c792ff" shape-rendering="crispEdges" style="animation-delay:7.0s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:7.0s">VS Code</text>
    </g>
    <g transform="translate(670.0,264.0)" style="color:#c792ff">
      <rect class="chip-border" x="0" y="0" width="100.0" height="42" fill="#15152b" stroke="#c792ff" stroke-width="2" shape-rendering="crispEdges" style="animation-delay:7.35s"/>
      <rect class="chip-top" x="3" y="3" width="94.0" height="4" fill="#c792ff" shape-rendering="crispEdges" style="animation-delay:7.35s"/>
      <text class="chip-text" x="50.0" y="30.0" font-family="'Press Start 2P','Courier New',monospace" font-size="10" fill="#eaeaea" text-anchor="middle" letter-spacing="0.5" style="animation-delay:7.35s">Postman</text>
    </g>

  <!-- footer scanline -->
  <rect width="900" height="340" fill="url(#scan)"/>
</svg>
