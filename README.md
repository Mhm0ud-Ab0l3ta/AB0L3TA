<style type="text/css">
<![CDATA[
  @keyframes pulse {
    0%, 100% { transform: scale(1); opacity: 0.9; }
    50% { transform: scale(1.08); opacity: 1; }
  }
  @keyframes ooze {
    0% { d: path("M0,200 Q200,50 400,200 Q600,350 800,200"); }
    50% { d: path("M0,200 Q200,350 400,200 Q600,50 800,200"); }
    100% { d: path("M0,200 Q200,50 400,200 Q600,350 800,200"); }
  }
  @keyframes tendrilWave {
    0% { transform: translateY(0); }
    50% { transform: translateY(-15px); }
    100% { transform: translateY(0); }
  }
  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }
  @keyframes blink {
    50% { border-color: transparent; }
  }
  .typing-text {
    overflow: hidden;
    border-right: 0.15em solid #ff0000;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: 0.05em;
    animation: typing 4s steps(50, end) forwards, blink 0.8s step-end infinite;
  }
]]>
</style>

<div align="center">

<!-- Animated Header SVG -->
<svg width="100%" height="450" viewBox="0 0 900 450" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
  <rect width="900" height="450" fill="#000000"/>

  <!-- Gooey Ooze Filter for Tendrils -->
  <defs>
    <filter id="goo">
      <feGaussianBlur in="SourceGraphic" stdDeviation="12" result="blur"/>
      <feColorMatrix in="blur" type="matrix" values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 19 -8" result="goo"/>
      <feComposite in="SourceGraphic" in2="goo" operator="atop"/>
    </filter>
  </defs>

  <!-- Animated Oozing Tendrils -->
  <g filter="url(#goo)" opacity="0.6">
    <path fill="none" stroke="#0a0a0a" stroke-width="40">
      <animate attributeName="d" dur="20s" repeatCount="indefinite" values="M0,225 Q225,100 450,225 Q675,350 900,225; M0,225 Q225,350 450,225 Q675,100 900,225; M0,225 Q225,100 450,225 Q675,350 900,225"/>
    </path>
    <path fill="none" stroke="#0f0f0f" stroke-width="30" style="animation: tendrilWave 15s infinite ease-in-out;">
      <animate attributeName="d" dur="18s" repeatCount="indefinite" values="M0,250 Q300,50 600,250 Q900,450 900,250; M0,250 Q300,450 600,250 Q900,50 900,250; M0,250 Q300,50 600,250 Q900,450 900,250"/>
    </path>
  </g>

  <!-- Pulsing Symbiote Spider Logo (Black Suit + Venom Style) -->
  <g transform="translate(450,225)" style="animation: pulse 6s infinite ease-in-out;">
    <!-- Main Body + Drooping Legs -->
    <path fill="#ffffff" d="M0,-110 Q-40,-70 -60,-20 Q-80,30 -70,80 Q-50,120 0,140 Q50,120 70,80 Q80,30 60,-20 Q40,-70 0,-110 Z 
                              M-30,-50 L-35,0 L-70,0 Q-60,40 -40,60 
                              M30,-50 L35,0 L70,0 Q60,40 40,60 
                              M-50,20 L-30,60 L0,50 L30,60 L50,20"/>
    <!-- Vertical Veins -->
    <path fill="none" stroke="#000000" stroke-width="8" opacity="0.4" d="M-25,-60 L-25,60 M25,-60 L25,60 M0,-80 L0,80"/>
  </g>

  <!-- Glowing Venom Eyes -->
  <ellipse cx="370" cy="160" rx="45" ry="70" fill="#ffffff" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="530" cy="160" rx="45" ry="70" fill="#ffffff" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/>
  </ellipse>

</svg>

<h1 style="color:#ffffff; font-family: monospace; font-size: 3em; text-shadow: 0 0 20px #ff0000; margin-top: -50px;">
  We are <span style="color:#ff0000;">AB0L3TA</span> 🕷️🖤
</h1>

<p class="typing-text" style="color:#ff0000; font-family: monospace; font-size: 1.8em; max-width: 800px;">
  Symbiote-powered developer | Bonding with the darkness...
</p>

<p style="color:#aaaaaa; max-width: 700px; margin: 20px auto;">
  Cybersecurity enthusiast • Web hacker • Open-source symbiote spreading through code.
</p>

</div>

<br>

<!-- Tech Stack -->
<div align="center">
  <h2 style="color:#ff0000; text-shadow: 0 0 10px #ff0000;">🕸️ Tech Stack</h2>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" alt="Kali"/>
  <!-- Add more badges as needed -->
</div>

<br>

<!-- GitHub Stats (Dracula theme for dark/Venom vibe) -->
<div align="center">
  <h2 style="color:#ff0000; text-shadow: 0 0 10px #ff0000;">📊 GitHub Stats</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=Mhm0ud-Ab0l3ta&theme=dracula&hide_border=true&count_private=true&show_icons=true" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mhm0ud-Ab0l3ta&theme=dracula&hide_border=true&layout=compact" alt="Top Languages"/>
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mhm0ud-Ab0l3ta&theme=dracula&hide_border=true" alt="Streak Stats"/>
</div>

<br>

<!-- Trophies -->
<div align="center">
  <h2 style="color:#ff0000; text-shadow: 0 0 10px #ff0000;">🏆 Trophies</h2>
  <img src="https://github-profile-trophy.vercel.app/?username=Mhm0ud-Ab0l3ta&theme=dracula&no-frame=true&margin-w=15" alt="Trophies"/>
</div>

<br>

<!-- Visitor Badge -->
<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Mhm0ud-Ab0l3ta.Mhm0ud-Ab0l3ta&format=shield" alt="Visitors"/>
</div>

<br>

<!-- Connect -->
<div align="center">
  <h2 style="color:#ff0000; text-shadow: 0 0 10px #ff0000;">🤝 Connect</h2>
  <!-- Replace with your links -->
  <a href="https://twitter.com/yourhandle"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/></a>
  <a href="https://linkedin.com/in/yourhandle"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</div>

<div align="center" style="margin-top: 50px; color:#555;">
  <p>"We... are... inevitable." 🖤</p>
</div>
