<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="320" viewBox="0 0 1000 320" role="img" aria-label="Durjoy - CSE Student, Problem Solver, Future ML Engineer">
  <defs>
    <clipPath id="round"><rect width="1000" height="320" rx="20"/></clipPath>

    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#04070b"/>
      <stop offset="50%" stop-color="#08170f"/>
      <stop offset="100%" stop-color="#0c3a1d"/>
    </linearGradient>
    <linearGradient id="name" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#ffffff"/>
      <stop offset="55%" stop-color="#c8ff9a"/>
      <stop offset="100%" stop-color="#7cfc00"/>
    </linearGradient>
    <linearGradient id="sweep" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#7cfc00" stop-opacity="0"/>
      <stop offset="50%" stop-color="#7cfc00" stop-opacity="1"/>
      <stop offset="100%" stop-color="#7cfc00" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="term" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0d1117" stop-opacity="0.92"/>
      <stop offset="100%" stop-color="#070b10" stop-opacity="0.92"/>
    </linearGradient>
    <pattern id="grid" width="36" height="36" patternUnits="userSpaceOnUse">
      <path d="M 36 0 L 0 0 0 36" fill="none" stroke="#7cfc00" stroke-opacity="0.06" stroke-width="1"/>
    </pattern>
    <filter id="blur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="38"/>
    </filter>
    <filter id="softglow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <style>
      .mono { font-family: 'Fira Code','JetBrains Mono','SFMono-Regular',Consolas,'Courier New',monospace; }
      .sans { font-family: 'Segoe UI','Helvetica Neue',Helvetica,Arial,sans-serif; }

      .orb1 { animation: drift1 9s ease-in-out infinite; }
      .orb2 { animation: drift2 11s ease-in-out infinite; }
      .float1 { animation: f1 6s ease-in-out infinite; }
      .float2 { animation: f2 7s ease-in-out infinite; }
      .float3 { animation: f1 8s ease-in-out infinite reverse; }

      .rise { opacity: 0; animation: rise 1s cubic-bezier(.2,.7,.2,1) forwards; }
      .pop  { opacity: 0; animation: pop .6s cubic-bezier(.2,.9,.3,1.3) forwards; }
      .show { opacity: 0; animation: show .01s forwards; }

      .d1 { animation-delay: .2s; } .d2 { animation-delay: .5s; } .d3 { animation-delay: .8s; }
      .d4 { animation-delay: 1.1s; } .d5 { animation-delay: 1.4s; }
      .c1 { animation-delay: 1.5s; } .c2 { animation-delay: 1.65s; } .c3 { animation-delay: 1.8s; }
      .c4 { animation-delay: 1.95s; } .c5 { animation-delay: 2.1s; } .c6 { animation-delay: 2.25s; }
      .t1 { animation-delay: 1.0s; } .t2 { animation-delay: 1.5s; } .t3 { animation-delay: 2.1s; }
      .t4 { animation-delay: 2.6s; } .t5 { animation-delay: 3.2s; } .t6 { animation-delay: 3.7s; }
      .t7 { animation-delay: 4.2s; }

      .blink { animation: blink 1s steps(1) infinite; }
      .pulse { animation: pulse 2s ease-in-out infinite; transform-box: fill-box; transform-origin: center; }
      .sweepbar { animation: sweepx 4.5s linear infinite; }
      .ring { animation: ring 3s ease-in-out infinite; transform-box: fill-box; transform-origin: center; }

      @keyframes drift1 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(-40px,30px); } }
      @keyframes drift2 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(35px,-25px); } }
      @keyframes f1 { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-12px); } }
      @keyframes f2 { 0%,100% { transform: translateY(0); } 50% { transform: translateY(10px); } }
      @keyframes rise { from { opacity: 0; transform: translateY(16px); } to { opacity: 1; transform: translateY(0); } }
      @keyframes pop { from { opacity: 0; transform: scale(.7); } to { opacity: 1; transform: scale(1); } }
      @keyframes show { to { opacity: 1; } }
      @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0; } }
      @keyframes pulse { 0%,100% { transform: scale(1); opacity: 1; } 50% { transform: scale(1.7); opacity: .35; } }
      @keyframes sweepx { from { transform: translateX(-320px); } to { transform: translateX(1000px); } }
      @keyframes ring { 0%,100% { transform: scale(1); opacity: .5; } 50% { transform: scale(1.08); opacity: 1; } }
    </style>
  </defs>

  <g clip-path="url(#round)">
    <!-- background -->
    <rect width="1000" height="320" fill="url(#bg)"/>
    <rect width="1000" height="320" fill="url(#grid)"/>

    <!-- glowing orbs -->
    <circle class="orb1" cx="820" cy="60" r="110" fill="#7cfc00" fill-opacity="0.28" filter="url(#blur)"/>
    <circle class="orb2" cx="140" cy="300" r="120" fill="#19c37d" fill-opacity="0.22" filter="url(#blur)"/>

    <!-- floating code symbols -->
    <g class="mono" fill="#7cfc00" fill-opacity="0.16" font-weight="700">
      <text class="float1" x="565" y="70" font-size="40">{ }</text>
      <text class="float2" x="955" y="62" font-size="28" text-anchor="end">#</text>
      <text class="float3" x="585" y="300" font-size="30">&lt;/&gt;</text>
      <text class="float2" x="965" y="300" font-size="26" text-anchor="end">01</text>
    </g>

    <!-- status pill -->
    <g class="rise d1">
      <rect x="60" y="38" width="236" height="30" rx="15" fill="#7cfc00" fill-opacity="0.1" stroke="#7cfc00" stroke-opacity="0.55"/>
      <circle class="pulse" cx="82" cy="53" r="5" fill="#7cfc00"/>
      <circle cx="82" cy="53" r="5" fill="#7cfc00"/>
      <text class="mono" x="98" y="58" font-size="13" fill="#c8ff9a">open to collaborate</text>
    </g>

    <!-- greeting + name -->
    <text class="mono rise d2" x="60" y="112" font-size="19" fill="#7cfc00">&gt; hello, world. i am</text>
    <text class="sans rise d3" x="58" y="176" font-size="64" font-weight="800" fill="url(#name)" letter-spacing="0.5" filter="url(#softglow)">Naimur Durjoy</text>

    <!-- role -->
    <g class="rise d4">
      <text class="mono" x="60" y="213" font-size="17" fill="#d0d7de">CSE Student <tspan fill="#7cfc00">/</tspan> Problem Solver <tspan fill="#7cfc00">/</tspan> Future ML Engineer</text>
    </g>

    <!-- tech chips -->
    <g class="mono" font-size="13" text-anchor="middle">
      <g class="pop c1"><rect x="60"  y="240" width="62" height="28" rx="14" fill="#ED8B00" fill-opacity="0.14" stroke="#ED8B00" stroke-opacity="0.7"/><text x="91"  y="259" fill="#ffc266">Java</text></g>
      <g class="pop c2"><rect x="132" y="240" width="64" height="28" rx="14" fill="#3b8fd9" fill-opacity="0.14" stroke="#3b8fd9" stroke-opacity="0.7"/><text x="164" y="259" fill="#9fcdf5">C/C++</text></g>
      <g class="pop c3"><rect x="206" y="240" width="76" height="28" rx="14" fill="#FFD43B" fill-opacity="0.12" stroke="#FFD43B" stroke-opacity="0.65"/><text x="244" y="259" fill="#ffe487">Python</text></g>
      <g class="pop c4"><rect x="292" y="240" width="70" height="28" rx="14" fill="#4aa3df" fill-opacity="0.14" stroke="#4aa3df" stroke-opacity="0.7"/><text x="327" y="259" fill="#a6d3f0">MySQL</text></g>
      <g class="pop c5"><rect x="372" y="240" width="54" height="28" rx="14" fill="#7cfc00" fill-opacity="0.12" stroke="#7cfc00" stroke-opacity="0.65"/><text x="399" y="259" fill="#c8ff9a">DSA</text></g>
      <g class="pop c6"><rect x="436" y="240" width="48" height="28" rx="14" fill="#a259ff" fill-opacity="0.14" stroke="#a259ff" stroke-opacity="0.7"/><text x="460" y="259" fill="#d2b0ff">ML</text></g>
    </g>

    <!-- terminal window -->
    <g class="rise d3">
      <rect class="ring" x="640" y="46" width="312" height="228" rx="14" fill="none" stroke="#7cfc00" stroke-opacity="0.35"/>
      <rect x="640" y="46" width="312" height="228" rx="14" fill="url(#term)" stroke="#7cfc00" stroke-opacity="0.5"/>
      <path d="M640 60 a14 14 0 0 1 14 -14 h284 a14 14 0 0 1 14 14 v18 h-312 z" fill="#ffffff" fill-opacity="0.05"/>
      <circle cx="662" cy="62" r="5" fill="#ff5f57"/>
      <circle cx="680" cy="62" r="5" fill="#febc2e"/>
      <circle cx="698" cy="62" r="5" fill="#28c840"/>
      <text class="mono" x="796" y="66" font-size="11" fill="#8b949e" text-anchor="middle">durjoy@dev: ~</text>

      <g class="mono" font-size="14">
        <text class="show t1" x="662" y="110" fill="#7cfc00">$ <tspan fill="#e6edf3">whoami</tspan></text>
        <text class="show t2" x="662" y="132" fill="#c8ff9a">durjoy</text>

        <text class="show t3" x="662" y="162" fill="#7cfc00">$ <tspan fill="#e6edf3">cat skills.txt</tspan></text>
        <text class="show t4" x="662" y="184" fill="#c8ff9a">java  c++  python  mysql</text>

        <text class="show t5" x="662" y="214" fill="#7cfc00">$ <tspan fill="#e6edf3">./goal --run</tspan></text>
        <text class="show t6" x="662" y="236" fill="#c8ff9a">Machine Learning Engineer</text>

        <text class="show t7" x="662" y="262" fill="#7cfc00">$ </text>
        <rect class="blink show t7" x="680" y="250" width="8" height="15" fill="#7cfc00"/>
      </g>
    </g>

    <!-- sweeping light on the bottom edge -->
    <g class="sweepbar">
      <rect x="0" y="316" width="320" height="4" fill="url(#sweep)"/>
    </g>
  </g>

  <!-- border -->
  <rect x="1" y="1" width="998" height="318" rx="19" fill="none" stroke="#7cfc00" stroke-opacity="0.4"/>
