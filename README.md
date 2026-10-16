<!--
╔══════════════════════════════════════════════════════════════════════╗
║  SETUP                                                               ║
║  1. Replace every "abhinav-swe" with your GitHub username            ║
║  2. Add your illustration/photo at assets/profile.png                ║
║  3. Create .github/workflows/snake.yml (copy it from the comment     ║
║     in the "GitHub Analytics" section) and run it once              ║
║                                                                      ║
║  COLOR COMBOS (find & replace hex codes across the file)             ║
║  1 · OCEAN BLUE (default)  03010a / 1e7cb3 / 7cc4ee                  ║
║  2 · ROYAL VIOLET          0d0221 / 8b5cf6 / c4b5fd                  ║
║  3 · EMERALD MINT          04110d / 10b981 / 6ee7b7                  ║
╚══════════════════════════════════════════════════════════════════════╝
-->

<!-- ═══════════════════ ANIMATED BANNER (LIGHT / DARK) ═══════════════════ -->
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:03010a,50:0b3a5c,100:1e7cb3&height=260&section=header&text=Abhinav%20Swe&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Full-stack%20developer&descSize=22&descAlignY=58&animation=fadeIn">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:7cc4ee,50:3b9ad1,100:1e7cb3&height=260&section=header&text=Abhinav%20Swe&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Full-stack%20developer&descSize=22&descAlignY=58&animation=fadeIn">
  <img alt="Profile banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:03010a,50:0b3a5c,100:1e7cb3&height=260&section=header&text=Abhinav%20Swe&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Full-stack%20developer&descSize=22&descAlignY=58&animation=fadeIn" width="100%">
</picture>

<!-- ═══════════════════ TITLE ═══════════════════ -->
<h1 align="center">Hey there, I'm Abhinav <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="32" alt="wave" /></h1>

<!-- ═══════════════════ TYPING ANIMATION ═══════════════════ -->
<a href="https://github.com/abhinav-swe">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2800&pause=900&color=7CC4EE&center=true&vCenter=true&repeat=true&width=640&height=60&lines=Full+Stack+Developer+%F0%9F%9A%80;Software+Engineer+%F0%9F%92%BB;Open+Source+Enthusiast+%F0%9F%8C%8D;Building+things+that+matter+%E2%9C%A8" alt="Typing SVG" />
</a>

<br><br>

<!-- ═══════════════════ BADGES ═══════════════════ -->
<a href="https://github.com/abhinav-swe?tab=followers">
  <img src="https://img.shields.io/github/followers/abhinav-swe?style=for-the-badge&logo=github&logoColor=white&label=FOLLOWERS&labelColor=3b4048&color=1e7cb3" alt="Followers" />
</a>
<a href="https://github.com/abhinav-swe?tab=repositories">
  <img src="https://img.shields.io/github/stars/abhinav-swe?style=for-the-badge&logo=github&logoColor=white&label=STARS&labelColor=3b4048&color=1e7cb3" alt="Stars" />
</a>
<a href="https://github.com/abhinav-swe">
  <img src="https://komarev.com/ghpvc/?username=abhinav-swe&style=for-the-badge&label=VIEWS&labelColor=3b4048&color=1e7cb3" alt="Profile Views" />
</a>

</div>

<br>

<!-- ═══════════════════ ABOUT ME ═══════════════════ -->
<h2 align="center">🧑‍💻 About Me</h2>

<table align="center" width="100%">
  <tr>
    <td width="65%" valign="middle">
      <ul>
        <li>💻 Full Stack Developer passionate about building modern web apps.</li>
        <li>🌱 Currently learning System Design, Cloud &amp; DevOps.</li>
        <li>🚀 Building AI-powered projects and contributing to Open Source.</li>
        <li>🎯 Goal: Create products that solve real-world problems.</li>
        <li>🎨 Passionate about AI, design, and building things that matter.</li>
        <li>✨ Always chasing the next idea worth building.</li>
      </ul>
    </td>
    <td width="35%" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/abhinav-swe/abhinav-swe/main/assets/profile.png" alt="Abhinav" width="200" />
    </td>
  </tr>
</table>

<!-- ═══════════════════ TECH STACK (ANIMATED ICONS) ═══════════════════ -->
<h2 align="center">💻 Tech Stack</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,nodejs,express,python,django,postgres,mongodb,tailwind,git,github,docker,vscode,figma,postman,linux,bash,npm,vercel,redis&perline=12&theme=dark" alt="Tech Stack" />
</p>

<!-- ═══════════════════ GITHUB ANALYTICS ═══════════════════ -->
<h2 align="center">📈 GitHub Analytics</h2>

