<!-- 🚀 HYPER-SPACE COMMANDER HUD - DICKY RAHMAT FURQON 🚀 -->

<div align="center">

<!-- ═══════════════════ 3D SPACE COCKPIT HEADER ═══════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" width="900" height="400" viewBox="0 0 900 400">
  <defs>
    <radialGradient id="deep_space" cx="50%" cy="50%" r="70%">
      <stop offset="0%" stop-color="#1a0005"/>
      <stop offset="100%" stop-color="#050001"/>
    </radialGradient>
    <radialGradient id="nebula_red" cx="25%" cy="35%" r="40%">
      <stop offset="0%" stop-color="#FF0000" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#050001" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="nebula_crim" cx="80%" cy="65%" r="35%">
      <stop offset="0%" stop-color="#DC143C" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#050001" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="mars" cx="38%" cy="32%" r="50%">
      <stop offset="0%" stop-color="#FF5555"/>
      <stop offset="35%" stop-color="#CC0000"/>
      <stop offset="70%" stop-color="#8B0000"/>
      <stop offset="100%" stop-color="#2D0000"/>
    </radialGradient>
    <radialGradient id="moon" cx="40%" cy="30%" r="50%">
      <stop offset="0%" stop-color="#FF8888"/>
      <stop offset="100%" stop-color="#550000"/>
    </radialGradient>
    <filter id="neon">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="soft">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="scanline" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#FF000000"/>
      <stop offset="48%" stop-color="#FF000000"/>
      <stop offset="50%" stop-color="#FF000018"/>
      <stop offset="52%" stop-color="#FF000000"/>
      <stop offset="100%" stop-color="#FF000000"/>
    </linearGradient>
  </defs>

  <!-- BG -->
  <rect width="900" height="400" fill="url(#deep_space)"/>
  <rect width="900" height="400" fill="url(#nebula_red)"/>
  <rect width="900" height="400" fill="url(#nebula_crim)"/>

  <!-- SCANLINE EFFECT -->
  <rect width="900" height="400" fill="url(#scanline)" opacity="0.5">
    <animateTransform attributeName="transform" type="translate" values="0,-400;0,400" dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- ★ STAR FIELD (60+ stars, 3 layers) ★ -->
  <g fill="#FFF" opacity="0.5">
    <circle cx="32" cy="18" r="0.7"><animate attributeName="opacity" values="0.2;1;0.2" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="88" cy="55" r="0.5"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="145" cy="30" r="0.8"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="4.1s" repeatCount="indefinite"/></circle>
    <circle cx="210" cy="72" r="0.6"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="278" cy="15" r="0.7"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.6s" repeatCount="indefinite"/></circle>
    <circle cx="340" cy="48" r="0.5"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.9s" repeatCount="indefinite"/></circle>
    <circle cx="405" cy="22" r="0.8"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="4.4s" repeatCount="indefinite"/></circle>
    <circle cx="468" cy="65" r="0.6"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" repeatCount="indefinite"/></circle>
    <circle cx="535" cy="35" r="0.7"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="3.8s" repeatCount="indefinite"/></circle>
    <circle cx="598" cy="58" r="0.5"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.6s" repeatCount="indefinite"/></circle>
    <circle cx="660" cy="20" r="0.8"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="4.2s" repeatCount="indefinite"/></circle>
    <circle cx="725" cy="42" r="0.6"><animate attributeName="opacity" values="0.6;1;0.6" dur="3.3s" repeatCount="indefinite"/></circle>
    <circle cx="790" cy="68" r="0.7"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="2.7s" repeatCount="indefinite"/></circle>
    <circle cx="855" cy="25" r="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="4.0s" repeatCount="indefinite"/></circle>
    <circle cx="55" cy="130" r="0.6"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.4s" repeatCount="indefinite"/></circle>
    <circle cx="160" cy="155" r="0.7"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="300" cy="120" r="0.5"><animate attributeName="opacity" values="0.6;0.9;0.6" dur="4.6s" repeatCount="indefinite"/></circle>
    <circle cx="440" cy="145" r="0.8"><animate attributeName="opacity" values="0.2;1;0.2" dur="3.1s" repeatCount="indefinite"/></circle>
    <circle cx="580" cy="115" r="0.6"><animate attributeName="opacity" values="0.5;0.8;0.5" dur="3.9s" repeatCount="indefinite"/></circle>
    <circle cx="710" cy="140" r="0.7"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.4s" repeatCount="indefinite"/></circle>
    <circle cx="840" cy="150" r="0.5"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="4.3s" repeatCount="indefinite"/></circle>
    <circle cx="75" cy="240" r="0.8"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="3.7s" repeatCount="indefinite"/></circle>
    <circle cx="200" cy="260" r="0.6"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="330" cy="230" r="0.7"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="520" cy="250" r="0.5"><animate attributeName="opacity" values="0.6;1;0.6" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="650" cy="235" r="0.8"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="2.6s" repeatCount="indefinite"/></circle>
    <circle cx="810" cy="255" r="0.6"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="45" cy="340" r="0.7"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="4.0s" repeatCount="indefinite"/></circle>
    <circle cx="185" cy="360" r="0.5"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.9s" repeatCount="indefinite"/></circle>
    <circle cx="370" cy="345" r="0.8"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.6s" repeatCount="indefinite"/></circle>
    <circle cx="500" cy="370" r="0.6"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.2s" repeatCount="indefinite"/></circle>
    <circle cx="620" cy="350" r="0.7"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="4.1s" repeatCount="indefinite"/></circle>
    <circle cx="760" cy="365" r="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="3.3s" repeatCount="indefinite"/></circle>
    <circle cx="880" cy="340" r="0.8"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="2.7s" repeatCount="indefinite"/></circle>
  </g>

  <!-- RED-TINTED STARS -->
  <g fill="#FF4444" opacity="0.4">
    <circle cx="110" cy="95" r="1.0"><animate attributeName="opacity" values="0.2;0.6;0.2" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="380" cy="85" r="0.9"><animate attributeName="opacity" values="0.3;0.7;0.3" dur="4.2s" repeatCount="indefinite"/></circle>
    <circle cx="620" cy="165" r="1.1"><animate attributeName="opacity" values="0.2;0.5;0.2" dur="5.5s" repeatCount="indefinite"/></circle>
    <circle cx="240" cy="310" r="0.9"><animate attributeName="opacity" values="0.3;0.6;0.3" dur="4.8s" repeatCount="indefinite"/></circle>
    <circle cx="690" cy="300" r="1.0"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="5.2s" repeatCount="indefinite"/></circle>
  </g>

  <!-- BRIGHT ACCENT STARS -->
  <g filter="url(#soft)">
    <circle cx="250" cy="50" r="1.5" fill="#FF4444"><animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="550" cy="30" r="1.8" fill="#FFFFFF"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="130" cy="195" r="1.3" fill="#FF6666"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="820" cy="200" r="1.6" fill="#FFFFFF"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="400" cy="350" r="1.4" fill="#FF4444"><animate attributeName="opacity" values="0.4;1;0.4" dur="4.5s" repeatCount="indefinite"/></circle>
  </g>

  <!-- 🪐 MAIN PLANET (Mars - 3D shading) -->
  <g>
    <circle cx="760" cy="130" r="65" fill="url(#mars)" opacity="0.95">
      <animate attributeName="cy" values="130;136;130" dur="8s" repeatCount="indefinite"/>
    </circle>
    <!-- Planet surface details -->
    <circle cx="745" cy="115" r="8" fill="#AA0000" opacity="0.3">
      <animate attributeName="cy" values="115;121;115" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="775" cy="140" r="12" fill="#990000" opacity="0.2">
      <animate attributeName="cy" values="140;146;140" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="150" r="6" fill="#880000" opacity="0.25">
      <animate attributeName="cy" values="150;156;150" dur="8s" repeatCount="indefinite"/>
    </circle>
    <!-- Ring system (3D dual rings) -->
    <ellipse cx="760" cy="130" rx="100" ry="20" fill="none" stroke="#FF444450" stroke-width="4" transform="rotate(-18, 760, 130)">
      <animate attributeName="cy" values="130;136;130" dur="8s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="760" cy="130" rx="90" ry="16" fill="none" stroke="#FF000030" stroke-width="2" transform="rotate(-18, 760, 130)">
      <animate attributeName="cy" values="130;136;130" dur="8s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Atmosphere glow -->
    <circle cx="760" cy="130" r="72" fill="none" stroke="#FF000020" stroke-width="6">
      <animate attributeName="cy" values="130;136;130" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.1;0.35;0.1" dur="4s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- 🌑 SMALL MOON -->
  <g>
    <circle cx="100" cy="310" r="18" fill="url(#moon)" opacity="0.75">
      <animate attributeName="cx" values="100;107;100" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="310;303;310" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="100" cy="310" r="22" fill="none" stroke="#FF000015" stroke-width="3">
      <animate attributeName="cx" values="100;107;100" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="310;303;310" dur="12s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- ☄️ SHOOTING STAR 1 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;0.8;0.8;0" dur="7s" repeatCount="indefinite" begin="1s"/>
    <line x1="700" y1="20" x2="660" y2="35" stroke="#FF6666" stroke-width="1.5" stroke-linecap="round">
      <animate attributeName="x1" values="850;150" dur="1.8s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="y1" values="0;140" dur="1.8s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="x2" values="820;120" dur="1.8s" repeatCount="indefinite" begin="3s"/>
      <animate attributeName="y2" values="8;148" dur="1.8s" repeatCount="indefinite" begin="3s"/>
    </line>
  </g>

  <!-- ☄️ SHOOTING STAR 2 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;0;0.7;0.7;0" dur="9s" repeatCount="indefinite" begin="5s"/>
    <line x1="300" y1="10" x2="270" y2="22" stroke="#FF4444" stroke-width="1" stroke-linecap="round">
      <animate attributeName="x1" values="900;200" dur="2s" repeatCount="indefinite" begin="7s"/>
      <animate attributeName="y1" values="5;180" dur="2s" repeatCount="indefinite" begin="7s"/>
      <animate attributeName="x2" values="870;170" dur="2s" repeatCount="indefinite" begin="7s"/>
      <animate attributeName="y2" values="12;187" dur="2s" repeatCount="indefinite" begin="7s"/>
    </line>
  </g>

  <!-- 🚀 ROCKET WITH FLAME -->
  <g transform="translate(85, 70) rotate(-45)" opacity="0.8">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" values="85,70;90,64;85,70" dur="6s" repeatCount="indefinite"/>
    <path d="M0,18 L6,0 L12,18 L10,18 L10,26 L2,26 L2,18 Z" fill="#FF3333"/>
    <circle cx="6" cy="11" r="2.5" fill="#FF9999"/>
    <path d="M2,26 L6,36 L10,26" fill="#FF0000">
      <animate attributeName="d" values="M2,26 L6,36 L10,26;M2,26 L6,42 L10,26;M2,26 L6,36 L10,26" dur="0.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="0.25s" repeatCount="indefinite"/>
    </path>
    <path d="M3,26 L6,32 L9,26" fill="#FFAA00" opacity="0.6">
      <animate attributeName="d" values="M3,26 L6,32 L9,26;M3,26 L6,38 L9,26;M3,26 L6,32 L9,26" dur="0.35s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- ═══ HUD COCKPIT FRAME ═══ -->
  <!-- Corner brackets -->
  <g stroke="#FF0000" stroke-width="2" fill="none" opacity="0.6">
    <!-- Top-left -->
    <path d="M30,30 L30,55 M30,30 L55,30"/>
    <!-- Top-right -->
    <path d="M870,30 L870,55 M870,30 L845,30"/>
    <!-- Bottom-left -->
    <path d="M30,370 L30,345 M30,370 L55,370"/>
    <!-- Bottom-right -->
    <path d="M870,370 L870,345 M870,370 L845,370"/>
  </g>

  <!-- HUD horizontal scan lines -->
  <line x1="30" y1="30" x2="870" y2="30" stroke="#FF000020" stroke-width="1"/>
  <line x1="30" y1="370" x2="870" y2="370" stroke="#FF000020" stroke-width="1"/>

  <!-- HUD top-left status -->
  <g font-family="'Courier New', monospace" fill="#FF000080" font-size="9">
    <text x="38" y="48">SYS://ONLINE</text>
    <text x="38" y="60">
      STATUS: ACTIVE
      <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- HUD top-right status -->
  <g font-family="'Courier New', monospace" fill="#FF000080" font-size="9" text-anchor="end">
    <text x="862" y="48">SECTOR: GITHUB</text>
    <text x="862" y="60">
      SIGNAL: ████████
      <animate attributeName="opacity" values="0.5;1;0.5" dur="1.5s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- ═══ MAIN TITLE ═══ -->
  <g filter="url(#neon)" text-anchor="middle">
    <!-- 3D Shadow -->
    <text x="453" y="178" font-family="'Segoe UI', 'Arial Black', sans-serif" font-size="48" font-weight="900" fill="#3D0000" letter-spacing="6">DICKY RAHMAT</text>
    <text x="453" y="228" font-family="'Segoe UI', 'Arial Black', sans-serif" font-size="48" font-weight="900" fill="#3D0000" letter-spacing="6">FURQON</text>
    <!-- Main text -->
    <text x="450" y="175" font-family="'Segoe UI', 'Arial Black', sans-serif" font-size="48" font-weight="900" fill="#FF0000" letter-spacing="6">
      DICKY RAHMAT
      <animate attributeName="fill" values="#FF0000;#FF3333;#FF0000" dur="3s" repeatCount="indefinite"/>
    </text>
    <text x="450" y="225" font-family="'Segoe UI', 'Arial Black', sans-serif" font-size="48" font-weight="900" fill="#FF0000" letter-spacing="6">
      FURQON
      <animate attributeName="fill" values="#FF0000;#FF3333;#FF0000" dur="3s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- SUBTITLE -->
  <text x="450" y="260" font-family="'Courier New', monospace" font-size="14" fill="#FF6666" text-anchor="middle" letter-spacing="4">
    &#x1F680; FULL STACK DEVELOPER &#x2022; DIGITAL SPACE EXPLORER &#x1F30C;
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- Expanding line -->
  <line x1="320" y1="278" x2="580" y2="278" stroke="#FF0000" stroke-width="1" opacity="0.5">
    <animate attributeName="x1" values="380;320;380" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="520;580;520" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="4s" repeatCount="indefinite"/>
  </line>

  <!-- TECH TAGS -->
  <text x="450" y="300" font-family="'Courier New', monospace" font-size="11" fill="#FF444470" text-anchor="middle" letter-spacing="3">
    PHP &#x2022; LARAVEL &#x2022; VUE.JS &#x2022; JAVASCRIPT &#x2022; MYSQL
  </text>

  <!-- HUD BOTTOM STATUS -->
  <g font-family="'Courier New', monospace" fill="#FF000060" font-size="9">
    <text x="38" y="362">COORDINATES: JAVA, INDONESIA</text>
    <text x="620" y="362">
      &#x25CF; MISSION LOG: BUILDING THE FUTURE
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2.5s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Bottom glow -->
  <line x1="0" y1="399" x2="900" y2="399" stroke="#FF0000" stroke-width="2" opacity="0.5">
    <animate attributeName="opacity" values="0.2;0.7;0.2" dur="3s" repeatCount="indefinite"/>
  </line>
