<!-- 🚀 3D SPACE THEMED GITHUB PROFILE - DICKY RAHMAT FURQON 🚀 -->

<div align="center">

<!-- ═══════════════════ 3D ANIMATED SPACE HEADER SVG ═══════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" width="900" height="350" viewBox="0 0 900 350">
  <defs>
    <!-- Radial glow for nebula -->
    <radialGradient id="nebula1" cx="20%" cy="40%" r="35%">
      <stop offset="0%" stop-color="#FF0000" stop-opacity="0.3"/>
      <stop offset="50%" stop-color="#8B0000" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#0d0208" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="nebula2" cx="75%" cy="60%" r="30%">
      <stop offset="0%" stop-color="#FF4444" stop-opacity="0.25"/>
      <stop offset="50%" stop-color="#B22222" stop-opacity="0.1"/>
      <stop offset="100%" stop-color="#0d0208" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="nebula3" cx="50%" cy="25%" r="25%">
      <stop offset="0%" stop-color="#FF6666" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#0d0208" stop-opacity="0"/>
    </radialGradient>
    <!-- Planet gradient -->
    <radialGradient id="planet" cx="40%" cy="35%" r="50%">
      <stop offset="0%" stop-color="#FF4444"/>
      <stop offset="60%" stop-color="#8B0000"/>
      <stop offset="100%" stop-color="#3D0000"/>
    </radialGradient>
    <!-- Small planet -->
    <radialGradient id="planet2" cx="35%" cy="30%" r="50%">
      <stop offset="0%" stop-color="#FF6666"/>
      <stop offset="100%" stop-color="#660000"/>
    </radialGradient>
    <!-- Text glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Deep space background -->
  <rect width="900" height="350" fill="#0d0208"/>

  <!-- Nebula layers -->
  <rect width="900" height="350" fill="url(#nebula1)"/>
  <rect width="900" height="350" fill="url(#nebula2)"/>
  <rect width="900" height="350" fill="url(#nebula3)"/>

  <!-- ★ Star field - Layer 1 (distant, small) ★ -->
  <g fill="#FFFFFF" opacity="0.6">
    <circle cx="45" cy="30" r="0.8"><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="120" cy="80" r="0.6"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="200" cy="45" r="0.7"><animate attributeName="opacity" values="0.4;1;0.4" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="310" cy="25" r="0.5"><animate attributeName="opacity" values="0.6;1;0.6" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="420" cy="70" r="0.8"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="530" cy="35" r="0.6"><animate attributeName="opacity" values="0.5;1;0.5" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="640" cy="55" r="0.7"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="4.2s" repeatCount="indefinite"/></circle>
    <circle cx="750" cy="40" r="0.5"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.6s" repeatCount="indefinite"/></circle>
    <circle cx="830" cy="75" r="0.8"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.8s" repeatCount="indefinite"/></circle>
    <circle cx="70" cy="150" r="0.6"><animate attributeName="opacity" values="0.5;0.9;0.5" dur="3.1s" repeatCount="indefinite"/></circle>
    <circle cx="180" cy="180" r="0.5"><animate attributeName="opacity" values="0.4;1;0.4" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="350" cy="140" r="0.7"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.9s" repeatCount="indefinite"/></circle>
    <circle cx="500" cy="160" r="0.6"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.7s" repeatCount="indefinite"/></circle>
    <circle cx="680" cy="130" r="0.8"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" repeatCount="indefinite"/></circle>
    <circle cx="800" cy="170" r="0.5"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="4.1s" repeatCount="indefinite"/></circle>
    <circle cx="100" cy="250" r="0.7"><animate attributeName="opacity" values="0.6;1;0.6" dur="3.3s" repeatCount="indefinite"/></circle>
    <circle cx="260" cy="280" r="0.6"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="2.7s" repeatCount="indefinite"/></circle>
    <circle cx="400" cy="300" r="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="4.3s" repeatCount="indefinite"/></circle>
    <circle cx="560" cy="270" r="0.8"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="3.6s" repeatCount="indefinite"/></circle>
    <circle cx="720" cy="290" r="0.6"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="860" cy="260" r="0.7"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.9s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ★ Star field - Layer 2 (mid, red tint) ★ -->
  <g fill="#FF6666" opacity="0.5">
    <circle cx="90" cy="60" r="1"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="250" cy="100" r="0.9"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="470" cy="50" r="1.1"><animate attributeName="opacity" values="0.2;0.6;0.2" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="600" cy="90" r="0.8"><animate attributeName="opacity" values="0.4;0.7;0.4" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="780" cy="120" r="1"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="5.5s" repeatCount="indefinite"/></circle>
    <circle cx="150" cy="310" r="0.9"><animate attributeName="opacity" values="0.3;0.7;0.3" dur="4.8s" repeatCount="indefinite"/></circle>
    <circle cx="480" cy="320" r="1.1"><animate attributeName="opacity" values="0.2;0.6;0.2" dur="5.2s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="330" r="0.8"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.8s" repeatCount="indefinite"/></circle>
  </g>

  <!-- ★ Star field - Layer 3 (bright accent stars) ★ -->
  <g filter="url(#softglow)">
    <circle cx="300" cy="60" r="1.5" fill="#FF4444"><animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="620" cy="40" r="1.8" fill="#FFFFFF"><animate attributeName="opacity" values="0.4;1;0.4" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="160" cy="200" r="1.3" fill="#FF6666"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="770" cy="220" r="1.6" fill="#FFFFFF"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="450" cy="310" r="1.4" fill="#FF4444"><animate attributeName="opacity" values="0.5;1;0.5" dur="4.5s" repeatCount="indefinite"/></circle>
  </g>

  <!-- 🌑 Large planet with 3D shading -->
  <g>
    <circle cx="780" cy="100" r="55" fill="url(#planet)" opacity="0.9">
      <animate attributeName="cy" values="100;105;100" dur="8s" repeatCount="indefinite"/>
    </circle>
    <!-- Planet ring (3D effect) -->
    <ellipse cx="780" cy="100" rx="85" ry="18" fill="none" stroke="#FF444480" stroke-width="3" transform="rotate(-20, 780, 100)">
      <animate attributeName="cy" values="100;105;100" dur="8s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="780" cy="100" rx="75" ry="14" fill="none" stroke="#FF000040" stroke-width="2" transform="rotate(-20, 780, 100)">
      <animate attributeName="cy" values="100;105;100" dur="8s" repeatCount="indefinite"/>
    </ellipse>
    <!-- Planet atmosphere glow -->
    <circle cx="780" cy="100" r="60" fill="none" stroke="#FF000030" stroke-width="5">
      <animate attributeName="cy" values="100;105;100" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.2;0.5;0.2" dur="4s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- 🌑 Small planet -->
  <g>
    <circle cx="120" cy="280" r="22" fill="url(#planet2)" opacity="0.8">
      <animate attributeName="cx" values="120;125;120" dur="10s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="280;275;280" dur="10s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- ☄️ Shooting star 1 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;1;1;0" dur="6s" repeatCount="indefinite" begin="0s"/>
    <line x1="200" y1="20" x2="130" y2="60" stroke="url(#nebula1)" stroke-width="2">
      <animate attributeName="x1" values="850;100" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="y1" values="0;120" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="x2" values="800;50" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="y2" values="10;130" dur="1.5s" repeatCount="indefinite" begin="2s"/>
    </line>
    <line x1="200" y1="20" x2="130" y2="60" stroke="#FF4444" stroke-width="1">
      <animate attributeName="x1" values="850;100" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="y1" values="0;120" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="x2" values="800;50" dur="1.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="y2" values="10;130" dur="1.5s" repeatCount="indefinite" begin="2s"/>
    </line>
  </g>

  <!-- ☄️ Shooting star 2 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;0;0;1;1;0" dur="8s" repeatCount="indefinite" begin="3s"/>
    <line x1="700" y1="30" x2="650" y2="55" stroke="#FF6666" stroke-width="1.5">
      <animate attributeName="x1" values="900;300" dur="2s" repeatCount="indefinite" begin="5s"/>
      <animate attributeName="y1" values="10;200" dur="2s" repeatCount="indefinite" begin="5s"/>
      <animate attributeName="x2" values="860;260" dur="2s" repeatCount="indefinite" begin="5s"/>
      <animate attributeName="y2" values="20;210" dur="2s" repeatCount="indefinite" begin="5s"/>
    </line>
  </g>

  <!-- 🚀 Rocket silhouette -->
  <g transform="translate(80, 80) rotate(-45)" opacity="0.7">
    <animate attributeName="opacity" values="0.5;0.9;0.5" dur="5s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" values="80,80;85,75;80,80" dur="6s" repeatCount="indefinite"/>
    <!-- Rocket body -->
    <path d="M0,15 L5,0 L10,15 L8,15 L8,22 L2,22 L2,15 Z" fill="#FF4444" opacity="0.8"/>
    <!-- Rocket window -->
    <circle cx="5" cy="10" r="2" fill="#FF8888"/>
    <!-- Rocket flame -->
    <path d="M2,22 L5,30 L8,22" fill="#FF0000" opacity="0.9">
      <animate attributeName="d" values="M2,22 L5,30 L8,22;M2,22 L5,34 L8,22;M2,22 L5,30 L8,22" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="0.3s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- ═══ MAIN TITLE TEXT ═══ -->
  <g filter="url(#glow)">
    <!-- Shadow for 3D depth -->
    <text x="453" y="152" font-family="'Segoe UI', Arial, sans-serif" font-size="42" font-weight="bold" fill="#3D0000" text-anchor="middle" letter-spacing="4">DICKY RAHMAT FURQON</text>
    <!-- Main text -->
    <text x="450" y="150" font-family="'Segoe UI', Arial, sans-serif" font-size="42" font-weight="bold" fill="#FF0000" text-anchor="middle" letter-spacing="4">
      DICKY RAHMAT FURQON
      <animate attributeName="fill" values="#FF0000;#FF4444;#FF0000" dur="4s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Subtitle -->
  <text x="450" y="190" font-family="'Segoe UI', Arial, sans-serif" font-size="16" fill="#FF6666" text-anchor="middle" letter-spacing="6" opacity="0.9">
    &#x1F680; FULL STACK DEVELOPER &#x2022; SPACE EXPLORER &#x1F30C;
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- Decorative line under title -->
  <line x1="280" y1="210" x2="620" y2="210" stroke="#FF000060" stroke-width="1">
    <animate attributeName="x1" values="350;280;350" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="550;620;550" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="stroke" values="#FF000040;#FF000090;#FF000040" dur="4s" repeatCount="indefinite"/>
  </line>

  <!-- Status badges text -->
  <text x="450" y="240" font-family="'Segoe UI', Arial, sans-serif" font-size="12" fill="#FF444490" text-anchor="middle" letter-spacing="3">
    PHP &#x2022; LARAVEL &#x2022; VUE.JS &#x2022; JAVASCRIPT &#x2022; MYSQL
  </text>

  <!-- Bottom gradient fade -->
  <rect y="310" width="900" height="40" fill="url(#nebula1)" opacity="0.3"/>

  <!-- Bottom border glow -->
  <line x1="0" y1="349" x2="900" y2="349" stroke="#FF0000" stroke-width="2" opacity="0.6">
    <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
  </line>
