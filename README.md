<div align="center">

![banner](https://capsule-render.vercel.app/api?type=waving&color=1d9e75&height=200&section=header&text=César%20Traver%20Bolos&fontSize=60&fontColor=e6edf3&fontAlignY=38&desc=AI%20automation%20%C2%B7%20Developer%20tooling%20%C2%B7%20Full%20stack&descAlignY=58&descSize=16&descColor=8b949e)

[![ColorlessBox](https://img.shields.io/badge/colorlessbox.net-0d1117?style=for-the-badge&logo=googlechrome&logoColor=1d9e75)](https://www.colorlessbox.net/)
[![Website](https://img.shields.io/badge/zorcedev.github.io-0d1117?style=for-the-badge&logo=github&logoColor=1d9e75)](https://zorcedev.github.io)
[![itch.io](https://img.shields.io/badge/itch.io-0d1117?style=for-the-badge&logo=itch.io&logoColor=1d9e75)](https://zorcedev.itch.io)
[![Unity Asset Store](https://img.shields.io/badge/Asset%20Store-0d1117?style=for-the-badge&logo=unity&logoColor=1d9e75)](https://assetstore.unity.com/publishers/142258)
[![Email](https://img.shields.io/badge/zorcedev@gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=1d9e75)](mailto:zorcedev@gmail.com)

</div>

---

### About me

Developer who builds tools that solve real problems — and then ships them. I automate repetitive work with **n8n and AI agents**, build **full-stack web apps**, and make tools for other developers. Everything I've shown here is live: a web app with real users, an app on Google Play and paid assets on the Unity Asset Store.

```
⚙️  Automating real workflows with n8n + AI agents
🌐  Running ColorlessBox in production on my own VPS
📦  Publishing tools other developers pay for
🐧  Running Linux daily (CachyOS)
```

📍 Castellón, Spain · 🇪🇸 Spanish / Catalan · 🇬🇧 English · **Open to freelance automation projects**

---

### Tech stack

<div align="center">

**Automation & AI**<br>
![n8n](https://img.shields.io/badge/n8n-0d1117?style=for-the-badge&logo=n8n&logoColor=97c459)
![Gemini](https://img.shields.io/badge/Gemini-0d1117?style=for-the-badge&logo=googlegemini&logoColor=97c459)
![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=97c459)

**Web & data**<br>
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=nextdotjs&logoColor=97c459)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-0d1117?style=for-the-badge&logo=dotnet&logoColor=97c459)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=97c459)

**Infra & DevOps**<br>
![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=97c459)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=97c459)
![Caddy](https://img.shields.io/badge/Caddy-0d1117?style=for-the-badge&logo=caddy&logoColor=97c459)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0d1117?style=for-the-badge&logo=githubactions&logoColor=97c459)
![Jenkins](https://img.shields.io/badge/Jenkins-0d1117?style=for-the-badge&logo=jenkins&logoColor=97c459)

**Games, tools & mobile**<br>
![Unity](https://img.shields.io/badge/Unity-0d1117?style=for-the-badge&logo=unity&logoColor=97c459)
![Godot](https://img.shields.io/badge/Godot-0d1117?style=for-the-badge&logo=godotengine&logoColor=97c459)
![C#](https://img.shields.io/badge/C%23-0d1117?style=for-the-badge&logo=csharp&logoColor=97c459)
![Kotlin](https://img.shields.io/badge/Kotlin-0d1117?style=for-the-badge&logo=kotlin&logoColor=97c459)

</div>

---

### Projects

<!-- PROYECTO TEMPLATE — duplica este bloque para añadir más
<details>
<summary><b>🔧 Nombre del proyecto</b> — tagline corta</summary>
<br>

> Descripción de una o dos líneas.

![badge tecnología](...)

**Links:** [Repo](url) · [Demo / Store](url)

</details>
-->

<details open>
<summary><b>🃏 ColorlessBox</b> — Free Pokémon TCG deckbuilder, live in production</summary>
<br>

> A web app to build and share Pokémon TCG decks, born because no existing deckbuilder did what I wanted. 23,000+ cards in 13 languages, 70 registered users and visits from several countries. Self-hosted on my own VPS after migrating off Vercel, Render and Supabase.

![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=97c459)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-0d1117?style=flat-square&logo=dotnet&logoColor=97c459)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=97c459)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=97c459)
![Caddy](https://img.shields.io/badge/Caddy-0d1117?style=flat-square&logo=caddy&logoColor=97c459)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat-square&logo=githubactions&logoColor=97c459)

**Highlights:** Full stack from DB to UI · CI and tests with GitHub Actions · Self-hosted on OVH (Debian + Docker + Caddy) · Query optimisation and data compression to fix a free-tier overrun · Daily card sync automated with n8n

**Links:** [colorlessbox.net](https://www.colorlessbox.net/)

</details>

<details>
<summary><b>⚙️ n8n production automations</b> — Workflows that run ColorlessBox while I sleep</summary>
<br>

> Self-hosted n8n connected to my own PostgreSQL. At 05:00 a workflow checks the card API, updates the database when new cards come out and emails me a report. At 08:00 another one emails me yesterday's new users from a SQL query. Saves around 40 minutes of manual work every day.

![n8n](https://img.shields.io/badge/n8n-0d1117?style=flat-square&logo=n8n&logoColor=97c459)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=97c459)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=97c459)

**Highlights:** Scheduled workflows in production · External API → database sync · SQL reporting by email · Self-hosted, zero SaaS cost

</details>

<details>
<summary><b>📖 ereader-dashboard</b> — An old e-reader turned into an E-Ink desk dashboard</summary>
<br>

> Every day it renders a 758×1024 image with the date, the weather, my Todoist tasks and a quote, and sets it as the screensaver of a discontinued ENERGY Sistem eReader Slim HD — no firmware hacks. Linux "plugs in" the e-reader over USB by software, waits for me to accept on screen, copies and verifies the image, ejects and "unplugs" it, while it keeps charging.

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=97c459)
![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=97c459)
![systemd](https://img.shields.io/badge/systemd%20·%20udev-0d1117?style=flat-square&logoColor=97c459)
![Waybar](https://img.shields.io/badge/Waybar-0d1117?style=flat-square&logoColor=97c459)
![Pillow](https://img.shields.io/badge/Pillow-0d1117?style=flat-square&logoColor=97c459)

**Highlights:** USB state machine with verified atomic transfer · Open-Meteo + Todoist (read-only, offline fallback) · Waybar module · systemd timers · udev rule scoped to one port · 101 pytest tests with a simulated device

**Links:** [Repo](https://github.com/CesarTraver/ereader-dashboard)

</details>

<details>
<summary><b>📊 Unity tools</b> — TelemetrySystem & Achievements, sold on the Asset Store</summary>
<br>

> **TelemetrySystem:** privacy-aware analytics SDK with multi-backend support, GDPR consent management and offline queue. Drops into any Unity project without coupling the codebase.<br>
> **Achievements:** plug-in achievements system for Unity games.<br>
> Designed, documented and published end to end — both have paying customers.

![Unity](https://img.shields.io/badge/Unity-0d1117?style=flat-square&logo=unity&logoColor=97c459)
![C#](https://img.shields.io/badge/C%23-0d1117?style=flat-square&logo=csharp&logoColor=97c459)
![Zenject](https://img.shields.io/badge/Zenject%20DI-0d1117?style=flat-square&logoColor=97c459)
![Supabase](https://img.shields.io/badge/Supabase-0d1117?style=flat-square&logo=supabase&logoColor=97c459)
![Firebase](https://img.shields.io/badge/Firebase-0d1117?style=flat-square&logo=firebase&logoColor=97c459)

**Highlights:** REST · Supabase · Firebase backends · GDPR consent · Offline queue (RAM + disk) · 63 NUnit tests · Assembly definitions

**Links:** [TelemetrySystem](https://assetstore.unity.com/packages/tools/utilities/telemetry-system-zorcedev-371662) · [Publisher page](https://assetstore.unity.com/publishers/142258)

</details>

<details>
<summary><b>📅 Nova Routine</b> — Agenda & routines app for Android</summary>
<br>

> Planner and routines app with Google Sign-In, Google Calendar and Google Drive integration. Published on Google Play, passing review on the first try.

![Kotlin](https://img.shields.io/badge/Kotlin-0d1117?style=flat-square&logo=kotlin&logoColor=97c459)
![Android](https://img.shields.io/badge/Android-0d1117?style=flat-square&logo=android&logoColor=97c459)

**Links:** [Google Play](https://play.google.com/store/apps/details?id=com.nova.routine)

</details>

<details>
<summary><b>🎮 PactumX</b> — Unity 6 2D game</summary>
<br>

> 2D game built in Unity 6 as a class project, deployed on itch.io.

![Unity](https://img.shields.io/badge/Unity-0d1117?style=flat-square&logo=unity&logoColor=97c459)
![C#](https://img.shields.io/badge/C%23-0d1117?style=flat-square&logo=csharp&logoColor=97c459)

**Links:** [itch.io](https://zorcedev.itch.io/PactumX)

</details>

---

### GitHub stats

<div align="center">
<img src="https://github-readme-stats-chi-five-29.vercel.app/api?username=CesarTraver&show_icons=true&hide_border=true&title_color=1d9e75&icon_color=97c459&text_color=8b949e&bg_color=0d1117&cache_seconds=3600" height="160" />
&nbsp;&nbsp;
<img src="https://github-readme-stats-chi-five-29.vercel.app/api/top-langs/?username=CesarTraver&layout=compact&hide_border=true&title_color=1d9e75&text_color=8b949e&bg_color=0d1117&cache_seconds=3600" height="160" />
</div>

---

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=1d9e75&height=100&section=footer)

</div>