</svg>

<br/>

<!-- ═══════════════════ TYPING ANIMATION ═══════════════════ -->

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=22&duration=2500&pause=1000&color=FF0000&center=true&vCenter=true&repeat=true&width=800&height=50&lines=%F0%9F%94%B4+INITIATING+COSMIC+PROTOCOLS...;%E2%9A%A1+SCANNING+FULL+STACK+GALAXY...;%F0%9F%9B%B8+CONSTRUCTING+DIGITAL+NEBULAS...;%F0%9F%94%A5+SYSTEMS+ONLINE+%E2%80%A2+CODE+DEPLOYED" alt="Typing SVG" />
</a>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

<!-- ═══════════════════ MISSION BRIEFING ═══════════════════ -->

<div align="center">

## ⚡ Mission Briefing — Commander Profile ⚡

</div>

<div align="center">
<table>
<tr>
<td width="55%" align="center">

```js
class SpaceCommander {
    constructor() {
        this.name     = "Dicky Rahmat Furqon";
        this.role     = "Full Stack Developer";
        this.base     = "Java, Indonesia 🇮🇩";
        this.stack    = ["PHP", "Laravel", "Vue.js", 
                         "JavaScript", "MySQL"];
        this.mission  = "Building stellar apps 🚀";
    }

    getCurrentProject() {
        return "🎵 Spotify Clone (Full Stack)";
    }

    getStatus() {
        return "⚡ Systems Online";
    }
}
```