</svg>

<br/>

<!-- ═══════════════════ ANIMATED TYPING ═══════════════════ -->

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=25&duration=3000&pause=1000&color=FF0000&center=true&vCenter=true&multiline=true&repeat=true&width=800&height=80&lines=%F0%9F%94%B4+Welcome+to+My+Digital+Universe+%F0%9F%94%B4;%E2%9C%A8+Exploring+Code+Across+the+Galaxy+%E2%9C%A8;%F0%9F%9B%B8+Building+Apps+Beyond+Imagination+%F0%9F%9B%B8" alt="Typing SVG" />
</a>

<br/>

<!-- ═══════════════════ SPACE DECORATION LINE ═══════════════════ -->

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</div>

<!-- ═══════════════════ ABOUT ME ═══════════════════ -->

<div align="center">

## 🌌 About Me — Space Commander 🌌

</div>

```javascript
const dickyFurqon = {
    fullName: "Dicky Rahmat Furqon",
    code: ["PHP", "JavaScript", "HTML", "CSS", "SQL"],
    tools: ["Laravel", "Vue.js", "Bootstrap", "MySQL", "Git"],
    passion: "Building beautiful web applications 🚀",
    currentMission: "Conquering the Full Stack Galaxy 🌠",
    funFact: "I debug code faster than light speed ⚡"
};
```

