<div align="center">

<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#818cf8"/>
    </linearGradient>

    <radialGradient id="orb1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#38bdf8" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orb2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#818cf8" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#818cf8" stop-opacity="0"/>
    </radialGradient>

    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#38bdf8" stroke-opacity="0.08" stroke-width="1"/>
    </pattern>

    <mask id="gridMask">
      <rect width="1200" height="320" fill="url(#fade)"/>
    </mask>
    <radialGradient id="fade" cx="50%" cy="45%" r="70%">
      <stop offset="0%" stop-color="white"/>
      <stop offset="100%" stop-color="black"/>
    </radialGradient>

    <filter id="blur1"><feGaussianBlur stdDeviation="30"/></filter>

    <style>
      .fadeup { opacity: 0; animation: fadeUp 0.9s ease forwards; }
      .d1 { animation-delay: 0.05s; }
      .d2 { animation-delay: 0.2s; }
      .d3 { animation-delay: 0.4s; }
      .d4 { animation-delay: 0.6s; }
      @keyframes fadeUp {
        from { opacity: 0; transform: translateY(16px); }
        to   { opacity: 1; transform: translateY(0); }
      }
      .cursor { animation: blink 1s step-end infinite; }
      @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0; } }
      .orbA { animation: floatA 9s ease-in-out infinite; }
      .orbB { animation: floatB 11s ease-in-out infinite; }
      @keyframes floatA { 0%,100% { transform: translate(0,0);} 50% { transform: translate(18px,-16px);} }
      @keyframes floatB { 0%,100% { transform: translate(0,0);} 50% { transform: translate(-16px,14px);} }
      .typeline { font-family: 'Courier New', monospace; }
      text { font-family: 'Segoe UI', Arial, sans-serif; }
    </style>
  </defs>

  <!-- background -->
  <rect width="1200" height="320" fill="#080c14"/>
  <rect width="1200" height="320" fill="url(#grid)" mask="url(#gridMask)"/>

  <!-- glow orbs -->
  <circle class="orbA" cx="980" cy="60" r="180" fill="url(#orb1)" filter="url(#blur1)"/>
  <circle class="orbB" cx="180" cy="270" r="160" fill="url(#orb2)" filter="url(#blur1)"/>

  <!-- tag pill -->
  <g class="fadeup d1">
    <rect x="500" y="42" width="200" height="30" rx="15" fill="#38bdf8" fill-opacity="0.10" stroke="#38bdf8" stroke-opacity="0.4"/>
    <text x="600" y="62" text-anchor="middle" fill="#38bdf8" font-size="12" letter-spacing="2" class="typeline">AVAILABLE FOR WORK</text>
  </g>

  <!-- name -->
  <g class="fadeup d2">
    <text x="600" y="140" text-anchor="middle" font-size="58" font-weight="700" letter-spacing="-1">
      <tspan fill="url(#nameGrad)">Yeshan</tspan>
      <tspan fill="#e2e8f0"> Perera</tspan>
    </text>
  </g>

  <!-- typed role line -->
  <g class="fadeup d3">
    <text x="600" y="185" text-anchor="middle" fill="#94a3b8" font-size="18" class="typeline">
      &gt; IT Student | Cybersecurity &amp; Networking Enthusiast<tspan class="cursor" fill="#38bdf8">_</tspan>
    </text>
  </g>

  <!-- bio -->
  <g class="fadeup d4">
    <text x="600" y="225" text-anchor="middle" fill="#64748b" font-size="14">
      Building desktop tools, Discord bots, and learning networking &amp; security along the way.
    </text>
  </g>

  <!-- bottom divider accent -->
  <rect x="560" y="255" width="80" height="3" rx="1.5" fill="url(#nameGrad)" class="fadeup d4"/>
</svg>


<br/>

<img src="https://img.shields.io/badge/Open%20to%20Work-38BDF8?style=flat-square&labelColor=080c14&color=38BDF8" height="26"/>
<img src="https://img.shields.io/badge/Based%20in-Kotte%2C%20Sri%20Lanka-818CF8?style=flat-square&labelColor=080c14&color=818CF8" height="26"/>
<img src="https://komarev.com/ghpvc/?username=YeshanSL&style=flat-square&color=38BDF8&labelColor=080c14" height="26"/>

<br/><br/>

<a href="https://yeshansl.github.io/Yeshan-perera/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-080c14?style=flat-square&logo=googlechrome&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="https://www.linkedin.com/in/yeshan-perera-b5b4ba247/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-080c14?style=flat-square&logo=linkedin&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="mailto:Pdyeshan2005@gmail.com"><img src="https://img.shields.io/badge/Email-080c14?style=flat-square&logo=gmail&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="https://github.com/YeshanSL" target="_blank"><img src="https://img.shields.io/badge/GitHub-080c14?style=flat-square&logo=github&logoColor=38BDF8&labelColor=080c14" height="30"/></a>

</div>

<br/>

<div align="center">
<sub><code>// 01. about</code></sub>
</div>

## Who I Am

I'm **Deneth Yeshan Perera**, an aspiring IT professional from Kotte, Sri Lanka, with a strong interest in **Computer Science, Networking, and Cybersecurity**. I build desktop tools with **PySide6** and Discord bots with **discord.py / discord.js**, and I'm always learning and building something new.

<div align="center">

