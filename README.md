# José Alejandro Téllez Prada · @Joserraldo

**Full-stack developer · AI agent orchestration** — Bucaramanga, Colombia 🇨🇴

I plan the architecture, split the work across AI agents and review what they ship.
That is how I build complete products: my own SaaS, a mobility platform for Bucaramanga,
and a CRM that won the UNAB Venture Challenge.

🔗 **[joserraldo.github.io](https://joserraldo.github.io)** · [Download CV](https://joserraldo.github.io/cv/CV_Jose_Tellez_Prada_ES.pdf) · [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-alejandro-t%C3%A9llez-prada-489312366/) · [Email](mailto:Joseale2006@gmail.com)

Systems Engineering @ UNAB · GPA 4.61/5.0 · Open to remote roles, internships and freelance (CO / US)

---

## 🏆 What I've shipped

### [CDE Conecta](https://cdeunab.lat/conecta) — winner, UNAB Venture Challenge 2026
A CRM 2.0 for UNAB's Business Development Center. Replaces a 30-sheet Excel workbook and gives
every startup its own growth panel. First place among 5 teams, 25h of continuous building,
and the Center is implementing it.
Four specialist agents behind a single router: the model never touches the data — code does.
Routed correctly in **7 of 7** production tests in ~2s, using **~200x fewer tokens** than feeding
the model the whole workbook. If it hesitates, fixed rules take over.
`TypeScript · multi-agent routing · strict JSON schema · human-in-the-loop`
*(source private)*

### [Calaut.pro](https://calaut.pro) — my own B2B SaaS
Multi-tenant scheduling for clinics, aesthetics, legal and education. Role-based privacy
(isolated agendas, hidden colleague rooms), 2-way Google Calendar sync with no double bookings,
omnichannel reminders, CRM with automatic profiling and a clinical module compliant with
Colombian Res. 2275 & 1995. Designed, built and scaled solo — multi-tenant through deploy.
`React 18 · TypeScript · Firebase · 43 Cloud Functions · 25 rule-protected paths · Bold · Resend · PWA`

### [BUCARATRANSIT](https://github.com/JaimeMrF/bus_unab) — mobility for Bucaramanga
One app to move around the city: live buses, routes, prepaid wallet and QR fares. Each transit
company runs separately on the same platform, and the driver's phone becomes the payment terminal
(zero extra hardware on the bus). I designed the move from campus tracker to multi-tenant platform
and built the wallet, dynamic QR, driver mode and brand. **88 automated tests.**
`Kotlin Multiplatform (Android + iOS) · Laravel 12 · Filament · MapLibre · HMAC-SHA256 QR, 60s single-use · double-entry ledger`
*(team of 3)*

### Models that left the notebook
- **[damaged_eggs_CNN](https://github.com/Joserraldo/damaged_eggs_CNN)** — YOLOv8n trained on Colab, served with FastAPI on EC2, consumed from an Expo app. Spots good vs. cracked eggs from a phone.
- **[Mano Musical](https://github.com/Joserraldo/proyecto_mano_musical)** — MediaPipe air-piano: the camera sees which finger you lower and plays its note. 10 fingers, 10 notes, game mode.
- **[Canine keypoints](https://github.com/Joserraldo/detector-puntos-clave-perro)** — MobileNetV2 locating 24 anatomical points on a dog, Streamlit demo.
- **[CNN digits](https://github.com/Joserraldo/reconocimiento-numeros-mnist)** — draw a digit, see the confidence and what the network sees.

### Hackathon & client work
- **[Factory OS](https://factoryos-beta.netlify.app)** ([code](https://github.com/Joserraldo/FactoryFlow-ERP)) — real-time industrial monitoring built at Hackathon Colombia 5.0: anomaly detection, alerts and natural-language queries over simulated sensors.
- **Hidrolavados** — platform for a Kärcher Gold Partner pressure-washer shop: catalog, rentals, repair tracking and photo receipts. `Next.js · Firebase · Supabase · Cloudflare Workers` *(private)*
- **[Urban Mobility Hub](https://github.com/Joserraldo/urban-mobility-hub)** — PWA for rental, sale and delivery of urban vehicles, with helmet detection (YOLOv8n-ONNX) running in the browser.
- Freelance storefronts shipped end to end: [K-Skin BGA](https://kskin-bga.vercel.app), [Bordados Zapatoca](https://bordados-zapatoca.vercel.app).

---

## 🧠 How I work

I spend more time planning than typing. Quality comes from how the work is split and reviewed.

| | |
|---|---|
| **1. Plan** | Architecture, rules, and what "done" means |
| **2. Split** | Small tasks, each with an owner and its own folder |
| **3. Agents build** | Parallel subagents, like a small dev studio |
| **4. Review** | Types, tests and CI before anything merges |

Daily drivers: **Claude Code** and **Hermes Agent** with subagents, **n8n** for flows, and a
library of **130+ reusable skills** for deploys, QA, audits and docs. I benchmark providers with
real requests (on CDE Conecta: Qwen ~2s, DeepSeek 4–8s with intermittent errors) and route each
task to the cheapest model that can do it.

---

## 🛠️ Stack

**Areas I've worked in:** multi-tenant B2B SaaS · agent orchestration & LLM routing · computer vision
& ML training · mobile (Kotlin Multiplatform / Compose) · IoT & telemetry · backend APIs ·
relational & NoSQL data · dashboards & analytics · 3D modeling & game dev · embedded C/C++

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

<details>
<summary><b>Full stack — every technology I've actually shipped with</b></summary>

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-404D59?style=for-the-badge&logo=express&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4e56a6?style=for-the-badge&logo=livewire&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens)
![Firebase Auth](https://img.shields.io/badge/Firebase_Auth-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)

**Frontend, mobile & desktop**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android_Kotlin-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![CameraX](https://img.shields.io/badge/CameraX-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![ML Kit](https://img.shields.io/badge/ML_Kit-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=electron&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-FF0000?style=for-the-badge&logo=java&logoColor=white)

**AI, ML & LLM engineering**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-white?style=for-the-badge&logo=opencv&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-0C55A5?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**Cloud & DevOps**

![Microsoft Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure IoT Hub](https://img.shields.io/badge/Azure_IoT_Hub-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Digital Twins](https://img.shields.io/badge/Azure_Digital_Twins-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure VMs](https://img.shields.io/badge/Azure_VMs-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=firebase&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-2C5263?style=for-the-badge&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D42029?style=for-the-badge&logo=apache&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405e?style=for-the-badge&logo=sqlite&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**IoT & embedded**

![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![AMQP](https://img.shields.io/badge/AMQP-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![CoAP](https://img.shields.io/badge/CoAP-4B8BBE?style=for-the-badge&logo=internetarchive&logoColor=white)
![Azure IoT Central](https://img.shields.io/badge/Azure_IoT_Central-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Wokwi](https://img.shields.io/badge/Wokwi-000000?style=for-the-badge&logo=wokwi&logoColor=white)

**Computer science fundamentals**

![Data Structures](https://img.shields.io/badge/Data_Structures-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Algorithms](https://img.shields.io/badge/Algorithms-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Competitive Programming](https://img.shields.io/badge/Competitive_Programming-00599C?style=for-the-badge&logo=codeforces&logoColor=white)
![Graph Algorithms](https://img.shields.io/badge/Graph_Algorithms-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Dynamic Programming](https://img.shields.io/badge/Dynamic_Programming-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Optimization](https://img.shields.io/badge/Optimization-FF6F00?style=for-the-badge&logo=scipy&logoColor=white)
![Numerical Methods](https://img.shields.io/badge/Numerical_Methods-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Networking](https://img.shields.io/badge/Networking-0078D4?style=for-the-badge&logo=cisco&logoColor=white)
![Operating Systems](https://img.shields.io/badge/Operating_Systems-111111?style=for-the-badge&logo=linux&logoColor=white)
![Concurrency](https://img.shields.io/badge/Concurrency-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Multithreading](https://img.shields.io/badge/Multithreading-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Sockets](https://img.shields.io/badge/Sockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**3D, game dev & design**

![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-313131?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Autodesk Maya](https://img.shields.io/badge/Autodesk_Maya-37A5CC?style=for-the-badge&logo=autodesk&logoColor=white)
![SketchUp](https://img.shields.io/badge/SketchUp-005F9E?style=for-the-badge&logo=sketchup&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white)
![Premiere Pro](https://img.shields.io/badge/Premiere_Pro-9999FF?style=for-the-badge&logo=adobepremierepro&logoColor=white)
![After Effects](https://img.shields.io/badge/After_Effects-9999FF?style=for-the-badge&logo=adobeaftereffects&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows Terminal](https://img.shields.io/badge/Windows_Terminal-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)
![PNPM](https://img.shields.io/badge/PNPM-4a4a4a?style=for-the-badge&logo=pnpm&logoColor=f69220)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0A0FFF?style=for-the-badge&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

</details>

**Also:** Claude Code · Hermes Agent · subagents & skills · LLM routing · strict JSON-schema outputs · token budgeting

---

## 🌍 Beyond the code

- 🥋 Taekwondo black belt — competed nationally and internationally for UNAB, Santander and Colombia. My black-belt project got taekwondo adopted at the school I attended.
- ✨ J-1 Cultural Exchange at **Walt Disney World** (attractions & operations, 4 venues, always in English).
- 🧩 On UNAB's competitive programming team — ACIS/REDIS National Marathon 2025 and 2026.
- 🖥️ I build gaming rigs for fun. And yes, I still think Overwatch is peak gaming.

---

## 📊 GitHub stats

![](https://github-readme-stats.shion.dev/api?username=Joserraldo&theme=dark&hide_border=false&include_all_commits=true&count_private=false)
![](https://streak-stats.demolab.com/?user=Joserraldo&theme=dark&hide_border=false)
![](https://github-readme-stats.shion.dev/api/top-langs/?username=Joserraldo&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

📫 **Joseale2006@gmail.com** · Discord `joserraldo` · [joserraldo.github.io](https://joserraldo.github.io)
