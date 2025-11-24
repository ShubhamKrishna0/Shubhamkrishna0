<!-- =======================
     Shubham Krishna — All-in-One Animated README
     Paste this entire single block into README.md
     ======================= -->

<!-- Animated Header (capsule-render SVG) -->
<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/kyechan99/capsule-render/master/dist/github.svg?text=Shubham%20Krishna&fontColor=ffffff&type=waving&fontSize=60&color=0:0f172a,100:0ea5e9&height=240" alt="Shubham Krishna Banner" />
</p>

<p align="center">
  <img alt="Intro GIF" src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="180" style="border-radius:12px;" />
</p>

<h1 align="center">👋 Hi, I'm <strong>Shubham Krishna</strong></h1>
<p align="center">Third-year CSE • Full-Stack • Mobile • Cloud • Always building ✨</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Bhubaneswar%2C%20India-ff69b4?style=for-the-badge" alt="location" />
  <img src="https://img.shields.io/badge/Role-Student%20%26%20FullStack-blueviolet?style=for-the-badge" alt="role" />
  <img src="https://img.shields.io/badge/Looking%20for-Internships-green?style=for-the-badge" alt="looking" />
</p>

---

<!-- Floating particle animated background as an inline SVG (no JS) -->
<div align="center">
  <!-- Inline animated SVG: floating/particle background -->
  <!-- Uses SMIL animate and prefers-color-scheme for dark/light -->
  <svg width="100%" height="140" viewBox="0 0 1200 140" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="bgGrad" x1="0%" x2="100%">
        <stop offset="0%" stop-color="#0f172a" />
        <stop offset="100%" stop-color="#001219" />
      </linearGradient>
      <linearGradient id="bgGradLight" x1="0%" x2="100%">
        <stop offset="0%" stop-color="#e0f2fe" />
        <stop offset="100%" stop-color="#f0f9ff" />
      </linearGradient>
      <style type="text/css"><![CDATA[
        @media (prefers-color-scheme: light) {
          .bg { fill: url(#bgGradLight); }
          .dot { fill: rgba(6, 95, 70, 0.85); }
        }
        @media (prefers-color-scheme: dark) {
          .bg { fill: url(#bgGrad); }
          .dot { fill: rgba(0,230,255,0.85); }
        }
      ]]></style>
    </defs>

    <rect class="bg" x="0" y="0" width="1200" height="140" rx="8" />

    <!-- Particles: small circles that float up and down via SMIL -->
    <!-- We create a few repeating circles with different speeds -->
    <g transform="translate(80,60)">
      <circle class="dot" cx="0" cy="0" r="4" opacity="0.9">
        <animate attributeName="cy" dur="6s" values="0; -18; 0" repeatCount="indefinite" />
        <animate attributeName="cx" dur="8s" values="0; 40; -10; 0" repeatCount="indefinite" />
      </circle>
    </g>

    <g transform="translate(260,40)">
      <circle class="dot" cx="0" cy="0" r="6" opacity="0.7">
        <animate attributeName="cy" dur="5s" values="0; -22; 0" repeatCount="indefinite" />
        <animate attributeName="cx" dur="9s" values="0; -30; 10; 0" repeatCount="indefinite" />
      </circle>
    </g>

    <g transform="translate(480,80)">
      <circle class="dot" cx="0" cy="0" r="5" opacity="0.85">
        <animate attributeName="cy" dur="7s" values="0; -16; 0" repeatCount="indefinite" />
        <animate attributeName="cx" dur="6s" values="0; 20; -7; 0" repeatCount="indefinite" />
      </circle>
    </g>

    <g transform="translate(760,50)">
      <circle class="dot" cx="0" cy="0" r="7" opacity="0.6">
        <animate attributeName="cy" dur="8s" values="0; -26; 0" repeatCount="indefinite" />
        <animate attributeName="cx" dur="7s" values="0; -40; 12; 0" repeatCount="indefinite" />
      </circle>
    </g>

    <g transform="translate(1000,70)">
      <circle class="dot" cx="0" cy="0" r="5" opacity="0.8">
        <animate attributeName="cy" dur="6.5s" values="0; -20; 0" repeatCount="indefinite" />
        <animate attributeName="cx" dur="9.5s" values="0; 32; -9; 0" repeatCount="indefinite" />
      </circle>
    </g>
  </svg>
</div>

---

## 🔧 Tech Snapshot (3D rotating skill icons)
<!-- Inline SVG with rotating group of skill icons using animateTransform (no JS) -->
<div align="center">
  <svg width="760" height="140" viewBox="0 0 760 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Rotating tech icons">
    <style><![CDATA[
      .card { fill: rgba(255,255,255,0.02); stroke: rgba(255,255,255,0.06); stroke-width:0; rx:14; }
      .label { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; font-size:12px; fill:#e6eef8; text-anchor:middle; }
      @media (prefers-color-scheme: light) {
        .label { fill: #0f172a; }
      }
    ]]></style>

    <!-- background rounded -->
    <rect x="10" y="8" width="740" height="124" rx="12" class="card" />

    <!-- rotating group centered horizontally -->
    <g transform="translate(380,70)">
      <!-- animateTransform rotates group slowly for 3D-like effect -->
      <animateTransform attributeName="transform"
                        type="rotate"
                        values="0 0 0; 360 0 0"
                        dur="18s"
                        repeatCount="indefinite" />
      <!-- icons as small images placed circularly -->
      <!-- Replace any of these hrefs with your custom icons if needed -->
      <g transform="translate(-260,-18)">
        <image href="https://skillicons.dev/icons?i=react" width="56" height="56" x="0" y="0" style="border-radius:8px;" />
        <text x="28" y="72" class="label">React</text>
      </g>

      <g transform="translate(-150,-40)">
        <image href="https://skillicons.dev/icons?i=next" width="56" height="56" x="0" y="0" />
        <text x="28" y="72" class="label">Next.js</text>
      </g>

      <g transform="translate(-40,-18)">
        <image href="https://skillicons.dev/icons?i=nodejs" width="56" height="56" x="0" y="0" />
        <text x="28" y="72" class="label">Node.js</text>
      </g>

      <g transform="translate(70,-40)">
        <image href="https://skillicons.dev/icons?i=nestjs" width="56" height="56" x="0" y="0" />
        <text x="28" y="72" class="label">NestJS</text>
      </g>

      <g transform="translate(180,-18)">
        <image href="https://skillicons.dev/icons?i=prisma" width="56" height="56" x="0" y="0" />
        <text x="28" y="72" class="label">Prisma</text>
      </g>

      <g transform="translate(290,-40)">
        <image href="https://skillicons.dev/icons?i=docker" width="56" height="56" x="0" y="0" />
        <text x="28" y="72" class="label">Docker</text>
      </g>
    </g>
  </svg>
</div>

---

## 📈 GitHub Activity & Commits

<div align="center">

<!-- GitHub Stats + Top languages -->
<img src="https://github-readme-stats.vercel.app/api?username=ShubhamKrishna0&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true" height="160" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShubhamKrishna0&layout=compact&theme=tokyonight" height="160" alt="Top languages" />

</div>

<p align="center">
  <!-- yearly commits badge (live) -->
  <img src="https://badges.pufler.dev/commits/yearly/ShubhamKrishna0" alt="Commits this year" />
  &nbsp;&nbsp;
  <!-- Contribution snake -->
  <img src="https://raw.githubusercontent.com/Platane/snk/master/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />
</p>

> ✅ **Total commits this year:** ![](https://badges.pufler.dev/commits/yearly/ShubhamKrishna0)  
> (Badge above updates automatically.)

---

## 🚀 Featured Projects

| Project | What I built | Tech |
|---|---:|---|
| **Ecomly_Backend** | E-commerce backend: auth, cart, orders, payments | Node.js · Express · MongoDB |
| **Foodly** | Mobile + web app for food ordering | Flutter · Dart · Node.js |
| **Taskly** | Real-time task manager (ongoing) | Next.js · NestJS · Prisma · PostgreSQL |
| **Auth Demo** | Authentication flows & security patterns | HTML/CSS/JS · OAuth · JWT |

🔗 See all repos: https://github.com/ShubhamKrishna0?tab=repositories

---

## 🌱 Currently Learning
- Cloud-native design & Kubernetes  
- Microservices & event-driven architecture  
- Performance engineering & advanced frontend animations

---

## 📬 Contact
- ✉️ krishnashubham09@gmail.com  
- LinkedIn: https://www.linkedin.com/in/shubham0  
- Twitter/X: https://x.com/_shubhamkrishna  
- Instagram: https://www.instagram.com/shhubham.__

---

<p align="center">
  <img width="100%" src="https://raw.githubusercontent.com/kyechan99/capsule-render/master/dist/footer.svg?color=0:001219,100:00eaff&height=80" alt="footer" />
</p>

<!-- End of README -->