<img src="https://img.shields.io/badge/21-Years%20Old-080c14?style=flat-square&labelColor=38BDF8&color=080c14"/>
<img src="https://img.shields.io/badge/20+-Certifications-080c14?style=flat-square&labelColor=818CF8&color=080c14"/>
<img src="https://img.shields.io/badge/%F0%9F%87%B1%F0%9F%87%B0-Kotte%2C%20Sri%20Lanka-080c14?style=flat-square&labelColor=38BDF8&color=080c14"/>
<img src="https://img.shields.io/badge/Fluent-Sinhala%20%26%20English-080c14?style=flat-square&labelColor=818CF8&color=080c14"/>

</div>

<br/>

<div align="center">
<sub><code>// 02. stack</code></sub>
</div>

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,js,nodejs,html,git,github,windows,vscode&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/discord.py-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/>
<img src="https://img.shields.io/badge/discord.js-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>
<img src="https://img.shields.io/badge/PySide6%20(Qt)-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/>
<img src="https://img.shields.io/badge/psutil-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>
<img src="https://img.shields.io/badge/PyInstaller-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/>
<img src="https://img.shields.io/badge/WSL-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>

</div>

<br/>

<div align="center">
<sub><code>// 03. projects</code></sub>
</div>

## What I've Built

<table align="center" width="100%">
<tr>
<td width="50%" valign="top">

**🔹 [inputX — Activity & Performance Monitor](https://github.com/YeshanSL/YeshanSL-InputX-Activity---Prefomance-Monitor-)**

<img src="https://img.shields.io/badge/Python-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/> <img src="https://img.shields.io/badge/PySide6-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>

Real-time Windows tray dashboard — live CPU/RAM/disk/GPU graphs, keyboard heatmap, and auto-detection of 30+ games, all in a dark Qt UI.

</td>
<td width="50%" valign="top">

**🔹 [MuteMaster — Discord Voice Bot](https://github.com/YeshanSL/MuteMaster-DiscordBot)**

<img src="https://img.shields.io/badge/Python-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/> <img src="https://img.shields.io/badge/discord.py-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>

Started as a voice-activity tracker, grew into a full Dead by Daylight session manager — killer rotation, ready checks, perk builds, live scoreboard.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔹 [NovaCore Suite — All-in-One Discord Bot](https://github.com/YeshanSL/NovaCore-Discord-Bot)**

<img src="https://img.shields.io/badge/JavaScript-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/> <img src="https://img.shields.io/badge/discord.js-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>

Custom welcome messages, chat & voice leveling, and a Steam stats suite — all on a local JSON file, no database needed.

</td>
<td width="50%" valign="top">

**🔹 [OpenClaw on WSL — Windows 11 Guide](https://github.com/YeshanSL/How-to-install-OpenClaw-with-Wsl-on-Windows-11)**

<img src="https://img.shields.io/badge/WSL-080c14?style=flat-square&labelColor=080c14&color=38BDF8"/> <img src="https://img.shields.io/badge/Guide-080c14?style=flat-square&labelColor=080c14&color=818CF8"/>

A step-by-step guide for getting OpenClaw running on Windows 11 through WSL.

</td>
</tr>
</table>

<div align="center">
<a href="https://github.com/YeshanSL?tab=repositories">
<img src="https://img.shields.io/badge/View%20All%20Repositories-080c14?style=flat-square&logo=github&logoColor=38BDF8&labelColor=080c14&color=080c14" height="30"/>
</a>
</div>

<br/>

<div align="center">
<sub><code>// 04. analytics</code></sub>
</div>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YeshanSL&show_icons=true&theme=react&bg_color=080c14&title_color=38BDF8&icon_color=818CF8&text_color=94a3b8&border_color=818CF8&hide_border=false&count_private=true" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YeshanSL&layout=compact&theme=react&bg_color=080c14&title_color=38BDF8&text_color=94a3b8&border_color=818CF8&hide_border=false" width="41%"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YeshanSL&background=080C14&border=818CF8&stroke=38BDF8&ring=818CF8&fire=38BDF8&currStreakLabel=38BDF8&sideNums=e2e8f0&sideLabels=94a3b8&dates=94a3b8" width="90%"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YeshanSL&bg_color=080c14&color=38BDF8&line=818CF8&point=e2e8f0&area=true&hide_border=true" width="90%"/>

</div>

<br/>

<div align="center">
<sub><code>// 05. currently learning</code></sub>
</div>

<div align="center">

<img src="https://img.shields.io/badge/Cybersecurity%20%26%20Networking-080c14?style=flat-square&labelColor=818CF8&color=080c14"/>
<img src="https://img.shields.io/badge/System%20Design-080c14?style=flat-square&labelColor=38BDF8&color=080c14"/>
<img src="https://img.shields.io/badge/Qt%20%2F%20PySide6-080c14?style=flat-square&labelColor=38BDF8&color=080c14"/>

</div>

<br/><br/>

<div align="center">
<sub><code>// 06. connect</code></sub>
</div>

<div align="center">

## Let's Connect

<a href="https://www.linkedin.com/in/yeshan-perera-b5b4ba247/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-080c14?style=flat-square&logo=linkedin&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="mailto:Pdyeshan2005@gmail.com"><img src="https://img.shields.io/badge/Email-080c14?style=flat-square&logo=gmail&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="tel:+94769292662"><img src="https://img.shields.io/badge/Phone-080c14?style=flat-square&logo=phone&logoColor=38BDF8&labelColor=080c14" height="30"/></a>
<a href="https://yeshansl.github.io/Yeshan-perera/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-080c14?style=flat-square&logo=googlechrome&logoColor=38BDF8&labelColor=080c14" height="30"/></a>

<br/><br/>

<i>⚡ "Code is like humor. When you have to explain it, it's bad." ⚡</i>

</div>
