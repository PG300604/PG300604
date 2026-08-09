<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=160&section=header&text=Priyanshu%20Ghosh&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Java%20Developer%20%7C%20AI%20Builder%20%7C%20Ships%20Fast&descAlignY=58&descSize=16&descColor=79b8ff&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2500&pause=900&color=79B8FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Architecting+Dijkstra+%2B+Hungarian+algorithms+for+TriageNet;Shipping+production+AI+agents+in+24+hours;9+microservices.+3+live+deployments.+0+shortcuts;Open+to+SDE+Internships+%E2%80%94+let's+build+something" alt="Typing SVG" />

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priyanshu-ghosh-)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A56DB?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-website-vercel-ten.vercel.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshughosh97@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/priyanshughosh30/)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

<!-- ═══════════════════════════════════════════ METRICS ═══════════════════════════════════════════ -->

<div align="center">

<table>
<tr>
<td align="center" width="16.6%">

### 🏗️
**5**
<sub>Projects Shipped</sub>

</td>
<td align="center" width="16.6%">

### 🟢
**3**
<sub>Live Deployments</sub>

</td>
<td align="center" width="16.6%">

### ⚡
**24hrs**
<sub>Fastest Ship</sub>

</td>
<td align="center" width="16.6%">

### 🏆
**2**
<sub>Competitions</sub>

</td>
<td align="center" width="16.6%">

### 🤖
**9+**
<sub>AI Agents Built</sub>

</td>
<td align="center" width="16.6%">

### 🔩
**9**
<sub>Microservices</sub>

</td>
</tr>
</table>

</div>

<br/>

```
┌──────────────────────────────────────────────────────────────────────────┐
│  ◉  DEPLOYMENT STATUS MONITOR                           [ LIVE · 2026 ]  │
├───────────────────┬──────────────┬───────────────────────┬───────────────┤
│  SERVICE          │  STATUS      │  STACK                │  UPTIME       │
├───────────────────┼──────────────┼───────────────────────┼───────────────┤
│  TriageNet        │  🔵 PHASE 4/5│  Java 21 · ML · Next   │ Final Yr Proj │
│  ShopFlow         │  🟡 BUILDING │  Java · Microservices  │ In Progress   │
│  SkillShare       │  🟢 LIVE     │  Spring Boot · React   │ Deployed ✓    │
│  ZeroHour         │  🟢 LIVE     │  Gemini AI · React     │ Deployed ✓    │
│  SkyCheck PWA     │  🟢 LIVE     │  React PWA · Java      │ Deployed ✓    │
├───────────────────┼──────────────┼───────────────────────┼───────────────┤
│  ACTIVE REPOS     │  10+         │  LANGUAGES             │  8+           │
│  FRAMEWORKS       │  15+         │  OPEN TO INTERN        │  ✅ YES       │
└───────────────────┴──────────────┴───────────────────────┴───────────────┘
```

<br/>

```java
/**
 * @author  Priyanshu Ghosh
 * @college Asansol Engineering College · CSBS · 2027
 * @status  Open to SDE Internships
 */
@RestController
public class Priyanshu {

    private final String[] domains = {
        "Backend APIs",  "Microservices",  "Autonomous AI Agents",
        "Full Stack Web", "PWAs",          "Security Systems"
    };

    private final String record = "Production app shipped in 24 hours (ZeroHour · Hackathon)";

    @GetMapping("/stack")
    public Map<String, String[]> getStack() {
        return Map.of(
            "backend",   new String[]{"Java 21", "Spring Boot", "Spring Security", "Hibernate/JPA", "Maven"},
            "ai",        new String[]{"Gemini API", "Multi-Agent Systems", "ML Severity Scoring", "SSE Streaming"},
            "database",  new String[]{"PostgreSQL", "MySQL", "H2", "Supabase"},
            "frontend",  new String[]{"React 19", "Next.js 16", "Vite", "Framer Motion", "Three.js"},
            "devops",    new String[]{"Docker", "Railway", "Vercel", "Git"},
            "mobile",    new String[]{"Kotlin", "Jetpack Compose", "Firebase"}
        );
    }
}
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

## 🚀 Projects

---

### 🏥 TriageNet — AI-Powered Hospital Triage, Resource & Financial Recovery System
> `Status: PHASE 4/5 COMPLETE` &nbsp;·&nbsp; `Type: Final Year Project` &nbsp;·&nbsp; `Scale: Full Platform + Autonomous Agents`

<table>
<tr>
<td width="58%" valign="top">

**The most technically ambitious project I've built.** A full-stack healthcare operations platform where autonomous AI agents manage patient triage, resource allocation, equipment costs, and inter-hospital transfers in real time — across a 4-hospital weighted regional network.

```
ML Engine:     Logistic Regression severity scorer
               Score = Sigmoid(W·X + b) × 100
               Risk Tiers: High(>=80) Moderate Low