<!--
  ══════════════ SNAKE RUNNING THROUGH THE STREAK BOX ══════════════
  GitHub cannot overlay one image on another, so this workflow downloads your
  streak card as an SVG, injects an animated snake into it, and saves it as
  streak-snake.svg. It also generates the contribution graph snake.

  Create .github/workflows/snake.yml with:

  name: Generate Snakes
  on:
    schedule:
      - cron: "0 */6 * * *"
    workflow_dispatch:
    push:
      branches:
        - main
  permissions:
    contents: write
  jobs:
    generate:
      runs-on: ubuntu-latest
      timeout-minutes: 10
      steps:
        - name: Contribution snake
          uses: Platane/snk/svg-only@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-snake.svg
              dist/github-snake-dark.svg?palette=github-dark&color_snake=#1e7cb3&color_dots=#0b1f2e,#0e4a6e,#1e7cb3,#3b9ad1,#7cc4ee

        - name: Streak card with animated snake
          run: |
            mkdir -p dist
            curl -sL "https://streak-stats.demolab.com/?user=${{ github.repository_owner }}&theme=dark&background=03010a&border=1e7cb3&stroke=1e7cb3&ring=1e7cb3&fire=1e7cb3&currStreakNum=FFFFFF&currStreakLabel=7CC4EE&sideNums=FFFFFF&sideLabels=7CC4EE&dates=8B949E" -o dist/streak.svg
            cat > snake.frag <<'EOF'
            <g fill="none" stroke-linecap="round" stroke-linejoin="round">
              <path d="M12,12 H483 V183 H12 Z" pathLength="100" stroke="#1e7cb3" stroke-width="5" stroke-dasharray="14 86" stroke-opacity="0.9">
                <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="7s" repeatCount="indefinite"/>
              </path>
              <path d="M12,12 H483 V183 H12 Z" pathLength="100" stroke="#7cc4ee" stroke-width="7" stroke-dasharray="2 98">
                <animate attributeName="stroke-dashoffset" from="-12" to="-112" dur="7s" repeatCount="indefinite"/>
              </path>
              <path d="M12,97 C60,40 110,154 160,97 S260,40 310,97 S410,154 483,97" pathLength="100" stroke="#1e7cb3" stroke-width="4" stroke-dasharray="10 90" stroke-opacity="0.55">
                <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="5s" repeatCount="indefinite"/>
              </path>
              <path d="M12,97 C60,40 110,154 160,97 S260,40 310,97 S410,154 483,97" pathLength="100" stroke="#7cc4ee" stroke-width="6" stroke-dasharray="1.5 98.5" stroke-opacity="0.8">
                <animate attributeName="stroke-dashoffset" from="-10" to="-110" dur="5s" repeatCount="indefinite"/>
              </path>
            </g>
            EOF
            python3 - <<'PY'
            svg = open("dist/streak.svg").read()
            frag = open("snake.frag").read()
            head, _, tail = svg.rpartition("</svg>")
            open("dist/streak-snake.svg", "w").write(head + frag + "</svg>" + tail)
            PY
            rm dist/streak.svg snake.frag

        - name: Push to output branch
          uses: crazy-max/ghaction-github-pages@v3.1.0
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  After committing: Actions → "Generate Snakes" → Run workflow (once).
  Tip: if the injected snake looks misaligned, tweak the path coordinates in the
  workflow (the card is 495 x 195).
-->

<div align="center">

<!-- Streak box with animated snake running through it -->
<img src="https://raw.githubusercontent.com/abhinav-swe/abhinav-swe/output/streak-snake.svg" alt="GitHub Streak with animated snake" width="85%" />

<br><br>

<!-- Activity graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=abhinav-swe&bg_color=03010a&color=7cc4ee&line=1e7cb3&point=FFFFFF&area=true&area_color=1e7cb3&hide_border=true&radius=10" alt="Activity Graph" width="95%" />

</div>

<br>

<!-- ═══════════════════ CONTRIBUTION GRAPH (SNAKE) ═══════════════════ -->
<h2 align="center">🐍 Contribution Graph</h2>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abhinav-swe/abhinav-swe/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/abhinav-swe/abhinav-swe/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/abhinav-swe/abhinav-swe/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

<!-- ═══════════════════ LET'S CONNECT ═══════════════════ -->
<h2 align="center">🌐 Let's Connect</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/abhinav-swe"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/abhinav_swe"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.instagram.com/abhinav.swe"><img src="https://img.shields.io/badge/INSTAGRAM-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://www.tiktok.com/@abhinav.swe"><img src="https://img.shields.io/badge/TIKTOK-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" /></a>
  <a href="https://www.youtube.com/@abhinav-swe"><img src="https://img.shields.io/badge/YOUTUBE-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="mailto:abhinav@example.com"><img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=3500&pause=1200&color=1E7CB3&center=true&vCenter=true&width=420&height=30&lines=Thanks+for+stopping+by+%F0%9F%92%99;Feel+free+to+%E2%AD%90+a+repo+or+say+hi!" alt="Thanks" />
</p>

<!-- ═══════════════════ PINK WAVING FOOTER ═══════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff9ecf,50:ef93c4,100:ec4899&height=180&section=footer&animation=twinkling" alt="Footer" width="100%" />
</p>