</svg>
<!-- ═══════════════════════ HERO ═══════════════════════ -->
<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Durjoy — CSE Student, Problem Solver, Future ML Engineer"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=7CFC00&center=true&vCenter=true&width=760&height=45&lines=Learn.+Build.+Improve.+Repeat.;Java+%7C+C%2B%2B+%7C+Python+%7C+MySQL;Solving+problems%2C+one+commit+at+a+time;On+the+road+to+Machine+Learning+%F0%9F%A4%96" alt="Typing animation"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GitHub-NRD--404run-161B22?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  <img src="https://img.shields.io/badge/University-City%20University-0d1117?style=for-the-badge&logo=academia&logoColor=7cfc00" alt="City University"/>
  <img src="https://img.shields.io/badge/Goal-ML%20Engineer-8A2BE2?style=for-the-badge&logo=python&logoColor=white" alt="Goal"/>
  <img src="https://komarev.com/ghpvc/?username=NRD-404run&label=Profile%20Views&color=7cfc00&style=for-the-badge&labelColor=0d1117" alt="Profile Views"/>
</p>

<!-- quick nav -->
<p align="center">
  <a href="#-about-me"><img src="https://img.shields.io/badge/About-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
  <a href="#-tech-arsenal"><img src="https://img.shields.io/badge/Skills-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
  <a href="#-featured-project"><img src="https://img.shields.io/badge/Projects-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
  <a href="#-github-analytics"><img src="https://img.shields.io/badge/Stats-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
  <a href="#-roadmap"><img src="https://img.shields.io/badge/Roadmap-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
  <a href="#-lets-connect"><img src="https://img.shields.io/badge/Contact-0d1117?style=flat-square&labelColor=0d1117&color=7cfc00"/></a>
