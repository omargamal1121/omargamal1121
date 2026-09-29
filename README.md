<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ADD8,100:512BD4&height=200&section=header&text=Omar%20Gamal&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=.NET%20Backend%20Engineer&descAlignY=58&descSize=22" width="100%" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1200&color=00ADD8&center=true&vCenter=true&width=800&lines=4+production+systems+shipped+for+real+clients;Idempotent+webhooks+%C2%B7+Concurrency-safe+payments;Redis+caching%3A+503ms+%E2%86%92+246ms;Open+to+remote+backend+roles" />

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-00ADD8?style=for-the-badge&logo=vercel&logoColor=white)](https://omar-gamal-eng.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-gamal-eng)
[![Gmail](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omar.gamal.eng@gmail.com)

</div>

---

## ⚡ Recruiter Snapshot

<div align="center">

| | |
|:--|:--|
| **🎯 Role** | .NET Backend Engineer (ASP.NET Core, Clean Architecture, CQRS) |
| **🏭 Focus** | E-commerce, payments, and third-party SaaS integrations |
| **📍 Location** | Cairo, Egypt |
| **🌍 Work mode** | Remote (currently working remotely with clients) |
| **⏳ Experience** | 1+ year shipping production backends (since Jul 2025) |
| **🎓 Education** | B.Sc. Computer Science, Benha University (May 2026) |
| **🗣️ Languages** | Arabic (native) · English (B2) |
| **📩 Contact** | omar.gamal.eng@gmail.com |

</div>

---

## 📈 Impact in Numbers

<div align="center">

| 🚀 **4** | ⚡ **60%** | ⏱️ **503 → 246 ms** | 💳 **0** | 🎓 **20+** |
|:---:|:---:|:---:|:---:|:---:|
| production systems | less DB load (Redis) | best-seller endpoint | critical payment failures | students taught |

</div>

---

## 🧭 What I Bring to a Team

- 🔒 **Correctness under concurrency**: pessimistic locking (`SELECT FOR UPDATE`) so a loyalty code can never be redeemed twice
- 🧾 **Reliable integrations**: idempotent webhook handling (Paymob, Rekaz) with Hangfire retries, safe under retries and out-of-order delivery
- ⚡ **Performance**: Redis caching that cut DB load by 60%
- 🏗️ **Maintainable architecture**: Clean Architecture, CQRS/MediatR, Repository, Unit of Work, Specification
- 🚢 **Ships end to end**: from API design to Docker, GitHub Actions CI/CD, and production deployment
- 🤝 **Works with other teams**: led backend for DentalHub, collaborating with frontend and AI teams through OpenAPI contracts
- 🧑‍🏫 **Communicates clearly**: sole curriculum author teaching 20+ students, which shows in my docs and code reviews

---

## 🏆 Experience

<table>
<tr>
<td width="50%">

### 💼 Backend Developer (Contract)
**R&S Fashion · Ziko Bags Store · Al-Ameen Cables** · Remote
*Jul 2025 — Present*

- Built and deployed production REST APIs for three freelance clients using ASP.NET Core, Clean Architecture, and CQRS
- Shipped **ElAmeenRewards**, a QR-based loyalty API with concurrency-safe redemption, fraud detection, and audit logging, plus a live Android app on Google Play
- Delivered Ziko Bags Store end to end: 131 products, 37 confirmed orders, 12,000+ EGP via Paymob with zero critical payment failures
- Cut DB load by 60% and API latency from 503ms to 246ms with Redis caching
- Integrated Paymob webhooks with idempotency and Hangfire retry jobs, preventing duplicate payments

</td>
<td width="50%">

### 🧑‍🏫 Programming Instructor
**3C School** · Remote
*May 2025 — Present*

- Designed and delivered a project-based HTML, CSS, and Python curriculum to **20+ students across 10+ cohorts**
- Sole curriculum author: lesson plans, assignments, and feedback loops built from scratch
- Iterated content each cohort based on student outcomes
- Students shipped and deployed web projects by course end

</td>
</tr>
</table>

---

## 📁 Featured Projects

<table>
<tr>
<td width="50%">

### 🔌 Al-Ameen Cables & ElAmeenRewards
[![Live](https://img.shields.io/badge/Live_Site-4CAF50?style=for-the-badge&logoColor=white)](https://alameencables.vercel.app/)
[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.alameen.cables)

**Production Freelance Project**

Corporate site plus a QR-based loyalty app: customers scan a code to earn points and confirm a cable is genuine.

- 🔒 Pessimistic locking so two scans of one code can never both succeed
- 🚨 Fraud detection & audit logging
- 🖨️ Batch QR PDF export (QuestPDF)
- 📱 Live Android app on Google Play

`ASP.NET Core` `Clean Architecture` `CQRS` `MySQL` `IMemoryCache`

</td>
<td width="50%">

### 🥊 Pro-Fighter
![Status](https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge)

**Gym Management Platform, Rekaz SaaS Integration**

Backend built around a webhook-driven subscription sync that stays correct when webhooks retry or arrive out of order.

- 🔄 Thin-webhook / fetch-full-state pattern
- 🧾 Idempotent Inbox pattern
- 🤖 AI fitness & nutrition plan generator (OpenAI)
- 🔔 Firebase push notifications, Flutter client

`ASP.NET Core` `CQRS/MediatR` `Hangfire` `Rekaz API` `Firebase` `Flutter`

</td>
</tr>
<tr>
<td width="50%">

### 🛍️ R&S Fashion E-Commerce API
[![Live](https://img.shields.io/badge/Live_Site-4CAF50?style=for-the-badge&logoColor=white)](https://r-and-s-one.vercel.app/)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/E-Commerce-API-V1)

**Production Freelance Project, .NET 9**

Fully deployed e-commerce backend serving real users with live transactions.

- ⚡ Redis: 60% less DB load, 503ms → 246ms
- 🔐 JWT auth & role-based authorization
- 🧪 xUnit tests on auth & role flows
- 🏗️ Manual CQRS across 8 domains

`.NET 9` `EF Core` `MySQL` `Redis` `Hangfire` `Paymob`

</td>
<td width="50%">

### 🛒 Bags-Shop API (Ziko Store)
[![Live Store](https://img.shields.io/badge/Live_Store-4CAF50?style=for-the-badge&logoColor=white)](https://ziko-store.vercel.app/)
[![API Docs](https://img.shields.io/badge/API_Docs-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://bags-shop.runasp.net/swagger)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/Bags-Shop-ApI)

**Production Freelance Project, .NET 10**

Powers a live store: 131 products, 37 confirmed orders, 12,000+ EGP processed.

- 💳 Paymob gateway + idempotent webhooks
- 🏗️ CQRS with MediatR
- 🔄 Hangfire discount scheduler & order jobs

`.NET 10` `EF Core` `SQL Server` `MediatR` `Paymob`

</td>
</tr>
<tr>
<td colspan="2">

### 🦷 DentalHub
[![Live Demo](https://img.shields.io/badge/Live_Demo-4CAF50?style=for-the-badge&logoColor=white)](https://unident-care.vercel.app/)
[![API Docs](https://img.shields.io/badge/API_Docs-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://dental-hup1.runasp.net/swagger/index.html)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/Dental-Hub)

**Backend Lead, Cross-Institutional Dental Collaboration Platform (.NET 9)**

Platform for doctors, students, patients, and administrators: patient case management, consultation scheduling, JWT auth with role-based authorization, Cloudinary media storage, Redis caching, Hangfire jobs, and 20+ documented REST endpoints. Multi-stage Docker builds, Docker Compose, and GitHub Actions CI/CD to production.

`.NET 9` `EF Core` `Redis` `Hangfire` `Cloudinary` `Docker` `GitHub Actions`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,python,js,mysql,redis,docker,githubactions,git,postman,azure,rabbitmq,firebase,flutter&perline=7" />

<br><br>

**Backend:** ASP.NET Core · EF Core · RESTful API design · Hangfire · MediatR
**Architecture:** Clean Architecture · CQRS · Repository · Unit of Work · Specification · SOLID · Dependency Injection
**Data:** SQL Server · MySQL · Redis · T-SQL · Query optimization
**Testing:** xUnit · NUnit · Moq · Integration testing
**Integrations:** Paymob · Cloudinary · Firebase Cloud Messaging · Rekaz API · OpenAI API · MailKit
**DevOps:** Docker · GitHub Actions · Swagger/Scalar · Vercel
**Currently learning:** Azure · RabbitMQ

</div>

---

## 🎓 Education

**B.Sc. Computer Science**, Benha University, Faculty of Science (May 2026), GPA 3.1/4.0
Coursework: Data Structures, Algorithms, Database Systems, Software Engineering, Operating Systems, OOP

---

## 📊 GitHub Activity

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=omargamal1121&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omargamal1121&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

<img src="https://streak-stats.demolab.com/?user=omargamal1121&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=omargamal1121&theme=tokyo-night&hide_border=true&area=true" width="100%" />

</div>

---

## 📫 Let's Work Together

<div align="center">

**Open to remote backend roles** in e-commerce, fintech, or SaaS, on a team that cares about correctness under real load.

[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omar.gamal.eng@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-gamal-eng)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-00ADD8?style=for-the-badge&logo=vercel&logoColor=white)](https://omar-gamal-eng.vercel.app)

*"Every project is a product, not just practice."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:00ADD8&height=120&section=footer" width="100%" />

</div>
