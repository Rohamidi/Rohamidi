<svg width="900" height="300" viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">
  <defs>

    <!-- Background gradient: deep navy -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#060B18"/>
      <stop offset="45%"  stop-color="#0A1628"/>
      <stop offset="100%" stop-color="#060B18"/>
    </linearGradient>

    <!-- Blue orb left -->
    <radialGradient id="orb1" cx="25%" cy="45%" r="50%">
      <stop offset="0%"   stop-color="#1565C0" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#060B18" stop-opacity="0"/>
    </radialGradient>

    <!-- Blue orb right -->
    <radialGradient id="orb2" cx="78%" cy="55%" r="40%">
      <stop offset="0%"   stop-color="#0288D1" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#060B18" stop-opacity="0"/>
    </radialGradient>

    <!-- Glass card fill -->
    <linearGradient id="glassFill" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#FFFFFF" stop-opacity="0.07"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0.02"/>
    </linearGradient>

    <!-- Top border shimmer -->
    <linearGradient id="shimmer" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#1E88E5" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#42A5F5" stop-opacity="1"/>
      <stop offset="70%"  stop-color="#29B6F6" stop-opacity="1"/>
      <stop offset="100%" stop-color="#29B6F6" stop-opacity="0"/>
    </linearGradient>

    <!-- Bottom border shimmer (dimmer) -->
    <linearGradient id="shimmerBottom" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#1E88E5" stop-opacity="0"/>
      <stop offset="40%"  stop-color="#1E88E5" stop-opacity="0.3"/>
      <stop offset="60%"  stop-color="#1E88E5" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#1E88E5" stop-opacity="0"/>
    </linearGradient>

    <!-- Name text glow -->
    <filter id="nameGlow" x="-20%" y="-40%" width="140%" height="180%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Subtle drop shadow for card -->
    <filter id="cardShadow" x="-5%" y="-5%" width="110%" height="120%">
      <feDropShadow dx="0" dy="8" stdDeviation="20" flood-color="#1565C0" flood-opacity="0.3"/>
    </filter>

    <!-- Tag pill gradient -->
    <linearGradient id="tagGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#1565C0" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#0288D1" stop-opacity="0.15"/>
    </linearGradient>

    <style>
      .a-fade  { animation: fadeUp 1.2s cubic-bezier(.4,0,.2,1) both; }
      .a-fade2 { animation: fadeUp 1.2s cubic-bezier(.4,0,.2,1) 0.25s both; }
      .a-fade3 { animation: fadeUp 1.2s cubic-bezier(.4,0,.2,1) 0.45s both; }
      .a-fade4 { animation: fadeUp 1.2s cubic-bezier(.4,0,.2,1) 0.65s both; }
      .pulse   { animation: pulse 4s ease-in-out infinite; }
      .pulse2  { animation: pulse 4s ease-in-out 2s infinite; }
      .blink   { animation: blink 1.1s step-end infinite; }
      .scan    { animation: scan 3s linear infinite; }

      @keyframes fadeUp {
        from { opacity:0; transform:translateY(14px); }
        to   { opacity:1; transform:translateY(0); }
      }
      @keyframes pulse {
        0%,100% { opacity:.35; }
        50%      { opacity:.75; }
      }
      @keyframes blink {
        0%,100% { opacity:1; }
        50%     { opacity:0; }
      }
      @keyframes scan {
        0%   { transform:translateY(-10px); opacity:0; }
        10%  { opacity:1; }
        90%  { opacity:.4; }
        100% { transform:translateY(210px); opacity:0; }
      }
    </style>
  </defs>

  <!-- ── BACKGROUND ── -->
  <rect width="900" height="300" fill="url(#bg)"/>
  <rect width="900" height="300" fill="url(#orb1)"/>
  <rect width="900" height="300" fill="url(#orb2)"/>

  <!-- ── SUBTLE GRID ── -->
  <!-- horizontals -->
  <line x1="0" y1="75"  x2="900" y2="75"  stroke="#2979FF" stroke-opacity=".045" stroke-width="1"/>
  <line x1="0" y1="150" x2="900" y2="150" stroke="#2979FF" stroke-opacity=".045" stroke-width="1"/>
  <line x1="0" y1="225" x2="900" y2="225" stroke="#2979FF" stroke-opacity=".045" stroke-width="1"/>
  <!-- verticals -->
  <line x1="112" y1="0" x2="112" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="225" y1="0" x2="225" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="337" y1="0" x2="337" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="450" y1="0" x2="450" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="562" y1="0" x2="562" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="675" y1="0" x2="675" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>
  <line x1="787" y1="0" x2="787" y2="300" stroke="#2979FF" stroke-opacity=".04" stroke-width="1"/>

  <!-- ── SCAN LINE (moves top→bottom) ── -->
  <rect x="55" y="0" width="790" height="1.5" fill="url(#shimmer)" opacity=".45" class="scan"/>

  <!-- ── GLASS CARD ── -->
  <rect x="55" y="38" width="790" height="224" rx="18"
        fill="url(#glassFill)"
        stroke="#FFFFFF" stroke-opacity=".09" stroke-width="1"
        filter="url(#cardShadow)"/>

  <!-- top shimmer border -->
  <rect x="55" y="38" width="790" height="1.5" rx="1" fill="url(#shimmer)" opacity=".9"/>
  <!-- bottom dim border -->
  <rect x="55" y="261" width="790" height="1"   rx="1" fill="url(#shimmerBottom)"/>

  <!-- ── CORNER BRACKETS ── -->
  <!-- top-left -->
  <path d="M55,70 L55,38 L90,38"   stroke="#42A5F5" stroke-width="2.5" fill="none" stroke-linecap="round" opacity=".8"/>
  <!-- top-right -->
  <path d="M845,70 L845,38 L810,38" stroke="#42A5F5" stroke-width="2.5" fill="none" stroke-linecap="round" opacity=".8"/>
  <!-- bottom-left -->
  <path d="M55,230 L55,262 L90,262"   stroke="#42A5F5" stroke-width="2.5" fill="none" stroke-linecap="round" opacity=".8"/>
  <!-- bottom-right -->
  <path d="M845,230 L845,262 L810,262" stroke="#42A5F5" stroke-width="2.5" fill="none" stroke-linecap="round" opacity=".8"/>

  <!-- corner dots -->
  <circle cx="55"  cy="38"  r="3.5" fill="#42A5F5" opacity=".7"/>
  <circle cx="845" cy="38"  r="3.5" fill="#42A5F5" opacity=".7"/>
  <circle cx="55"  cy="262" r="3.5" fill="#42A5F5" opacity=".7"/>
  <circle cx="845" cy="262" r="3.5" fill="#42A5F5" opacity=".7"/>

  <!-- ── WINDOW DOTS (iOS/macOS style) ── -->
  <circle cx="88"  cy="58" r="4.5" fill="#FF5F57" opacity=".85"/>
  <circle cx="106" cy="58" r="4.5" fill="#FEBC2E" opacity=".85"/>
  <circle cx="124" cy="58" r="4.5" fill="#28C840" opacity=".85"/>

  <!-- terminal label -->
  <text x="160" y="63" font-family="'Courier New', monospace" font-size="11.5"
        fill="#42A5F5" opacity=".6" letter-spacing="1">root@github ~ %</text>

  <!-- ── NAME ── -->
  <text x="450" y="138" text-anchor="middle"
        font-family="'Helvetica Neue', 'Segoe UI', Arial, sans-serif"
        font-weight="700" font-size="46" letter-spacing="-0.5"
        fill="#FFFFFF" filter="url(#nameGlow)"
        class="a-fade">Roham Hamidi</text>

  <!-- blue accent line under name -->
  <rect x="310" y="148" width="280" height="2" rx="1" fill="url(#shimmer)" class="a-fade2"/>

  <!-- ── SUBTITLE ── -->
  <text x="450" y="178" text-anchor="middle"
        font-family="'Courier New', monospace"
        font-size="13.5" letter-spacing="2.5"
        fill="#90CAF9" class="a-fade2">Python · Cybersecurity · Software Development</text>

  <!-- ── PILL TAGS ── -->
  <!-- Tbilisi -->
  <rect x="188" y="198" width="102" height="24" rx="12"
        fill="url(#tagGrad)" stroke="#42A5F5" stroke-opacity=".35" stroke-width="1"
        class="a-fade3"/>
  <text x="239" y="214" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#90CAF9" class="a-fade3">📍 Tbilisi, GE</text>

  <!-- Security -->
  <rect x="304" y="198" width="90" height="24" rx="12"
        fill="url(#tagGrad)" stroke="#42A5F5" stroke-opacity=".35" stroke-width="1"
        class="a-fade3"/>
  <text x="349" y="214" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#90CAF9" class="a-fade3">🔒 Security</text>

  <!-- Python -->
  <rect x="408" y="198" width="84" height="24" rx="12"
        fill="url(#tagGrad)" stroke="#42A5F5" stroke-opacity=".35" stroke-width="1"
        class="a-fade4"/>
  <text x="450" y="214" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#90CAF9" class="a-fade4">🐍 Python</text>

  <!-- Automation -->
  <rect x="506" y="198" width="100" height="24" rx="12"
        fill="url(#tagGrad)" stroke="#42A5F5" stroke-opacity=".35" stroke-width="1"
        class="a-fade4"/>
  <text x="556" y="214" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#90CAF9" class="a-fade4">⚡ Automation</text>

  <!-- ── BOTTOM TERMINAL LINE ── -->
  <text x="88" y="248" font-family="'Courier New', monospace" font-size="12"
        fill="#42A5F5" opacity=".5">$</text>
  <text x="100" y="248" font-family="'Courier New', monospace" font-size="12"
        fill="#64B5F6" opacity=".7">Build. Learn. Improve. Repeat.</text>
  <text x="400" y="248" font-family="'Courier New', monospace" font-size="12"
        fill="#42A5F5" opacity=".9" class="blink">▌</text>

  <!-- ── FLOATING AMBIENT DOTS ── -->
  <circle cx="28"  cy="60"  r="2" fill="#42A5F5" opacity=".3" class="pulse"/>
  <circle cx="28"  cy="150" r="2" fill="#1E88E5" opacity=".2" class="pulse2"/>
  <circle cx="28"  cy="240" r="2" fill="#42A5F5" opacity=".3" class="pulse"/>
  <circle cx="872" cy="60"  r="2" fill="#29B6F6" opacity=".3" class="pulse2"/>
  <circle cx="872" cy="150" r="2" fill="#42A5F5" opacity=".2" class="pulse"/>
  <circle cx="872" cy="240" r="2" fill="#29B6F6" opacity=".3" class="pulse2"/>

</svg>
