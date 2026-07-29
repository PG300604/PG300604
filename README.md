<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=140&section=header&text=Priyanshu%20Ghosh&fontSize=40&fontColor=ffffff&fontAlignY=42&desc=Full%20Stack%20Java%20Developer%20%7C%20AI%20Builder%20%7C%20Ships%20Fast&descAlignY=65&descSize=15&descColor=79b8ff&animation=fadeIn" width="100%"/>
</div>

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                    SYSTEM METRICS DASHBOARD                     ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

<div align="center">

| 🏗️ Projects Shipped | 🟢 Live Deployments | ⚡ Fastest Ship | 🏆 Competitions | 🤖 AI Features Built | 🔩 Microservices |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **4** | **3** | **24 hrs** | **2** | **5+** | **9** |

</div>

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                      SYSTEM STATUS BOARD                        ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

```
┌─────────────────────────────────────────────────────────────────────────┐
│  ◉  DEPLOYMENT STATUS MONITOR                          [LIVE · 2026]    │
├──────────────────┬──────────────┬──────────────────────┬────────────────┤
│  SERVICE         │  STATUS      │  STACK               │  UPTIME        │
├──────────────────┼──────────────┼──────────────────────┼────────────────┤
│  ShopFlow        │  🟡 BUILDING │  Java · Microsvcs    │  In Progress   │
│  SkillShare      │  🟢 LIVE     │  Spring Boot · React │  Deployed ✓    │
│  ZeroHour        │  🟢 LIVE     │  Gemini AI · React   │  Deployed ✓    │
│  SkyCheck PWA    │  🟢 LIVE     │  React PWA · Java    │  Deployed ✓    │
├──────────────────┼──────────────┼──────────────────────┼────────────────┤
│  ACTIVE REPOS    │  10+         │  LANGUAGES           │  8+            │
│  FRAMEWORKS      │  15+         │  OPEN TO INTERN      │  ✅ YES        │
└──────────────────┴──────────────┴──────────────────────┴────────────────┘
```

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                        IDENTITY BLOCK                           ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

```java
/**
 * @author  Priyanshu Ghosh
 * @college Asansol Engineering College · CSBS · 2027
 * @status  Open to SDE Internships
 */
@RestController
public class Priyanshu {

    // What I build
    private final String[] domains = {
        "Backend APIs",  "Microservices",  "AI Agents",
        "Full Stack Web", "PWAs",          "Security Systems"
    };

    // How fast I build it
    private final String record = "Production app shipped in 24 hours (ZeroHour · Hackathon)";

    @GetMapping("/stack")
    public Map<String, String[]> getStack() {
        return Map.of(
            "backend",   new String[]{"Java 17", "Spring Boot", "Spring Security", "Hibernate/JPA", "Maven"},
            "ai",        new String[]{"Gemini API", "Multi-Agent Systems", "Edge Inference", "SSE Streaming"},
            "database",  new String[]{"PostgreSQL", "MySQL", "H2", "Supabase"},
            "frontend",  new String[]{"React 19", "Next.js", "Vite", "Framer Motion", "Three.js"},
            "devops",    new String[]{"Docker", "Railway", "Vercel", "Git"},
            "mobile",    new String[]{"Kotlin", "Jetpack Compose", "Firebase"}
        );
    }
}
```

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                       PROJECT DASHBOARD                         ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

## 🚀 Projects

---

### 🏗️ ShopFlow — Full Stack E-Commerce Platform
> `Status: IN PROGRESS` &nbsp;·&nbsp; `Type: Microservices` &nbsp;·&nbsp; `Scale: 9 Services`

<table>
<tr>
<td width="58%" valign="top">

**The most architecturally complex project I've built.** A production-grade e-commerce platform on a 9-microservice Spring Boot architecture — each service independently deployable with its own database schema.