</p>

<p align="center">
  <a href="https://github.com/NRD-404run?tab=repositories">
    <img src="https://img.shields.io/badge/%F0%9F%93%82%20Explore%20My%20Repositories-0d1117?style=for-the-badge&labelColor=0d1117&color=7cfc00" alt="Repositories"/>
  </a>
</p>

---

## 👨‍💻 About Me

<table>
<tr>
<td width="55%" valign="top">

```python
class Durjoy:
    name       = "MD Naimur Rahman Durjoy"
    role       = "CSE Student"
    university = "City University"
    languages  = ["C", "C++", "Java", "Python"]
    database   = ["MySQL"]
    interests  = ["Problem Solving",
                  "Software Development",
                  "Machine Learning"]
    focus      = ["Python", "DSA", "Projects"]
    goal       = "Machine Learning Engineer"

    def motto(self):
        return "Consistency over perfection."

print(Durjoy().motto())
```

</td>
<td width="45%" valign="top">

- 🎓 **CSE** @ City University
- 🔭 Building **Blood Link**, a Java donor management system
- 🌱 Learning **Python, DSA & databases**
- 🤖 Heading toward **Machine Learning**
- 🤝 Open to **Java + Database** collaborations
- 💬 Ask me about **C / C++ / Java / DSA**
- ⚡ *Turns coffee ☕ into code 💻 and bugs 🐞 into learning*