Algorithms:    Dijkstra shortest-path referrals
               Hungarian bed assignment matcher
               Priority decay: E = S + lambda*W

AI Agents:     Supply Demand Agent (24/7 telemetry)
               Financial Cost Recovery Agent (Rupees)
               Dijkstra Overflow Routing Agent

Backend:       8 Maven test suites -- 100% passing
               Full JPA persistence + REST APIs
```

**Phase 4 additions — Autonomous AI Agents:**
- 🤖 **Supply Demand Agent** — 24/7 telemetry, dynamic deficit calculator, live CLI terminal
- 💰 **Financial Recovery Agent** — manages a **₹12.80 Cr** budget, tracks equipment costs, computes **+₹1.46 Cr surplus** at a **142.7% Cost Recovery Ratio**
- 🖥️ **Darkroom Terminal UI** — live macOS/Linux-style CLI streaming real telemetry
- 📊 Real-time SVG dashboards — wait latency trends, specialist matching, cost vs recovery

**Phase 3 — Core Engine (complete):**
- 🚨 Sepsis early warning, Explainable AI risk attribution
- 🛏️ ICU/General bed stratification with disease-specific recovery thresholds
- 🔒 Non-preemptible critical occupancy lock (severity ≥ 85)

`Java 21` `Spring Boot 3.4` `Next.js 16` `Python` `scikit-learn` `PostgreSQL` `Docker`

**[Code ↗](https://github.com/PG300604/TriageNet)**

</td>
<td width="42%" align="center" valign="top">

[![TriageNet](https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=TriageNet&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/TriageNet)

<br/>

![](https://img.shields.io/badge/Phase-4/5_Complete-1A56DB?style=flat-square)
![](https://img.shields.io/badge/AI_Agents-3_Autonomous-8E75B2?style=flat-square)
![](https://img.shields.io/badge/Tests-8_Suites_100%25-4fcea6?style=flat-square)
![](https://img.shields.io/badge/Budget_Managed-₹12.80_Cr-ff6b35?style=flat-square)
![](https://img.shields.io/badge/Surplus-%2B₹1.46_Cr-brightgreen?style=flat-square)
![](https://img.shields.io/badge/Algorithm-Dijkstra_+_Hungarian-316192?style=flat-square)

</td>
</tr>
</table>

---

### 🏗️ ShopFlow — Full Stack E-Commerce Platform
> `Status: IN PROGRESS` &nbsp;·&nbsp; `Type: Microservices` &nbsp;·&nbsp; `Scale: 9 Services`

<table>
<tr>
<td width="58%" valign="top">

**A production-grade e-commerce platform on a 9-microservice Spring Boot architecture** — each service independently deployable with its own database schema.

```
Auth Service       -> JWT + BCrypt + Role Management
Product Service    -> Catalog, Search, Pagination
Order Service      -> Cart -> Checkout -> State Machine
Payment Service    -> Stripe + Webhook Callbacks
Inventory Service  -> PENDING -> COMMITTED -> RELEASED
Notification Svc   -> Async SMTP Email Pipeline
API Gateway        -> Routing + Auth Validation
```

**Key engineering highlights:**
- 📦 Inventory state machine — prevents oversell on concurrent checkouts
- 💳 Stripe webhook handler — async payment confirmation pipeline
- 📧 Non-blocking email notifications via background threads
- ⚛️ Next.js frontend with Vanilla CSS — zero framework overhead

`Java` `Spring Boot` `Microservices` `PostgreSQL` `Next.js` `Stripe` `Docker` `JWT`

**[Code ↗](https://github.com/PG300604/ShopFLow)**

</td>
<td width="42%" align="center" valign="top">

[![ShopFlow](https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=ShopFLow&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/ShopFLow)

<br/>

![](https://img.shields.io/badge/Services-9_Microservices-1A56DB?style=flat-square)
![](https://img.shields.io/badge/Database-PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![](https://img.shields.io/badge/Payment-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![](https://img.shields.io/badge/Auth-JWT_+_BCrypt-green?style=flat-square)
![](https://img.shields.io/badge/Frontend-Next.js-000000?style=flat-square&logo=next.js)

</td>
</tr>
</table>

---

### 🔗 SkillShare — Skill Matching Platform
> `Status: IN PROGRESS` &nbsp;·&nbsp; `Type: Full Stack` &nbsp;·&nbsp; `Live: ✅`

<table>
<tr>
<td width="58%" valign="top">

A Tinder-style web app that connects users with nearby collaborators based on shared skills — built with a custom geolocation engine.

```
Algorithm: Haversine Formula
Radius:    10km -> 100km (dynamic expansion)
Fallback:  Global top profiles by proficiency score
Auth:      OAuth2 + JWT via JWKS endpoint
ORM:       Spring Data JPA + Hibernate
DB:        PostgreSQL (prod) · H2 (dev/test)
Deploy:    Multi-stage Docker -> JRE Alpine
```

`Java` `Spring Boot` `Spring Security` `OAuth2` `PostgreSQL` `Docker` `React 19`

**[🌐 Live App](https://skillshare-app-vercel-xv9i.vercel.app)** &nbsp;·&nbsp; **[Code ↗](https://github.com/PG300604/skillshare-app-vercel)**

</td>
<td width="42%" align="center" valign="top">

[![SkillShare](https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=skillshare-app-vercel&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/skillshare-app-vercel)

<br/>

![](https://img.shields.io/badge/Algorithm-Haversine-4fcea6?style=flat-square)
![](https://img.shields.io/badge/Auth-OAuth2_+_JWT-1A56DB?style=flat-square)
![](https://img.shields.io/badge/Deploy-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)

</td>
</tr>
</table>

---

### ⚡ ZeroHour — Multi-Agent AI Productivity Platform
> `Status: SHIPPED` &nbsp;·&nbsp; `Built in: 24 hours` &nbsp;·&nbsp; `Event: CodingNinjas × Google Vibe2Ship`

<table>
<tr>
<td width="58%" valign="top">

**Built and deployed end-to-end in 24 hours at a national hackathon.** A multi-agent AI crisis companion that turns impossible deadlines into managed schedules — automatically.

```
Pipeline:  PlannerAgent -> PrioritizerAgent
           -> SchedulerAgent -> NudgeAgent
