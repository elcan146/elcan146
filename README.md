<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,55:0f2a3d,100:1f6feb&height=200&section=header&text=Elcan%20%C4%B0smay%C4%B1lov&fontSize=52&fontColor=e6edf3&fontAlignY=38&animation=fadeIn&desc=Full-Stack%20Engineer%20%E2%80%94%20Real-Time%20Systems%2C%20RF%20and%20Signal%20Processing&descSize=17&descAlignY=60&descColor=8b949e" alt="Elcan İsmayılov" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=19&duration=3200&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=Full-Stack+Engineer+%E2%80%94+Python%2C+FastAPI%2C+React;Real-time+systems+and+hardware-software+integration;SDR+monitoring+of+FM+and+DAB%2B+broadcast+bands;Senior+Engineer+at+AzTV" alt="Typing summary" />
</p>

<p align="center">
  <a href="https://elcanismayilov.com"><img src="https://img.shields.io/badge/Website-elcanismayilov.com-1f6feb?style=flat-square&labelColor=0d1117" alt="Website" /></a>
  <a href="mailto:me@elcanismayilov.com"><img src="https://img.shields.io/badge/Email-me@elcanismayilov.com-1f6feb?style=flat-square&labelColor=0d1117" alt="Email" /></a>
  <a href="mailto:elcanismayilov@proton.me"><img src="https://img.shields.io/badge/Proton-elcanismayilov@proton.me-1f6feb?style=flat-square&labelColor=0d1117&logo=protonmail&logoColor=white" alt="Proton Mail" /></a>
  <img src="https://img.shields.io/badge/Location-Baku%2C%20Azerbaijan-1f6feb?style=flat-square&labelColor=0d1117" alt="Location" />
</p>

<br/>

### About

Full-Stack Engineer specializing in **real-time systems** and **hardware-software integration**. Background in telecommunication engineering and information security, with hands-on experience in digital signal processing, system architecture and modern user interfaces. I build end-to-end data pipelines and monitoring platforms, and I work day to day on broadcast and satellite infrastructure as a Senior Engineer at AzTV.

<br/>

### Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/elcan146/CGrep-v3">CGrep</a></h4>
      <sub>Real-time SDR radio monitoring platform</sub>
      <ul>
        <li>RTL-SDR sweeps of the FM and DAB+ bands with live WFM demodulation and RDS decoding.</li>
        <li>Remote collector agents stream sweeps to a central FastAPI and PostgreSQL backend.</li>
        <li>3D tactical dashboard in React Three Fiber, with live spectrum over WebSocket.</li>
        <li>Self-hosted Ollama assistant, WebAuthn passkeys, JWT and RBAC.</li>
        <li>Desktop GUI with spectrum and waterfall views, WhatsApp alerts, S3 backups, PDF reports and an EN/AZ interface.</li>
        <li>In deployment: 7 regional SDRs, ~700 measurements/s, ~2.5M records/day, 75 ms dashboard queries.</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/React%2019-161b22?style=flat-square&logo=react&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Three.js-161b22?style=flat-square&logo=threedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/PyQt6-161b22?style=flat-square&logo=qt&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/elcan146/CClip">CClip</a></h4>
      <sub>AI-powered cinematic clip engine</sub>
      <ul>
        <li>Local Whisper transcription, with Gemini choosing the key moments, titles and hooks.</li>
        <li>9:16 reframe, karaoke-style ASS subtitles (including Azerbaijani), Edge-TTS voiceover and music mixing.</li>
        <li>FFmpeg rendering, automated YouTube upload and an analytics dashboard in a PyQt6 desktop app.</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Gemini-161b22?style=flat-square&logo=googlegemini&logoColor=white" />
      <img src="https://img.shields.io/badge/Whisper-161b22?style=flat-square&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/FFmpeg-161b22?style=flat-square&logo=ffmpeg&logoColor=white" />
      <img src="https://img.shields.io/badge/PyQt6-161b22?style=flat-square&logo=qt&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/elcan146/radiogrep">radiogrep</a></h4>
      <sub>RF jamming detection on the 433 MHz ISM band</sub>
      <ul>
        <li>Reduces each FFT window to five spectral features: power, flatness, noise floor, peak and RSSI.</li>
        <li>A Random Forest classifies each window as clean or jammed, with live monitoring from an ADALM-Pluto or simulated input.</li>
        <li>Runs end to end on synthetic IQ data and exports KPIs, ROC curves and an alarm log to Excel.</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/scikit--learn-161b22?style=flat-square&logo=scikitlearn&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-161b22?style=flat-square&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/ADALM--Pluto-161b22?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/elcan146/GoW">Grails of War</a></h4>
      <sub>Digital card game prototype</sub>
      <ul>
        <li>Simultaneous secret turns across three locations, best of three rounds.</li>
        <li>Monorepo: a web client (React, Vite and Phaser) and a mobile client (React Native and Expo) share one pure-TypeScript game engine.</li>
      </ul>
      <img src="https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/React-161b22?style=flat-square&logo=react&logoColor=white" />
      <img src="https://img.shields.io/badge/Phaser-161b22?style=flat-square" />
      <img src="https://img.shields.io/badge/Expo-161b22?style=flat-square&logo=expo&logoColor=white" />
    </td>
  </tr>