```
Auth Service       → JWT + BCrypt + Role Management
Product Service    → Catalog, Search, Pagination
Order Service      → Cart → Checkout → State Machine
Payment Service    → Stripe + Webhook Callbacks
Inventory Service  → PENDING → COMMITTED → RELEASED
Notification Svc   → Async SMTP Email Pipeline
API Gateway        → Routing + Auth Validation
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
Radius:    10km → 100km (dynamic expansion)
Fallback:  Global top profiles by proficiency score
Auth:      OAuth2 + JWT via JWKS endpoint
ORM:       Spring Data JPA + Hibernate
DB:        PostgreSQL (prod) · H2 (dev/test)
Deploy:    Multi-stage Docker → JRE Alpine
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
Pipeline:  PlannerAgent → PrioritizerAgent
           → SchedulerAgent → NudgeAgent
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
Sync:       Cascading ID reconciliation → PostgreSQL
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

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                         TECH STACK                              ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

## 🛠 Tech Stack

<div align="center">

**Backend · 5 frameworks**

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
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

**Frontend & AI · 5 tools**

![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Mobile · 2 tools**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                       GITHUB METRICS                            ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

## 📊 GitHub Metrics

<div align="center">

<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=PG300604&show_icons=true&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=4fcea6&count_private=true&include_all_commits=true&show=reviews,discussions_started" />
<img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=PG300604&layout=compact&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&langs_count=7&hide=html,css" />

</div>

<div align="center">

<img src="https://github-readme-stats-sigma-five.vercel.app/api/pin/?username=PG300604&repo=ShopFLow&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB" style="display:none"/>

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=PG300604&bg_color=0d1117&color=79b8ff&line=1A56DB&point=4fcea6&area=true&area_color=1A56DB&hide_border=false&border_color=1A56DB&radius=6)

</div>
<div align="center">
     [![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=PG300604&theme=dark&background=0d1117&border=1A56DB&stroke=1A56DB&ring=79b8ff&fire=ff6b35&currStreakLabel=79b8ff&sideLabels=8fa3c0&dates=8fa3c0&currStreakNum=ffffff&sideNums=ffffff) 

</div>

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                      ACHIEVEMENT BOARD                          ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

## 🏆 Achievement Board

<div align="center">

| 🎖️ Achievement | 📋 Details | 📅 Year |
|:---|:---|:---:|
| ⚡ **24-Hour Ship** | Built + deployed ZeroHour (multi-agent AI app) end-to-end at CodingNinjas × Google Hackathon | 2026 |
| 🏭 **Tata InnoVent Submission** | SkyCheck PWA submitted to Tata Technologies InnoVent 2026 — AI-powered industrial inspection | 2026 |
| 🏦 **JPMorgan Job Simulation** | Software Engineering Simulation — Kafka · REST APIs · H2 Integration via Forage | 2026 |
| 👑 **Mr. CSBS 2023** | Won personality & aptitude competition — Asansol Engineering College | 2023 |
| 🎓 **SGPA 8.88** | B.Tech CSBS — Asansol Engineering College | Ongoing |

</div>

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                        OPEN SOURCE                              ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

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

<!-- Update as you contribute:
| ✅ Merged | spring-projects/spring-boot #XXXXX | Description | Date |
-->

<br/>

<!-- ╔══════════════════════════════════════════════════════════════════╗
     ║                        CONNECT                                  ║
     ╚══════════════════════════════════════════════════════════════════╝ -->

## 📫 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priyanshu-ghosh-)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshughosh97@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A56DB?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-website-vercel-ten.vercel.app/)
[![ZeroHour](https://img.shields.io/badge/ZeroHour_Live-ff6b35?style=for-the-badge&logo=firebase&logoColor=white)](https://zerohour-a84d3.web.app)
[![SkillShare](https://img.shields.io/badge/SkillShare_Live-4fcea6?style=for-the-badge&logo=vercel&logoColor=white)](https://skillshare-app-vercel-xv9i.vercel.app)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=90&section=footer" width="100%"/>
</div>