Stream:    Real-time SSE (watch agents think live)
Input:     PDFs · Syllabi · Photos (Gemini multimodal)
Calendar:  Google Calendar API (auto-schedule + sync)
Alerts:    Gmail API (deadline nudge emails)
Security:  CSRF · IDOR mitigation · 30-day sessions
```

`React` `Spring Boot` `Gemini API` `Google Calendar` `Firebase` `Railway` `SSE`

**[🌐 Live App](https://zerohour-a84d3.web.app)** &nbsp;·&nbsp; **[Code ↗](https://github.com/PG300604/ZeroHour)**

</td>
<td width="42%" align="center" valign="top">

[![ZeroHour](https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=ZeroHour&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/ZeroHour)

<br/>

![](https://img.shields.io/badge/Shipped_in-24_Hours-ff6b35?style=flat-square)
![](https://img.shields.io/badge/Agents-4_AI_Agents-8E75B2?style=flat-square&logo=google&logoColor=white)
![](https://img.shields.io/badge/Stream-SSE_Realtime-4fcea6?style=flat-square)
![](https://img.shields.io/badge/Event-Hackathon_Win-gold?style=flat-square)
![](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)

</td>
</tr>
</table>

---

### 🔍 SkyCheck — AI Visual Structural Inspection PWA
> `Status: SUBMITTED` &nbsp;·&nbsp; `Event: Tata Technologies InnoVent 2026` &nbsp;·&nbsp; `Live: ✅`

<table>
<tr>
<td width="58%" valign="top">

An offline-first PWA for industrial safety audits — real-time AI defect classification directly in the browser, no internet required.

```
AI Engine:  Edge inference via camera feed (in-browser)
Classifies: Corrosion · Cracks · Normal (real-time)
Offline:    Full audit capability via Dexie.js (IndexedDB)
Sync:       Cascading ID reconciliation -> PostgreSQL
Auth:       JWT + OTP password recovery via SMTP
Reports:    Gemini-powered narrative maintenance briefs
```

`React PWA` `Spring Boot 3.5` `PostgreSQL` `Dexie.js` `Gemini API` `Tailwind CSS`

**[🌐 Live App](https://dist-five-gules-45.vercel.app)** &nbsp;·&nbsp; **[Code ↗](https://github.com/PG300604/SkyCheck)**

</td>
<td width="42%" align="center" valign="top">

[![SkyCheck](https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=SkyCheck&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/SkyCheck)

<br/>

![](https://img.shields.io/badge/Type-Offline_First_PWA-1A56DB?style=flat-square)
![](https://img.shields.io/badge/AI-Edge_Inference-8E75B2?style=flat-square)
![](https://img.shields.io/badge/Event-Tata_InnoVent_2026-blue?style=flat-square)
![](https://img.shields.io/badge/Team-2_Members-4fcea6?style=flat-square)
![](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

## 🛠 Tech Stack

<div align="center">

**Backend · 5 frameworks**

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

**Database & DevOps · 6 tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Frontend & AI · 6 tools**

![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Mobile · 2 tools**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PG300604/PG300604/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PG300604/PG300604/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/PG300604/PG300604/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

</div>

<br/>

## 📊 GitHub Metrics

<div align="center">

<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=PG300604&show_icons=true&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=4fcea6&count_private=true&include_all_commits=true&show=reviews,discussions_started" />
<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=PG300604&layout=compact&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&langs_count=7&hide=html,css" />

</div>

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=PG300604&bg_color=0d1117&color=79b8ff&line=1A56DB&point=4fcea6&area=true&area_color=1A56DB&hide_border=false&border_color=1A56DB&radius=6)

</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=PG300604&style=for-the-badge&color=1A56DB&label=PROFILE+VIEWS)
&nbsp;&nbsp;
![Followers](https://img.shields.io/github/followers/PG300604?style=for-the-badge&color=4fcea6&label=FOLLOWERS&logo=github)
&nbsp;&nbsp;
![Stars](https://img.shields.io/github/stars/PG300604?style=for-the-badge&color=ff6b35&label=TOTAL+STARS&logo=github)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

## 🏆 Achievement Board

<div align="center">

| 🎖️ Achievement | 📋 Details | 📅 Year |
|:---|:---|:---:|
| 🏥 **TriageNet — Phase 4/5 Complete** | Built 3 autonomous AI agents managing a ₹12.80 Cr budget with +₹1.46 Cr recovery surplus; 8/8 Maven test suites passing | 2026 |
| ⚡ **24-Hour Ship** | Built + deployed ZeroHour (multi-agent AI app) end-to-end at CodingNinjas × Google Hackathon | 2026 |
| 🏭 **Tata InnoVent Submission** | SkyCheck PWA submitted to Tata Technologies InnoVent 2026 — AI-powered industrial inspection | 2026 |
| 🏦 **JPMorgan Job Simulation** | Software Engineering Simulation — Kafka · REST APIs · H2 Integration via Forage | 2026 |
| 🎓 **SGPA 8.83 · CGPA 8.05** | B.Tech CSBS — Asansol Engineering College | Ongoing |

</div>

<br/>

## 🌱 Open Source Roadmap

```
[▓▓▓▓▓▓░░░░░░░░░░░░░░]  30%  Exploring Spring Boot issues
[▓▓▓▓░░░░░░░░░░░░░░░░]  20%  Studying Baeldung contribution patterns
[░░░░░░░░░░░░░░░░░░░░]   0%  First PR — Target: Q3 2026
```

| Status | Repo | Area | ETA |
|:---:|:---|:---|:---:|
| 🔍 Exploring | `spring-projects/spring-boot` | Bug fixes · Docs | Q3 2026 |
| 📖 Studying | `eugenp/tutorials` | Java best practices | Q3 2026 |
| 🎯 Target | First merged PR | Any Java/Spring repo | Q3 2026 |

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" height="4px"/>

<br/>

<div align="center">

## 📫 Let's Build Something

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priyanshu-ghosh-)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshughosh97@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A56DB?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-website-vercel-ten.vercel.app/)
[![ZeroHour](https://img.shields.io/badge/ZeroHour_Live-ff6b35?style=for-the-badge&logo=firebase&logoColor=white)](https://zerohour-a84d3.web.app)
[![SkillShare](https://img.shields.io/badge/SkillShare_Live-4fcea6?style=for-the-badge&logo=vercel&logoColor=white)](https://skillshare-app-vercel-xv9i.vercel.app)

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=4A6080&center=true&vCenter=true&width=500&lines=%22Code+is+read+more+often+than+it+is+written%22;Thanks+for+scrolling+this+far+%F0%9F%91%80" alt="footer typing" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer" width="100%"/>
