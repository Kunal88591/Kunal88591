<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  ANIMATED SVG HERO                     -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="900" height="300" viewBox="0 0 900 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020b10"/>
      <stop offset="50%" style="stop-color:#050f1a"/>
      <stop offset="100%" style="stop-color:#020b10"/>
    </linearGradient>
    <linearGradient id="teal-glow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="50%" style="stop-color:#00ffd5"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
    <linearGradient id="name-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ffd5"/>
      <stop offset="45%" style="stop-color:#9b5de5"/>
      <stop offset="100%" style="stop-color:#ff2d78"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow-strong">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <radialGradient id="orb1" cx="20%" cy="30%" r="50%">
      <stop offset="0%" style="stop-color:#00ffd5;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#00ffd5;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="80%" cy="70%" r="50%">
      <stop offset="0%" style="stop-color:#9b5de5;stop-opacity:0.18"/>
      <stop offset="100%" style="stop-color:#9b5de5;stop-opacity:0"/>
    </radialGradient>
    <radialGradient id="orb3" cx="55%" cy="20%" r="40%">
      <stop offset="0%" style="stop-color:#ff2d78;stop-opacity:0.1"/>
      <stop offset="100%" style="stop-color:#ff2d78;stop-opacity:0"/>
    </radialGradient>
  </defs>

  <!-- Background -->
  <rect width="900" height="300" fill="url(#bg)" rx="12"/>
  <rect width="900" height="300" fill="url(#orb1)" rx="12"/>
  <rect width="900" height="300" fill="url(#orb2)" rx="12"/>
  <rect width="900" height="300" fill="url(#orb3)" rx="12"/>

  <!-- Circuit lines -->
  <g opacity="0.12" stroke="#00ffd5" stroke-width="0.8" fill="none">
    <path d="M0,80 L120,80 L140,60 L300,60"/>
    <path d="M0,200 L80,200 L100,180 L200,180 L220,160 L350,160"/>
    <path d="M900,100 L780,100 L760,120 L600,120"/>
    <path d="M900,220 L820,220 L800,200 L700,200 L680,180 L550,180"/>
    <circle cx="120" cy="80" r="3" fill="#00ffd5" opacity="0.6"/>
    <circle cx="140" cy="60" r="3" fill="#00ffd5" opacity="0.6"/>
    <circle cx="80" cy="200" r="3" fill="#00ffd5" opacity="0.6"/>
    <circle cx="100" cy="180" r="3" fill="#00ffd5" opacity="0.6"/>
    <circle cx="220" cy="160" r="3" fill="#00ffd5" opacity="0.6"/>
    <circle cx="780" cy="100" r="3" fill="#9b5de5" opacity="0.6"/>
    <circle cx="760" cy="120" r="3" fill="#9b5de5" opacity="0.6"/>
    <circle cx="820" cy="220" r="3" fill="#9b5de5" opacity="0.6"/>
    <circle cx="800" cy="200" r="3" fill="#9b5de5" opacity="0.6"/>
  </g>

  <!-- Animated scan line -->
  <rect x="0" y="0" width="900" height="2" fill="url(#teal-glow)" opacity="0.6">
    <animateTransform attributeName="transform" type="translate" from="0,0" to="0,300" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;0.6;0" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner decorations -->
  <g stroke="#00ffd5" stroke-width="1.5" fill="none" opacity="0.5">
    <path d="M20,10 L10,10 L10,20"/>
    <path d="M880,10 L890,10 L890,20"/>
    <path d="M20,290 L10,290 L10,280"/>
    <path d="M880,290 L890,290 L890,280"/>
  </g>

  <!-- STATUS badge -->
  <rect x="350" y="30" width="200" height="22" rx="11" fill="rgba(0,255,213,0.06)" stroke="rgba(0,255,213,0.25)" stroke-width="1"/>
  <circle cx="365" cy="41" r="4" fill="#00ffd5">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/>
  </circle>
  <text x="375" y="46" font-family="monospace" font-size="9" fill="#00ffd5" letter-spacing="2">AVAILABLE FOR HIRE</text>

  <!-- Main name -->
  <text x="450" y="130" font-family="'Arial Black', sans-serif" font-size="72" font-weight="900"
        text-anchor="middle" fill="url(#name-grad)" filter="url(#glow-strong)"
        letter-spacing="-2">KUNAL</text>
  <text x="450" y="195" font-family="'Arial Black', sans-serif" font-size="72" font-weight="900"
        text-anchor="middle" fill="#eaf4ff" filter="url(#glow)"
        letter-spacing="-2" opacity="0.92">MEENA</text>

  <!-- Subtitle line -->
  <line x1="180" y1="218" x2="720" y2="218" stroke="url(#teal-glow)" stroke-width="1"/>

  <!-- Role badges -->
  <text x="220" y="245" font-family="monospace" font-size="9.5" fill="#00ffd5" letter-spacing="3" text-anchor="middle">DEVELOPER</text>
  <text x="340" y="245" font-family="monospace" font-size="9.5" fill="rgba(255,255,255,0.2)" text-anchor="middle">·</text>
  <text x="450" y="245" font-family="monospace" font-size="9.5" fill="#9b5de5" letter-spacing="3" text-anchor="middle">AI ENGINEER</text>
  <text x="560" y="245" font-family="monospace" font-size="9.5" fill="rgba(255,255,255,0.2)" text-anchor="middle">·</text>
  <text x="680" y="245" font-family="monospace" font-size="9.5" fill="#ffd60a" letter-spacing="3" text-anchor="middle">AUTHOR</text>

  <!-- IIITDM label -->
  <text x="450" y="272" font-family="monospace" font-size="8" fill="rgba(74,122,155,0.8)" letter-spacing="4" text-anchor="middle">IIITDM JABALPUR  //  B.TECH CSE</text>

  <!-- Animated particles -->
  <circle cx="50" cy="50" r="1.5" fill="#00ffd5" opacity="0.7">
    <animate attributeName="cy" values="50;40;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="250" r="1.5" fill="#9b5de5" opacity="0.7">
    <animate attributeName="cy" values="250;260;250" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="250" r="1" fill="#ff2d78" opacity="0.5">
    <animate attributeName="cx" values="150;160;150" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="50" r="1" fill="#ffd60a" opacity="0.5">
    <animate attributeName="cx" values="750;740;750" dur="4.5s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=15&duration=2800&pause=700&color=00FFD5&center=true&vCenter=true&width=700&lines=%E3%80%94+Full-Stack+Developer+%2F%2F+AI+Engineer+%E3%80%95;%E3%80%94+Building+at+the+edge+of+Code+%26+Intelligence+%E3%80%95;%E3%80%94+NPTEL+Gold+%C2%B7+Top+1%25+among+16%2C000%2B+%7C+IIT+Kharagpur+%E3%80%95;%E3%80%94+Published+Author+%E2%80%94+%22The+Ideal+Man%22+%E3%80%95;%E3%80%94+Build.+Break.+Learn.+Repeat.+%E3%80%95)](https://github.com/Kunal88591)

