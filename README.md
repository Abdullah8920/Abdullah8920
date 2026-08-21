<div align="center">

<svg width="1200" height="300" viewBox="0 0 1200 300"
     xmlns="http://www.w3.org/2000/svg">

  <defs>

    <!-- Main gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0F172A"/>
      <stop offset="45%" stop-color="#1E3A8A"/>
      <stop offset="100%" stop-color="#06B6D4"/>
    </linearGradient>

    <!-- Animated glow -->
    <radialGradient id="glow">
      <stop offset="0%" stop-color="#67E8F9" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#67E8F9" stop-opacity="0"/>
    </radialGradient>

    <!-- Grid -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40"
            fill="none"
            stroke="#ffffff"
            stroke-opacity="0.06"
            stroke-width="1"/>
    </pattern>

    <!-- Clip -->
    <clipPath id="rounded">
      <rect width="1200" height="300" rx="18"/>
    </clipPath>

  </defs>

  <g clip-path="url(#rounded)">

    <!-- Background -->
    <rect width="1200" height="300" fill="url(#bg)"/>

    <!-- Grid -->
    <rect width="1200" height="300" fill="url(#grid)"/>

    <!-- Moving glow -->
    <circle cx="-100" cy="80" r="220" fill="url(#glow)">
      <animate
        attributeName="cx"
        values="-100;1300;-100"
        dur="9s"
        repeatCount="indefinite"/>
    </circle>

    <!-- Floating glow -->
    <circle cx="950" cy="100" r="160" fill="url(#glow)" opacity="0.5">
      <animate
        attributeName="cy"
        values="100;180;100"
        dur="5s"
        repeatCount="indefinite"/>
    </circle>

    <!-- Decorative dots -->
    <g fill="#ffffff" opacity="0.45">
      <circle cx="100" cy="80" r="2">
        <animate attributeName="opacity"
                 values="0.2;1;0.2"
                 dur="2s"
                 repeatCount="indefinite"/>
      </circle>

      <circle cx="1080" cy="70" r="2">
        <animate attributeName="opacity"
                 values="1;0.2;1"
                 dur="3s"
                 repeatCount="indefinite"/>
      </circle>

      <circle cx="980" cy="210" r="2">
        <animate attributeName="opacity"
                 values="0.2;1;0.2"
                 dur="2.5s"
                 repeatCount="indefinite"/>
      </circle>

      <circle cx="180" cy="210" r="2">
        <animate attributeName="opacity"
                 values="1;0.2;1"
                 dur="3.5s"
                 repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- Main heading -->
    <text
      x="600"
      y="115"
      text-anchor="middle"
      fill="white"
      font-family="Arial, Helvetica, sans-serif"
      font-size="48"
      font-weight="700">
      Hi, I'm Abdullah
    </text>

    <!-- Subtitle -->
    <text
      x="600"
      y="155"
      text-anchor="middle"
      fill="#CFFAFE"
      font-family="Arial, Helvetica, sans-serif"
      font-size="20"
      font-weight="500">
      Full Stack Web Developer
    </text>

    <!-- Small animated line -->
    <rect
      x="500"
      y="178"
      width="200"
      height="2"
      rx="2"
      fill="#67E8F9">

      <animate
        attributeName="width"
        values="80;240;80"
        dur="3s"
        repeatCount="indefinite"/>

      <animate
        attributeName="x"
        values="560;480;560"
        dur="3s"
        repeatCount="indefinite"/>
    </rect>

    <!-- Bottom wave -->
    <path
      d="M0 245
         C180 205 300 285 480 245
         C650 205 800 280 980 235
         C1080 210 1140 230 1200 215
         L1200 300
         L0 300 Z"
      fill="#020617"
      opacity="0.75">

      <animate
        attributeName="d"
        dur="7s"
        repeatCount="indefinite"
        values="
        M0 245 C180 205 300 285 480 245 C650 205 800 280 980 235 C1080 210 1140 230 1200 215 L1200 300 L0 300 Z;
        M0 220 C180 270 300 200 480 230 C650 270 800 205 980 250 C1080 270 1140 235 1200 245 L1200 300 L0 300 Z;
        M0 245 C180 205 300 285 480 245 C650 205 800 280 980 235 C1080 210 1140 230 1200 215 L1200 300 L0 300 Z
        "/>
    </path>

  </g>

</svg>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=06B6D4&center=true&vCenter=true&width=650&lines=Building+Modern+Web+Applications;React+%7C+Next.js+%7C+Node.js+%7C+MongoDB;Turning+Ideas+Into+Interfaces" />

<br/>

<a href="YOUR_WHATSAPP">
<img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<a href="mailto:YOUR_EMAIL">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="YOUR_PORTFOLIO">
<img src="https://img.shields.io/badge/Portfolio-06B6D4?style=for-the-badge&logo=vercel&logoColor=white"/>
</a>

<a href="YOUR_LINKEDIN">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>

---
## 👨‍💻 About Me

I'm a Full Stack Web Developer focused on building modern, responsive and
scalable web applications.

I enjoy working with **React, Next.js, Node.js and MongoDB**, creating clean
interfaces and connecting them with reliable backend APIs.

> 🚀 Learn → Build → Break → Fix → Repeat
## 🛠️ Tech Stack

### 💻 Frontend

<p>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
<img src="https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white"/>
</p>

### ⚙️ Backend

<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white"/>
</p>

### 🗄️ Database & Services

<p>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
</p>

### 🎨 UI & Styling

<p>
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Responsive_Design-111111?style=flat-square&logo=css3&logoColor=white"/>
</p>

### 🔧 Tools

<p>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

![](https://github-readme-stats.shion.dev/api/top-langs/?username=Abdullah8920&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)


---