</td>
<td width="45%" align="center">

🔴 **Status**: `SYSTEMS ONLINE`

🚀 **Current Mission**: Spotify Clone

🌌 **Exploring**: Laravel & Vue.js

⭐ **Speciality**: Full Stack Development

🛸 **Base**: Indonesia 🇮🇩

🔥 **Fuel**: Coffee → Code ☕

<br>

<img src="https://komarev.com/ghpvc/?username=furqon2004&style=flat-square&color=FF0000&label=PROFILE+SCANS"/>

</td>
</tr>
</table>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ TECH ARSENAL ═══════════════════ -->

<div align="center">

## 🔴 Tech Arsenal — Weapons of Mass Creation 🔴

<br>

<table>
<tr>
<td align="center" width="50%">

### 🛸 Core Languages

![PHP](https://img.shields.io/badge/PHP-0d0208?style=for-the-badge&logo=php&logoColor=FF0000)
![JavaScript](https://img.shields.io/badge/JavaScript-0d0208?style=for-the-badge&logo=javascript&logoColor=FF0000)
![HTML5](https://img.shields.io/badge/HTML5-0d0208?style=for-the-badge&logo=html5&logoColor=FF0000)
![CSS3](https://img.shields.io/badge/CSS3-0d0208?style=for-the-badge&logo=css3&logoColor=FF0000)

</td>
<td align="center" width="50%">

### 🚀 Frameworks

![Laravel](https://img.shields.io/badge/Laravel-0d0208?style=for-the-badge&logo=laravel&logoColor=FF0000)
![Vue.js](https://img.shields.io/badge/Vue.js-0d0208?style=for-the-badge&logo=vue.js&logoColor=FF0000)
![Bootstrap](https://img.shields.io/badge/Bootstrap-0d0208?style=for-the-badge&logo=bootstrap&logoColor=FF0000)
![jQuery](https://img.shields.io/badge/jQuery-0d0208?style=for-the-badge&logo=jquery&logoColor=FF0000)

</td>
</tr>
<tr>
<td align="center" colspan="2">

### ⭐ Database & Tools

![MySQL](https://img.shields.io/badge/MySQL-0d0208?style=for-the-badge&logo=mysql&logoColor=FF0000)
![Git](https://img.shields.io/badge/Git-0d0208?style=for-the-badge&logo=git&logoColor=FF0000)
![GitHub](https://img.shields.io/badge/GitHub-0d0208?style=for-the-badge&logo=github&logoColor=FF0000)
![VS Code](https://img.shields.io/badge/VS_Code-0d0208?style=for-the-badge&logo=visualstudiocode&logoColor=FF0000)
![Postman](https://img.shields.io/badge/Postman-0d0208?style=for-the-badge&logo=postman&logoColor=FF0000)
![Figma](https://img.shields.io/badge/Figma-0d0208?style=for-the-badge&logo=figma&logoColor=FF0000)

</td>
</tr>
</table>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ MISSION CONTROL STATS ═══════════════════ -->

<div align="center">

## 📊 Mission Control — Intelligence Report 📊

<br>

<table>
<tr>
<td align="center" width="50%">

<a href="https://github.com/furqon2004">
  <img width="400" src="https://github-readme-stats.vercel.app/api?username=furqon2004&show_icons=true&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666&ring_color=FF0000&count_private=true&custom_title=⚡+Commander+Stats"/>
</a>

</td>
<td align="center" width="50%">

<a href="https://github.com/furqon2004">
  <img width="400" src="https://github-readme-stats.vercel.app/api/top-langs/?username=furqon2004&layout=compact&hide_border=true&bg_color=0d0208&title_color=FF0000&text_color=FF6666&custom_title=🔴+Arsenal+Languages"/>
</a>

</td>
</tr>
</table>

<br>

<!-- STREAK -->
<a href="https://github.com/furqon2004">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=furqon2004&hide_border=true&background=0d0208&ring=FF0000&fire=FF4444&currStreakLabel=FF6666&sideLabels=FF4444&currStreakNum=FF0000&sideNums=FF6666&dates=8B0000&stroke=FF000020"/>
</a>

<br><br>

<!-- ACTIVITY GRAPH -->
<a href="https://github.com/furqon2004">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=furqon2004&bg_color=0d0208&color=FF4444&line=FF0000&point=FFFFFF&area_color=FF000040&area=true&hide_border=true&custom_title=🔴%20Mission%20Activity%20Log%20🔴"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ FEATURED MISSIONS ═══════════════════ -->

<div align="center">

## 🛸 Featured Missions — Top Projects 🛸

<br>

<a href="https://github.com/furqon2004/backend-copy-spotify">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=backend-copy-spotify&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/Portfolio.Dicky">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=Portfolio.Dicky&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

<a href="https://github.com/furqon2004/front-end-sistem-antrian-rumah-sakit">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=front-end-sistem-antrian-rumah-sakit&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/marketplaceVue">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=marketplaceVue&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

<a href="https://github.com/furqon2004/web-recipe">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=web-recipe&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/tokoku">
  <img width="400" src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=tokoku&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ TROPHIES ═══════════════════ -->

<div align="center">

## 🏆 Space Achievements 🏆

<br>

<a href="https://github.com/furqon2004">
  <img src="https://github-profile-trophy.vercel.app/?username=furqon2004&theme=radical&no-frame=true&no-bg=true&column=7&margin-w=10&margin-h=10"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ CONNECT ═══════════════════ -->

<div align="center">

## 🌠 Transmission Channel — Connect 🌠

<br>

[![GitHub](https://img.shields.io/badge/GITHUB-0d0208?style=for-the-badge&logo=github&logoColor=FF0000)](https://github.com/furqon2004)
[![Portfolio](https://img.shields.io/badge/PORTFOLIO-0d0208?style=for-the-badge&logo=google-chrome&logoColor=FF0000)](https://github.com/furqon2004/Portfolio.Dicky)

<br><br>

### 🔴 _"In the vast universe of code, every line is a star waiting to shine."_ 🔴

<br>

</div>

<!-- ═══════════════════ FOOTER ═══════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:050001,50:8B0000,100:FF0000&section=footer"/>