</table>

<br/>

### Experience

| Role | Organization | Period |
| :--- | :--- | :--- |
| **Senior Engineer** — radio broadcast infrastructure, satellite network, server and network operations, studio signal chain | AzTV | Oct 2024 – Present |
| **Presenter / Reporter** (Intern) | AzTV | Sep 2025 – Feb 2026 |
| **Communications Engineer** (Intern) — onboard radar and RF equipment inspection | Silkway | May 2023 – Sep 2024 |

<br/>

### Technical Skills

| Area | Stack |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-161b22?style=flat-square) ![Shell](https://img.shields.io/badge/Shell-161b22?style=flat-square&logo=gnubash&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-161b22?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-161b22?style=flat-square&logo=sqlalchemy&logoColor=white) ![REST](https://img.shields.io/badge/REST%20API-161b22?style=flat-square) ![WebSockets](https://img.shields.io/badge/WebSockets-161b22?style=flat-square) |
| **Frontend** | ![React](https://img.shields.io/badge/React%2019-161b22?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-161b22?style=flat-square&logo=vite&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-161b22?style=flat-square&logo=threedotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-161b22?style=flat-square&logo=tailwindcss&logoColor=white) ![PyQt6](https://img.shields.io/badge/PyQt6-161b22?style=flat-square&logo=qt&logoColor=white) |
| **Data & AI** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-161b22?style=flat-square&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-161b22?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-161b22?style=flat-square&logo=numpy&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-161b22?style=flat-square&logo=googlegemini&logoColor=white) ![Whisper](https://img.shields.io/badge/Whisper-161b22?style=flat-square&logo=openai&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-161b22?style=flat-square&logo=ollama&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-161b22?style=flat-square&logo=ffmpeg&logoColor=white) |
| **Security** | ![WebAuthn](https://img.shields.io/badge/WebAuthn-161b22?style=flat-square&logo=webauthn&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-161b22?style=flat-square&logo=jsonwebtokens&logoColor=white) ![RBAC](https://img.shields.io/badge/RBAC-161b22?style=flat-square) ![Cloudflare WAF](https://img.shields.io/badge/Cloudflare%20WAF-161b22?style=flat-square&logo=cloudflare&logoColor=white) |
| **Cloud & DevOps** | ![GCP](https://img.shields.io/badge/GCP-161b22?style=flat-square&logo=googlecloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-161b22?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=white) |
| **RF & Hardware** | ![RTL-SDR](https://img.shields.io/badge/RTL--SDR-161b22?style=flat-square) ![ADALM-Pluto](https://img.shields.io/badge/ADALM--Pluto-161b22?style=flat-square) ![DSP](https://img.shields.io/badge/DSP-161b22?style=flat-square) ![Satellite](https://img.shields.io/badge/Satellite%20Comms-161b22?style=flat-square) |

<br/>

### Education

| Degree | Institution | Period |
| :--- | :--- | :--- |
| **M.Sc.** Information Security of Telecommunication Systems | Azerbaijan Technical University | 2024 – 2026 |
| **B.Sc.** Telecommunication Engineering | Azerbaijan National Aviation Academy | 2020 – 2024 |
| Artificial Intelligence Engineering (Bootcamp) | Div Academy | 2025 – 2026 |
| Java Foundation (Bootcamp) | Code Space | 2023 – 2024 |

**Languages:** Azerbaijani (Native), English (B2–C1), Russian (A1)

<br/>

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=elcan146&show_icons=true&hide_border=true&hide_rank=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=elcan146&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top languages" />
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,45:0f2a3d,100:0d1117&height=110&section=footer" alt="" />
</p>
