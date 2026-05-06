<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1A56DB&height=120&section=header&text=Priyanshu%20Ghosh&fontSize=36&fontColor=ffffff&fontAlignY=40&desc=Full%20Stack%20Java%20Developer&descAlignY=65&descSize=16&descColor=a0c4ff" width="100%"/>

</div>

```java
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
            "security", new String[]{"Spring Security", "OAuth2", "JWT", "Supabase"},
            "database", new String[]{"PostgreSQL", "MySQL", "H2"},
            "frontend", new String[]{"React 19", "Vite", "Framer Motion", "Three.js"},
            "devops",   new String[]{"Docker", "Vercel", "Git"},
            "mobile",   new String[]{"Kotlin", "Jetpack Compose", "Firebase"}
        );
    }
}
```

---

### 🚀 Projects

<!-- ═══════════════════════════════════════════════════════════════
     PROJECT 1 — SkillShare
     ═══════════════════════════════════════════════════════════════ -->

<table>
<tr>
<td width="55%" valign="top">

#### [SkillShare — Skill Matching Platform](https://github.com/PG300604/skillshare-app-vercel)
> *In Progress · Full Stack*

A Tinder-style web app that connects users with nearby collaborators based on shared skills.

- 📍 Haversine geolocation engine — dynamic 10→100km radius expansion
- 🔐 OAuth2 JWT auth via Supabase as identity provider
- 🗄️ Spring Data JPA + PostgreSQL (prod) · H2 (dev)
- 🐳 Multi-stage Docker build — Maven → JRE Alpine
- ⚛️ React 19 · Framer Motion · React Three Fiber

`Java` `Spring Boot` `Spring Security` `PostgreSQL` `Docker` `React`

**[Live App ↗](https://skillshare-app-vercel-xv9i.vercel.app)** &nbsp;·&nbsp; **[Code ↗](https://github.com/PG300604/skillshare-app-vercel)**

</td>
<td width="45%" align="center" valign="top">

[![SkillShare](https://github-readme-stats.vercel.app/api/pin/?username=PG300604&repo=skillshare-app-vercel&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/skillshare-app-vercel)

</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════
     TO ADD PROJECT 2: uncomment the block below, fill in details
     ═══════════════════════════════════════════════════════════════

<table>
<tr>
<td width="55%" valign="top">

#### [Project Name](https://github.com/PG300604/repo-name)
> *Status · Type*

Short description of what the project does.

- ✦ Key feature one
- ✦ Key feature two
- ✦ Key feature three

`Tech1` `Tech2` `Tech3`

**[Live ↗](https://your-link)** &nbsp;·&nbsp; **[Code ↗](https://github.com/PG300604/repo)**

</td>
<td width="45%" align="center" valign="top">

[![Repo](https://github-readme-stats.vercel.app/api/pin/?username=PG300604&repo=REPO-NAME&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB)](https://github.com/PG300604/REPO-NAME)

</td>
</tr>
</table>

-->

---

### 🛠 Tech Stack

<div align="center">

**Backend**

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

**Database & DevOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

---

### 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=PG300604&show_icons=true&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&icon_color=1A56DB&count_private=true&include_all_commits=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PG300604&layout=compact&theme=react&bg_color=0d1117&border_color=1A56DB&title_color=79b8ff&text_color=8fa3c0&langs_count=6&hide=html,css" />

</div>

---

### 🌱 Open Source

> Actively looking for my first open source contributions in the Java / Spring ecosystem.

| Status | Project | Area |
|--------|---------|------|
| 🔍 Exploring | Spring Boot issues | Bug fixes / documentation |
| 📖 Learning | Baeldung samples | Java best practices |
| 🎯 Target | First PR merged | Q3 2026 |

<!-- As you contribute, replace rows with real PRs like this:
| ✅ Merged | spring-projects/spring-boot #XXXXX | Fixed null check in XYZ |
-->

---

### 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priyanshu-ghosh-)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshughosh97@gmail.com)
[![SkillShare App](https://img.shields.io/badge/Live_Project-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://skillshare-app-vercel-xv9i.vercel.app)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=1A56DB&height=80&section=footer" width="100%"/>
</div>