</div>

<br>

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Kunal88591&label=PROFILE+VIEWS&color=00ffd5&style=flat-square&labelColor=020b10)](https://github.com/Kunal88591)&nbsp;
[![Followers](https://img.shields.io/github/followers/Kunal88591?label=FOLLOWERS&style=flat-square&color=9b5de5&labelColor=020b10)](https://github.com/Kunal88591)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-00b4d8?style=flat-square&logo=linkedin&logoColor=white&labelColor=020b10)](https://linkedin.com/in/kunal8859)&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-ffd60a?style=flat-square&logo=firefox-browser&logoColor=black&labelColor=020b10)](https://kunal88591.github.io/portfolio)&nbsp;
[![Email](https://img.shields.io/badge/Email-Reach_Out-ff2d78?style=flat-square&logo=gmail&logoColor=white&labelColor=020b10)](mailto:kunalmeena1311@gmail.com)

</div>

<br>

---

<div align="center">
<svg width="860" height="30" viewBox="0 0 860 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sl1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#00ffd5"/>
      <stop offset="80%" style="stop-color:#9b5de5"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="15" x2="860" y2="15" stroke="url(#sl1)" stroke-width="1" opacity="0.4"/>
  <text x="430" y="20" font-family="monospace" font-size="11" fill="#00ffd5" text-anchor="middle" letter-spacing="6">// ABOUT ME</text>
</svg>
</div>

<br>

<table align="center" border="0" cellspacing="0" cellpadding="0">
<tr>
<td width="55%" valign="top">

```java
/**
 * @author  Kunal Meena
 * @version ∞
 * @since   Birth of an Idea
 */
public class KunalMeena extends Developer {

  private final String[] superpowers = {
    "Full-Stack Architecture",
    "AI / ML Systems",
    "Published Author",
    "Competitive Programming"
  };

  private final String institute =
      "IIITDM Jabalpur · B.Tech CSE";

  @Override
  public String motto() {
    return "Build. Break. Learn. Repeat.";
  }

  @Override
  public void think() {
    // Curiosity is my compass.
    // Every error is a lesson.
  }
}
```

</td>
<td width="5%"></td>
<td width="40%" valign="top">

<br>

🟢 &nbsp;**Status** — Open to Opportunities  
📍 &nbsp;**Location** — Jabalpur, India  
🎓 &nbsp;**Degree** — B.Tech CSE · IIITDM  
🤖 &nbsp;**Focus** — AI / ML + Full Stack  
📖 &nbsp;**Author** — *The Ideal Man*  
🏆 &nbsp;**NPTEL** — Gold + Elite · Top 1%  
💻 &nbsp;**DSA** — 300+ Problems Solved  
🎭 &nbsp;**Drama** — Jazbaat · National Level  

<br>

> *"Curiosity is my compass.*  
> *Adventure is my code."*

</td>
</tr>
</table>

<br>

---

<div align="center">
<svg width="860" height="30" viewBox="0 0 860 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sl2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#9b5de5"/>
      <stop offset="80%" style="stop-color:#ff2d78"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="15" x2="860" y2="15" stroke="url(#sl2)" stroke-width="1" opacity="0.4"/>
  <text x="430" y="20" font-family="monospace" font-size="11" fill="#9b5de5" text-anchor="middle" letter-spacing="6">// TECH ARSENAL</text>
</svg>
</div>

<br><br>

<div align="center">

**〔 Languages 〕**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-00ffd5?style=for-the-badge&logo=python&logoColor=020b10)
![JavaScript](https://img.shields.io/badge/JavaScript-ffd60a?style=for-the-badge&logo=javascript&logoColor=020b10)
![C++](https://img.shields.io/badge/C++-9b5de5?style=for-the-badge&logo=cplusplus&logoColor=white)

**〔 Frontend 〕**

![React](https://img.shields.io/badge/React-00ffd5?style=for-the-badge&logo=react&logoColor=020b10)
![Next.js](https://img.shields.io/badge/Next.js-ffffff?style=for-the-badge&logo=next.js&logoColor=020b10)
![TailwindCSS](https://img.shields.io/badge/Tailwind-00b4d8?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-ff2d78?style=for-the-badge&logo=html5&logoColor=white)

**〔 Backend 〕**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Django](https://img.shields.io/badge/Django-9b5de5?style=for-the-badge&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-00ffd5?style=for-the-badge&logo=node.js&logoColor=020b10)
![Flask](https://img.shields.io/badge/Flask-ffffff?style=for-the-badge&logo=flask&logoColor=020b10)

**〔 AI / ML 〕**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-9b5de5?style=for-the-badge&logo=opencv&logoColor=white)
![NLP](https://img.shields.io/badge/NLP_SpaCy-00ffd5?style=for-the-badge&logo=spacy&logoColor=020b10)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-ff2d78?style=for-the-badge&logo=pytorch&logoColor=white)

**〔 Databases & DevOps 〕**

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00b4d8?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-ffd60a?style=for-the-badge&logo=firebase&logoColor=020b10)
![Supabase](https://img.shields.io/badge/Supabase-00ffd5?style=for-the-badge&logo=supabase&logoColor=020b10)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-ff2d78?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

---

<div align="center">
<svg width="860" height="30" viewBox="0 0 860 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sl3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#ffd60a"/>
      <stop offset="80%" style="stop-color:#00ffd5"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="15" x2="860" y2="15" stroke="url(#sl3)" stroke-width="1" opacity="0.4"/>
  <text x="430" y="20" font-family="monospace" font-size="11" fill="#ffd60a" text-anchor="middle" letter-spacing="6">// GITHUB STATS</text>
</svg>
</div>

<br><br>

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=Kunal88591&show_icons=true&theme=tokyonight&bg_color=020b10&title_color=00ffd5&icon_color=9b5de5&text_color=eaf4ff&border_color=00ffd520&count_private=true&include_all_commits=true&rank_icon=github" />
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kunal88591&layout=compact&theme=tokyonight&bg_color=020b10&title_color=00ffd5&text_color=eaf4ff&border_color=00ffd520&langs_count=8" />

<br><br>

<img width="68%" src="https://github-readme-streak-stats.herokuapp.com/?user=Kunal88591&theme=tokyonight&background=020b10&ring=00ffd5&fire=ff2d78&currStreakLabel=9b5de5&sideLabels=eaf4ff&currStreakNum=ffffff&sideNums=ffffff&dates=4a7a9b&border=00ffd520" />

<br><br>

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=Kunal88591&bg_color=020b10&color=00ffd5&line=9b5de5&point=ff2d78&area=true&area_color=00ffd515&hide_border=true" />

</div>

<br>

---

<div align="center">
<svg width="860" height="30" viewBox="0 0 860 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sl4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#ff2d78"/>
      <stop offset="80%" style="stop-color:#ffd60a"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="15" x2="860" y2="15" stroke="url(#sl4)" stroke-width="1" opacity="0.4"/>
  <text x="430" y="20" font-family="monospace" font-size="11" fill="#ff2d78" text-anchor="middle" letter-spacing="6">// ACHIEVEMENTS</text>
</svg>
</div>

<br>

<div align="center">

<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cdbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020b10"/>
      <stop offset="100%" style="stop-color:#051520"/>
    </linearGradient>
  </defs>

  <!-- Card 1 - Gold -->
  <rect x="10" y="10" width="185" height="120" rx="8" fill="url(#cdbg)" stroke="rgba(255,214,10,0.25)" stroke-width="1"/>
  <rect x="10" y="10" width="185" height="3" rx="2" fill="#ffd60a" opacity="0.7"/>
  <text x="30" y="48" font-size="24" font-family="monospace">🥇</text>
  <text x="62" y="42" font-family="Arial" font-size="10" font-weight="bold" fill="#ffd60a" letter-spacing="1">NPTEL GOLD+ELITE</text>
  <text x="30" y="62" font-family="monospace" font-size="8" fill="rgba(255,255,255,0.45)">IIT Kharagpur · Java</text>
  <text x="30" y="80" font-family="Arial" font-size="9" fill="rgba(234,244,255,0.7)">94% Score · Top 1%</text>
  <text x="30" y="96" font-family="Arial" font-size="8.5" fill="rgba(74,122,155,0.9)">Among 16,000+ participants</text>
  <text x="30" y="124" font-family="monospace" font-size="7.5" fill="#ffd60a" opacity="0.6" letter-spacing="1">CERTIFICATION</text>

  <!-- Card 2 - Teal -->
  <rect x="215" y="10" width="185" height="120" rx="8" fill="url(#cdbg)" stroke="rgba(0,255,213,0.2)" stroke-width="1"/>
  <rect x="215" y="10" width="185" height="3" rx="2" fill="#00ffd5" opacity="0.7"/>
  <text x="235" y="48" font-size="24" font-family="monospace">🥉</text>
  <text x="267" y="42" font-family="Arial" font-size="10" font-weight="bold" fill="#00ffd5" letter-spacing="1">2ND RUNNER-UP</text>
  <text x="235" y="62" font-family="monospace" font-size="8" fill="rgba(255,255,255,0.45)">Pearl 2025 · BITS Hyderabad</text>
  <text x="235" y="80" font-family="Arial" font-size="9" fill="rgba(234,244,255,0.7)">National Street Play</text>
  <text x="235" y="96" font-family="Arial" font-size="8.5" fill="rgba(74,122,155,0.9)">Jazbaat Dramatics Society</text>
  <text x="235" y="124" font-family="monospace" font-size="7.5" fill="#00ffd5" opacity="0.6" letter-spacing="1">NATIONAL LEVEL</text>

  <!-- Card 3 - Purple -->
  <rect x="420" y="10" width="185" height="120" rx="8" fill="url(#cdbg)" stroke="rgba(155,93,229,0.25)" stroke-width="1"/>
  <rect x="420" y="10" width="185" height="3" rx="2" fill="#9b5de5" opacity="0.7"/>
  <text x="440" y="48" font-size="24" font-family="monospace">💻</text>
  <text x="472" y="42" font-family="Arial" font-size="10" font-weight="bold" fill="#9b5de5" letter-spacing="1">300+ DSA PROBLEMS</text>
  <text x="440" y="62" font-family="monospace" font-size="8" fill="rgba(255,255,255,0.45)">Competitive Programming</text>
  <text x="440" y="80" font-family="Arial" font-size="9" fill="rgba(234,244,255,0.7)">CodeRumble Hackathon 2024</text>
  <text x="440" y="96" font-family="Arial" font-size="8.5" fill="rgba(74,122,155,0.9)">IIITDM Jabalpur</text>
  <text x="440" y="124" font-family="monospace" font-size="7.5" fill="#9b5de5" opacity="0.6" letter-spacing="1">PROBLEM SOLVER</text>

  <!-- Card 4 - Pink -->
  <rect x="625" y="10" width="220" height="120" rx="8" fill="url(#cdbg)" stroke="rgba(255,45,120,0.22)" stroke-width="1"/>
  <rect x="625" y="10" width="220" height="3" rx="2" fill="#ff2d78" opacity="0.7"/>
  <text x="645" y="48" font-size="24" font-family="monospace">🏅</text>
  <text x="677" y="42" font-family="Arial" font-size="10" font-weight="bold" fill="#ff2d78" letter-spacing="1">MICROSOFT-AICTE</text>
  <text x="645" y="62" font-family="monospace" font-size="8" fill="rgba(255,255,255,0.45)">Edunet Foundation</text>
  <text x="645" y="80" font-family="Arial" font-size="9" fill="rgba(234,244,255,0.7)">Technical Excellence Award</text>
  <text x="645" y="96" font-family="Arial" font-size="8.5" fill="rgba(74,122,155,0.9)">Project Innovation Certified</text>
  <text x="645" y="124" font-family="monospace" font-size="7.5" fill="#ff2d78" opacity="0.6" letter-spacing="1">CERTIFIED</text>

  <!-- Book card - wide -->
  <rect x="10" y="150" width="840" height="120" rx="8" fill="url(#cdbg)" stroke="rgba(255,214,10,0.2)" stroke-width="1"/>
  <rect x="10" y="150" width="840" height="3" rx="2" fill="#ffd60a" opacity="0.5"/>

  <!-- Book cover -->
  <rect x="30" y="168" width="58" height="84" rx="3" fill="#1a0a30" stroke="rgba(255,214,10,0.35)" stroke-width="1"/>
  <rect x="30" y="168" width="10" height="84" rx="2" fill="#0d0620"/>
  <text x="59" y="196" font-family="Arial" font-size="7" font-weight="bold" fill="#ffd60a" text-anchor="middle">THE</text>
  <text x="59" y="208" font-family="Arial" font-size="7" font-weight="bold" fill="#ffd60a" text-anchor="middle">IDEAL</text>
  <text x="59" y="220" font-family="Arial" font-size="7" font-weight="bold" fill="#ffd60a" text-anchor="middle">MAN</text>
  <line x1="42" y1="228" x2="76" y2="228" stroke="#ffd60a" stroke-width="0.5" opacity="0.5"/>
  <text x="59" y="240" font-family="monospace" font-size="5" fill="rgba(255,214,10,0.4)" text-anchor="middle">KUNAL MEENA</text>

  <!-- Book text -->
  <text x="112" y="183" font-family="monospace" font-size="9" fill="#ffd60a" letter-spacing="2">✦  PUBLISHED AUTHOR</text>
  <text x="112" y="204" font-family="Arial" font-size="14" font-weight="bold" fill="white">The Ideal Man</text>
  <text x="112" y="222" font-family="Arial" font-size="9" fill="rgba(234,244,255,0.6)" font-style="italic">A philosophical debut — purpose, discipline, integrity.</text>
  <text x="112" y="239" font-family="Arial" font-size="8.5" fill="rgba(74,122,155,0.9)">Written during B.Tech in 10 months · 9 Lessons · 72 Parts</text>
  <text x="112" y="260" font-family="monospace" font-size="8" fill="rgba(255,214,10,0.55)" letter-spacing="1">Available on Pothi.com  ↗</text>

  <!-- Stats -->
  <rect x="580" y="166" width="80" height="48" rx="4" fill="rgba(255,214,10,0.04)" stroke="rgba(255,214,10,0.12)" stroke-width="1"/>
  <text x="620" y="185" font-family="Arial" font-size="18" font-weight="900" fill="#ffd60a" text-anchor="middle">10</text>
  <text x="620" y="200" font-family="monospace" font-size="7" fill="rgba(255,255,255,0.35)" text-anchor="middle" letter-spacing="1">MONTHS</text>
  <text x="620" y="210" font-family="monospace" font-size="6" fill="rgba(255,214,10,0.4)" text-anchor="middle">TO WRITE</text>

  <rect x="670" y="166" width="80" height="48" rx="4" fill="rgba(155,93,229,0.04)" stroke="rgba(155,93,229,0.12)" stroke-width="1"/>
  <text x="710" y="185" font-family="Arial" font-size="18" font-weight="900" fill="#9b5de5" text-anchor="middle">9</text>
  <text x="710" y="200" font-family="monospace" font-size="7" fill="rgba(255,255,255,0.35)" text-anchor="middle" letter-spacing="1">LESSONS</text>
  <text x="710" y="210" font-family="monospace" font-size="6" fill="rgba(155,93,229,0.4)" text-anchor="middle">PROFOUND</text>

  <rect x="760" y="166" width="80" height="48" rx="4" fill="rgba(0,255,213,0.04)" stroke="rgba(0,255,213,0.12)" stroke-width="1"/>
  <text x="800" y="185" font-family="Arial" font-size="18" font-weight="900" fill="#00ffd5" text-anchor="middle">72</text>
  <text x="800" y="200" font-family="monospace" font-size="7" fill="rgba(255,255,255,0.35)" text-anchor="middle" letter-spacing="1">PARTS</text>
  <text x="800" y="210" font-family="monospace" font-size="6" fill="rgba(0,255,213,0.4)" text-anchor="middle">COMPLETE</text>
</svg>

</div>

<br>

---

<div align="center">
<svg width="860" height="30" viewBox="0 0 860 30" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sl5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#00ffd5"/>
      <stop offset="80%" style="stop-color:#ff2d78"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="15" x2="860" y2="15" stroke="url(#sl5)" stroke-width="1" opacity="0.4"/>
  <text x="430" y="20" font-family="monospace" font-size="11" fill="#00ffd5" text-anchor="middle" letter-spacing="6">// LET'S CONNECT</text>
</svg>
</div>

<br>

```bash
╔══════════════════════════════════════════════════════════════╗
║  $ ./connect_with_kunal.sh                                   ║
║                                                              ║
║  > Scanning for: builders, dreamers, collaborators...        ║
║  > Status:  ████████████████████  ONLINE                     ║
║  > Ping:    < 1ms  ·  Always available                       ║
║  > Mode:    Internships · Collabs · Great Ideas              ║
║                                                              ║
║  > Connection established. Let's build something legendary.  ║
╚══════════════════════════════════════════════════════════════╝
```

<br>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kunal8859)
[![Gmail](https://img.shields.io/badge/Gmail-ff2d78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kunalmeena1311@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-020b10?style=for-the-badge&logo=github&logoColor=00ffd5)](https://github.com/Kunal88591)
[![Portfolio](https://img.shields.io/badge/Portfolio-ffd60a?style=for-the-badge&logo=firefox-browser&logoColor=020b10)](https://kunal88591.github.io/portfolio)
[![Phone](https://img.shields.io/badge/+91_6261_629_737-00ffd5?style=for-the-badge&logo=whatsapp&logoColor=020b10)](tel:+916261629737)

</div>

<br>

---

<div align="center">

<svg width="900" height="80" viewBox="0 0 900 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fbg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#020b10"/>
      <stop offset="50%" style="stop-color:#050f1a"/>
      <stop offset="100%" style="stop-color:#020b10"/>
    </linearGradient>
    <linearGradient id="fline" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="30%" style="stop-color:#00ffd5"/>
      <stop offset="50%" style="stop-color:#9b5de5"/>
      <stop offset="70%" style="stop-color:#ff2d78"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  <rect width="900" height="80" fill="url(#fbg)"/>
  <line x1="0" y1="1" x2="900" y2="1" stroke="url(#fline)" stroke-width="1.5"/>
  <circle cx="450" cy="28" r="3" fill="#00ffd5" opacity="0.8">
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="450" y="48" font-family="monospace" font-size="10" fill="#4a7a9b" text-anchor="middle" letter-spacing="3">// KUNAL MEENA · 2025</text>
  <text x="450" y="66" font-family="monospace" font-size="8.5" fill="rgba(0,255,213,0.4)" text-anchor="middle" letter-spacing="2" font-style="italic">Built with obsession, not templates.</text>
</svg>

</div>