</td>
</tr>
</table>

---

## 🛠️ Tech Arsenal

<p align="center">
  <b>Languages</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=c,cpp,java,python&theme=dark" alt="Languages"/>
</p>

<p align="center">
  <b>Tools & Technologies</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=mysql,git,github,vscode,html,css&theme=dark" alt="Tools"/>
</p>

<p align="center">
  <b>Currently Learning</b><br/><br/>
  <img src="https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms-00599C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-8A2BE2?style=for-the-badge" />
</p>

---

## 🚀 Featured Project

<table align="center">
<tr>
<td>

### 🩸 Blood Link — Blood Donor Management System

A Java desktop application focused on connecting people with blood donors and managing blood donation requests.

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Java%20Swing-5382A1?style=for-the-badge" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/JDBC-0d1117?style=for-the-badge&labelColor=0d1117&color=7cfc00" />

| 🔐 Role-based login | 🩸 Donor registration | 🔍 Blood-group search |
|:---:|:---:|:---:|
| 📍 Location-based discovery | 📩 Request management | 🛡️ Admin controls |

<sub>Feature list reflects the project roadmap.</sub>

</td>
</tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/C%2FC%2B%2B%20Practice-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java%20%26%20OOP-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python%20Fundamentals-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/DSA%20Problems-7CFC00?style=flat-square&logoColor=black" />
</p>

---

## 📊 GitHub Analytics

<p align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=NRD-404run&show_icons=true&rank_icon=github&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7cfc00&icon_color=7cfc00&cache_seconds=3600" alt="GitHub stats"/>
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=NRD-404run&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7cfc00&cache_seconds=3600" alt="Top languages"/>
</p>

<p align="center">
  <img width="70%" src="https://streak-stats.demolab.com?user=NRD-404run&theme=tokyonight&hide_border=true&background=0d1117&ring=7cfc00&fire=7cfc00&currStreakLabel=7cfc00&cache_seconds=3600" alt="Streak"/>
</p>

<p align="center">
  <img height="150" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=NRD-404run&theme=tokyonight" />
  <img height="150" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=NRD-404run&theme=tokyonight" />
  <img height="150" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=NRD-404run&theme=tokyonight&utcOffset=6" />
</p>

<p align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=NRD-404run&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=7cfc00&line=7cfc00&point=ffffff&area=true&area_color=7cfc00" alt="Contribution graph"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/NRD-404run/NRD-404run/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/NRD-404run/NRD-404run/output/github-snake.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/NRD-404run/NRD-404run/output/github-snake-dark.svg"/>
  </picture>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=NRD-404run&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" width="100%" alt="Trophies"/>
</p>

---

## 🎯 Roadmap

| Stage | Goal | Status |
|:---:|---|:---:|
| 1 | Learn programming fundamentals | ✅ Done |
| 2 | Start working with Java and databases | ✅ Done |
| 3 | Strengthen Data Structures & Algorithms | 🔄 In progress |
| 4 | Build and publish more Python projects | 🔜 Next |
| 5 | Learn NumPy, Pandas & data analysis | 🔜 Next |
| 6 | Study Machine Learning fundamentals | 🎯 Planned |
| 7 | Build practical ML projects | 🎯 Planned |
| 8 | Contribute to open source | 🎯 Planned |

---

## 🌱 Beyond the Code

<p align="center">
  <img src="https://img.shields.io/badge/🏸_Badminton-0d1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🏊_Swimming-0d1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/💪_Fitness_&_Gym-0d1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🍵_Tea-0d1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/📚_Tech_Reading-0d1117?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🎬_Movies-0d1117?style=for-the-badge" />
</p>

---

## 🌐 Let's Connect

<p align="center">
  <a href="https://github.com/NRD-404run">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://twitter.com/mddurjoy16250">
    <img src="https://img.shields.io/badge/Twitter-000000?style=for-the-badge&logo=x&logoColor=white" alt="Twitter / X"/>
  </a>
  <a href="https://www.facebook.com/md.naimur.rahman.durjoy.360743">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/>
  </a>
  <a href="mailto:mddurjoy54531113@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  <i>"First, solve the problem. Then, write the code."</i><br/><br/>
  <b>Thanks for visiting! ⭐ Keep Learning • Keep Building • Keep Growing</b>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1b4332,100:7cfc00&height=110&section=footer" />
