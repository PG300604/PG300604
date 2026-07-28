<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=1A56DB&height=120&section=header&text=Priyanshu%20Ghosh&fontSize=36&fontColor=ffffff&fontAlignY=40&desc=Full%20Stack%20Java%20Developer&descAlignY=65&descSize=16&descColor=a0c4ff" width="100%"/>
</div>

@RestController
public class Priyanshu {

    private final String role     = "Full Stack Java Developer";
    private final String college  = "Asansol Engineering College · CSBS · 2027";
    private final String focus    = "Backend APIs · Spring Security · System Design";
    private final String status   = "Open to SDE Internships";

    @GetMapping("/stack")
    public Map<String, String[]> getStack() {
        return Map.of(
            "backend",  new String[]{"Java 17", "Spring Boot", "Hibernate/JPA", "REST APIs", "Maven"},
            "security", new String[]{"Spring Security", "OAuth2", "JWT"},
            "database", new String[]{"PostgreSQL", "MySQL", "H2"},
            "frontend", new String[]{"React 19", "Next.js", "Vite", "Framer Motion", "Three.js"},
            "devops",   new String[]{"Docker", "Vercel", "Railway", "Git"},
            "ai",       new String[]{"Gemini API", "Multi-Agent Systems", "Edge Inference"},
            "mobile",   new String[]{"Kotlin", "Jetpack Compose", "Firebase"}
        );
    }
}

🚀 Projects

<!-- ═══════════════════════════════════════════════════════════════
     PROJECT 1 — ShopFlow
     ═══════════════════════════════════════════════════════════════ -->
<table>
<tr>
<td width="55%" valign="top">ShopFlow — Full Stack E-Commerce Platform
In Progress · Microservices · Most Complex Build
A modern, secure e-commerce platform built on a Java Spring Boot microservices architecture — independently scalable services for auth, products, orders, payments, notifications, and inventory.

🏗️ 9 independent microservices — Auth, Product, Order, Payment, Inventory, Notification, API Gateway
💳 Stripe payment integration with webhook/callback handlers and transaction logs
🔐 JWT role-based auth (Customer / Admin) with BCrypt password hashing
📦 Inventory reservation system with PENDING → COMMITTED → RELEASED state machine
📧 Async email notifications via SMTP for order confirmation, payment, and shipping updates
⚛️ Next.js frontend with Vanilla CSS — zero layout shifts, Server Components
Java Spring Boot Microservices PostgreSQL Next.js Stripe Docker JWT
Code ↗


</td>
<td width="45%" align="center" valign="top">


</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════
     PROJECT 2 — SkillShare
     ═══════════════════════════════════════════════════════════════ -->
<table>
<tr>
<td width="55%" valign="top">SkillShare — Skill Matching Platform
In Progress · Full Stack
A Tinder-style web app that connects users with nearby collaborators based on shared skills.

📍 Haversine geolocation engine — dynamic 10→100km radius expansion
🔐 OAuth2 JWT auth — Spring Security Resource Server + JWKS validation
🗄️ Spring Data JPA + PostgreSQL (prod) · H2 (dev)
🐳 Multi-stage Docker build — Maven → JRE Alpine
⚛️ React 19 · Framer Motion · React Three Fiber
Java Spring Boot Spring Security PostgreSQL Docker React
Live App ↗  ·  Code ↗


</td>
<td width="45%" align="center" valign="top">


</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════
     PROJECT 3 — ZeroHour
     ═══════════════════════════════════════════════════════════════ -->
<table>
<tr>
<td width="55%" valign="top">ZeroHour — Multi-Agent AI Productivity Platform
Shipped · Hackathon · CodingNinjas × Google Vibe2Ship
A multi-agent AI crisis-response companion that helps you survive tight deadlines — built and deployed end-to-end in 24 hours.

🧠 4-agent pipeline — Planner → Prioritizer → Scheduler → Nudge Agent
📅 Google Calendar API integration for automatic scheduling and two-way sync
📧 Gmail API for real-time deadline nudge emails
📄 Multimodal Gemini — uploads PDFs, syllabi, and photos to extract milestones
⚡ Real-time agent streams via Server-Sent Events (SSE)
🔐 Spring Security + CSRF + IDOR mitigation + 30-day session persistence
React Spring Boot Gemini API Google Calendar API Firebase Railway SSE
Live App ↗  ·  Code ↗


</td>
<td width="45%" align="center" valign="top">


</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════
     PROJECT 4 — SkyCheck
     ═══════════════════════════════════════════════════════════════ -->
<table>
<tr>
<td width="55%" valign="top">SkyCheck — AI Visual Structural Inspection PWA
Submitted · Tata Technologies InnoVent 2026 · Team Project
An offline-first PWA for site inspectors to perform AI-powered safety audits of heavy machinery in low-connectivity industrial environments.

📷 Real-time edge AI inference — classifies Corrosion, Cracks, and Normal via camera feed directly in-browser
📶 Offline-first with Dexie.js (IndexedDB) — full audit capability with zero connectivity
🔄 Online sync — cascading ID reconciliation pushes local records to PostgreSQL on Railway
🔐 JWT auth + OTP-based password recovery via SMTP
🤖 AI maintenance brief generation — Gemini-powered narrative inspection reports
👥 Co-developed with Riya Gupta (CSBS)
React PWA Spring Boot PostgreSQL Dexie.js Gemini API Vercel Railway Tailwind CSS
Live App ↗  ·  Code ↗


</td>
<td width="45%" align="center" valign="top">


</td>
</tr>
</table>

🛠 Tech Stack

<div align="center">Backend

Database & DevOps

Frontend & AI

Mobile



</div>

📊 GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats-sigma-five.vercel.app/api?username=PG300604&show_icons=true&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=PG300604&theme=react&background=0d1117&border=1A56DB&stroke=1A56DB&ring=1A56DB&fire=1A56DB&currStreakNum=79b8ff&sideNums=8fa3c0&currStreakLabel=79b8ff&sideLabels=8fa3c0&dates=8fa3c0" alt="GitHub Streak" />
<img height="160" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=PG300604&layout=compact&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&langs_count=6&hide=html,css" />
</div>

<div align="center">


</div>
<div align="center">


</div>

🌱 Open Source
Actively looking for my first open source contributions in the Java / Spring ecosystem.

Status | Project | Area
--- | --- | ---
🔍 Exploring | Spring Boot issues | Bug fixes / documentation
📖 Learning | Baeldung samples | Java best practices
🎯 Target | First PR merged | Q3 2026

<!-- As you contribute, replace rows with real PRs like this:
| ✅ Merged | spring-projects/spring-boot #XXXXX | Fixed null check in XYZ |
-->

📫 Let's Connect

<div align="center">

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=1A56DB&height=80&section=footer" width="100%"/>
</div>