<div align="center">

<table>
<tr>
<td width="50%" align="center">

🔴 **Currently exploring**: Full Stack Development

🚀 **Working on**: Spotify Clone & More

🌌 **Learning**: Advanced Laravel & Vue.js

⭐ **Goal**: Building stellar web applications

🛸 **Fun**: Turning coffee into code ☕

</td>
<td width="50%" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300"/>

</td>
</tr>
</table>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ TECH STACK ═══════════════════ -->

<div align="center">

## 🔴 Tech Arsenal — Weapons of Creation 🔴

<br>

### 🛸 Languages

![PHP](https://img.shields.io/badge/PHP-8B0000?style=for-the-badge&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-8B0000?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-8B0000?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-8B0000?style=for-the-badge&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-8B0000?style=for-the-badge&logo=postgresql&logoColor=white)

### 🚀 Frameworks & Tools

![Laravel](https://img.shields.io/badge/Laravel-FF0000?style=for-the-badge&logo=laravel&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-FF0000?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Bootstrap](https://img.shields.io/badge/Bootstrap-FF0000?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-FF0000?style=for-the-badge&logo=jquery&logoColor=white)

### ⭐ Database & DevOps

![MySQL](https://img.shields.io/badge/MySQL-B22222?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-B22222?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-B22222?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-B22222?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-B22222?style=for-the-badge&logo=postman&logoColor=white)

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ GITHUB STATS ═══════════════════ -->

<div align="center">

## 📊 Mission Control — GitHub Stats 📊

<br>

<a href="https://github.com/furqon2004">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=furqon2004&show_icons=true&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666&ring_color=FF0000&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=furqon2004&layout=compact&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&text_color=FF6666"/>
</a>

<br/><br/>

<!-- STREAK STATS -->
<a href="https://github.com/furqon2004">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=furqon2004&theme=highcontrast&hide_border=true&background=0d0208&ring=FF0000&fire=FF4444&currStreakLabel=FF6666&sideLabels=FF4444&currStreakNum=FF0000&sideNums=FF6666&dates=8B0000&stroke=FF000050"/>
</a>

<br/><br/>

<!-- ACTIVITY GRAPH -->
<a href="https://github.com/furqon2004">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=furqon2004&bg_color=0d0208&color=FF4444&line=FF0000&point=FFFFFF&area_color=FF000040&area=true&hide_border=true&custom_title=🔴%20Contribution%20Galaxy%20Map%20🔴"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ FEATURED PROJECTS ═══════════════════ -->

<div align="center">

## 🛸 Featured Missions — Top Projects 🛸

<br>

<a href="https://github.com/furqon2004/backend-copy-spotify">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=backend-copy-spotify&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/Portfolio.Dicky">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=Portfolio.Dicky&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

<br/>

<a href="https://github.com/furqon2004/front-end-sistem-antrian-rumah-sakit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=front-end-sistem-antrian-rumah-sakit&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/marketplaceVue">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=marketplaceVue&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

<br/>

<a href="https://github.com/furqon2004/web-recipe">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=web-recipe&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>
<a href="https://github.com/furqon2004/tokoku">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=furqon2004&repo=tokoku&theme=radical&hide_border=true&bg_color=0d0208&title_color=FF0000&icon_color=FF4444&text_color=FF6666"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ TROPHY SECTION ═══════════════════ -->

<div align="center">

## 🏆 Space Achievements — Trophies 🏆

<br>

<a href="https://github.com/furqon2004">
  <img src="https://github-profile-trophy.vercel.app/?username=furqon2004&theme=radical&no-frame=true&no-bg=true&column=7&margin-w=15&margin-h=15"/>
</a>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ SNAKE ANIMATION ═══════════════════ -->

<div align="center">

## 🐍 Contribution Snake 🐍

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/furqon2004/furqon2004/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/furqon2004/furqon2004/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/furqon2004/furqon2004/output/github-snake-dark.svg" />
</picture>

</div>

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!-- ═══════════════════ VISITORS & CONNECT ═══════════════════ -->

<div align="center">

## 🌠 Connect With Me — Across the Universe 🌠

<br>

[![GitHub](https://img.shields.io/badge/GitHub-8B0000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/furqon2004)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF0000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/furqon2004/Portfolio.Dicky)

<br/><br/>

<!-- PROFILE VIEWS -->
<img src="https://komarev.com/ghpvc/?username=furqon2004&style=for-the-badge&color=FF0000&label=🔴+SPACE+VISITORS"/>

<br/><br/>

### 🔴 "The universe is under no obligation to make sense to you. But code should." 🔴

<br>

</div>

<!-- ═══════════════════ FOOTER ═══════════════════ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=0:0d0208,50:8B0000,100:FF0000&section=footer"/>
