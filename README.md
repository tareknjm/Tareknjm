<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=tarek%2Fcareer&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=a%20full%20stack%20repository%2C%20actively%20maintained&descAlignY=62&descSize=16" width="100%"/>

[![GitHub](https://img.shields.io/badge/GitHub-tareknjm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tareknjm)
![views](https://komarev.com/ghpvc/?username=tareknjm&style=for-the-badge&color=6D28D9&label=CLONES)

</div>

<br/>

## 📖 git log --graph --oneline

```
* a3f9c21 (HEAD -> main) feat: harden HealthCheck Monitor with SSRF protection + 50 tests
* 7b21e4d feat: add Keycloak auth + Docker Compose healthchecks to HealthCheck Monitor
* d94a017 feat: ship E-Learning Platform — JWT auth, PDF certs, admin dashboard
* 5c3fa88 feat: full stack pivot — React + Spring Boot as daily stack
* 91ab2c0 chore: enroll in software engineering degree
* 0000001 Initial commit — curiosity about how software actually works
```

> `git blame README.md` will tell you this file is rewritten more often than most people update their CV. That's on purpose — this repo is a living build, not a snapshot.

---

## 🔀 Pull requests merged into production

Real features, shipped and tested — not tutorial clones.

<table>
<tr><td width="60%">

**PR #2 — `HealthCheck Monitor`**
*Real-time HTTP/HTTPS service supervision*

```diff
+ UrlSecurityValidator (SSRF protection)   7/7 tests
+ Keycloak-based auth + role lockdown      passing
+ Docker Compose: healthchecks on all svc  healthy
+ 5 Redux slices, fully tested             43/43
+ React components (StatusChip, KPI...)    tested
- naive "trust the URL" input handling
```

`Spring Boot` `PostgreSQL` `React` `Redux` `Keycloak` `Docker`
[→ view diff](https://github.com/stodar/Observateur-des-services)

</td><td width="40%" valign="top">

**Review status**
```
✅ Approved
🧪 Tests:     50+ passing
🐳 Deploy:    docker compose up --build -d
🔐 Security:  SSRF-hardened
```

</td></tr>
<tr><td width="60%">

**PR #1 — `E-Learning Platform`**
*End-to-end learning platform, enrollment → certificate*

```diff
+ JWT auth with 3 roles (Admin/Instructor/Learner)
+ Auto-generated PDF certificates
+ Interactive quiz engine
+ Analytics + chatbot integration
- manual grading spreadsheets
```

`Spring Boot` `JWT` `MySQL` `React` `Vite` `Tailwind`
[→ view diff](https://github.com/tareknjm/elearning-backend)

</td><td width="40%" valign="top">

**Review status**
```
✅ Approved
🎓 Roles:     3 (RBAC)
📄 Output:    PDF certs
🤖 Extra:     AI chatbot
```

</td></tr>
</table>

---

## 📡 GET /skills

```json
{
  "backend": ["Spring Boot", "Java", ".NET", "Laravel", "Django", "PHP", "C#"],
  "frontend": ["React", "Angular", "Vite", "Tailwind CSS", "JavaScript"],
  "data": ["MySQL", "PostgreSQL"],
  "auth": ["JWT", "OAuth2", "Keycloak"],
  "infra": ["Docker", "Docker Compose", "Git"],
  "testing": ["JUnit", "Vitest", "React Testing Library"],
  "mobile": ["Android", "Android Studio"],
  "status": 200
}
```

<div align="center">

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
<br/>
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
<br/>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</div>

---

## 🐛 Known issues (a.k.a. what I'm working on)

```
ISSUE #14  Not enough production traffic to test at real scale     [open]
ISSUE #11  CI/CD pipeline missing on personal projects              [in progress]
ISSUE #9   Event-driven / distributed systems knowledge — v1.0      [backlog → started]
ISSUE #3   Sleep schedule vs deploy schedule conflict                [won't fix]
```

---

## 📊 npm run stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=tareknjm&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6D28D9&icon_color=6D28D9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tareknjm&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6D28D9" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=tareknjm&theme=tokyonight&hide_border=true&background=0D1117&ring=6D28D9&fire=6D28D9" />

</div>

---

<div align="center">

## 🤝 Open a pull request into your team

I'm looking to merge into a team that ships real things — reach out and let's talk architecture.

[![GitHub](https://img.shields.io/badge/GitHub-tareknjm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tareknjm)

```bash
$ git commit -m "say hi to Tarek"
$ git push origin your-team
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
