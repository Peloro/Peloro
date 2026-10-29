<h1 align="center">Pedro Louro Fernandes</h1>
<p align="center">
  <b>Full-Stack Developer · Computer Science @ ICMC-USP · Robotics & Data</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pedro-louro-fernandes/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:plf@outlook.com.br"><img src="https://img.shields.io/badge/Email-plf%40outlook.com.br-1d4e89?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
</p>

---

### About me

- I build and maintain **InPlay**, a production SaaS for live baseball scoring and team analytics, on my own: product, front end, back end, mobile and operations.
- At **Warthog Robotics** (USP), I develop locomotion software for assistive autonomous robots: navigation, obstacle avoidance and motion control with ROS.
- I study Computer Science at the **University of São Paulo (ICMC)**. My interests are software engineering, data and applied AI.
- I like turning complex domain rules into reliable, well-tested systems.

---

### Featured project

#### [InPlay Baseball Analytics](https://github.com/Peloro/InPlay-Baseball-Analytics) · *Founder & Full-Stack Developer (2026 – present)*

A multi-tenant SaaS for amateur baseball clubs to score games live and track season statistics. It runs on the web and as an Android app.

- **Offline-first:** all data lives in IndexedDB and syncs in the background, with idempotent request replay and conflict-safe merging across devices. Scoring keeps working in dugouts with no signal.
- **Rules engine:** every play is recorded in an event log, and the whole game state can be rewound to any play. The app derives batting and pitching stats (AVG, OBP, OPS, ERA, WHIP), spray charts and pitch heatmaps.
- **Real SaaS:** 4-tier plan ladder with Mercado Pago billing (one-off and recurring), JWT auth with team invites, TOTP 2FA, Firebase push notifications and transactional e-mail.
- **Engineering:** unit and integration tests (Vitest, in-memory MongoDB), Playwright E2E with WCAG accessibility checks, GitHub Actions CI/CD with signed APK builds, Sentry monitoring, and a UI in Portuguese, English and Spanish.

`TypeScript` `React` `Node.js` `Express` `MongoDB` `IndexedDB` `Capacitor` `Vitest` `Playwright` `GitHub Actions`

---

### Other projects

**[CacoAI: AI Personal Finance Assistant](https://github.com/Peloro/CacoAI)**
A chat bot that logs expenses and income from plain, natural-language messages ("spent 30 on lunch") and turns them into categorized, structured records, then answers questions about the user's spending. Before choosing a model, I benchmarked local LLMs (Llama) against hosted APIs (Gemini, OpenAI, Claude) on classification quality and cost per message, and picked Gemini for the best balance. The MVP runs on Telegram, after I found the official WhatsApp API too costly for an AI bot at this stage.
`LLMs` `Gemini API` `Groq` `Llama` `Telegram Bot API`

**[Overtone: Volume Overlay for Windows](https://github.com/Peloro/overtone-volume-overlay)**
A lightweight, always-on-top volume mixer with per-application and system-wide control. Features include global hotkeys, app filtering, themes, profiles and system tray integration. It is built on the Windows audio APIs with an event-driven desktop architecture.
`Python` `PyQt5` `Windows Core Audio`

**[Robot with Computer Vision and Speech Recognition](https://github.com/EnzoTM/R2_D2)**
A team project presented at the USP Undergraduate Research Symposium (SIICUSP 2023), which added computer vision and speech recognition to a robot driven by an ESP-32. I wrote the embedded C++ firmware for its communication and navigation. ([certificate](https://drive.google.com/file/d/1yw5TbL3bTsvKT0r6YJKZV02f3wh_FrvR/view))
`C++` `ESP-32` `Computer Vision` `CNNs`

**[Apartment Complex Online Store](https://github.com/joaopgodoy/online_store_project)**
A full-stack store with product listing, registration and session-based authentication, shopping cart and order placement. It uses a modular REST back end on a NoSQL database.
`Node.js` `Express` `MongoDB` `EJS`

---

### Tech stack

**Languages**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" title="TypeScript">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="40" height="40" alt="C" title="C">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" height="40" alt="C++" title="C++">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" height="40" alt="Java" title="Java">
</p>

**Full-stack & mobile**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40" alt="React" title="React">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" title="Node.js">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="40" height="40" alt="MongoDB" title="MongoDB">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" title="PostgreSQL">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" title="HTML5">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" title="CSS3">
</p>

**Data & AI**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="40" height="40" alt="PyTorch" title="PyTorch">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="40" height="40" alt="TensorFlow" title="TensorFlow">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" width="40" height="40" alt="OpenCV" title="OpenCV">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="40" height="40" alt="NumPy" title="NumPy">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" height="40" alt="Pandas" title="Pandas">
</p>

**DevOps, tooling & robotics**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" width="40" height="40" alt="GitHub Actions" title="GitHub Actions">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" alt="Git" title="Git">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="40" height="40" alt="Linux" title="Linux">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ros/ros-original.svg" width="40" height="40" alt="ROS" title="ROS">
</p>

---

<p align="center"><i>Open to conversations about software engineering, full-stack and data roles. Feel free to reach out.</i></p>
