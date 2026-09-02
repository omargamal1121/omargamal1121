<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=00ADD8&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B+I'm+Omar+Gamal;Backend+Developer+%7C+E-Commerce+%7C+Instructor" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-gamal-backend)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Omargamal1132004@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/omargamal1121)

### 🎯 .NET Backend Engineer &nbsp;·&nbsp; E-Commerce &amp; SaaS Integrations &nbsp;·&nbsp; Instructor

I build backend systems that stay correct under real load — production APIs for four clients, handling live payments, loyalty points, and webhook syncs with third-party platforms.

</div>

<br>

<div align="center">

| 🚀 4 systems live | 💳 12,000+ EGP processed | ⚡ 60% less DB load | 🧾 idempotent webhooks | 🎓 20+ students taught |
|:---:|:---:|:---:|:---:|:---:|

</div>

---

## 📁 Projects

<table>
<tr>
<td width="50%">

### 🔌 Al-Ameen Cables & ElAmeenRewards
[![Live](https://img.shields.io/badge/Live_Site-4CAF50?style=for-the-badge&logoColor=white)](https://alameencables.vercel.app/)
[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.alameen.cables)

**Production Freelance Project**

Corporate site plus a QR-based loyalty app: customers scan a code to earn points and confirm a cable is genuine. Redemption is guarded with pessimistic row locking so two scans of the same code can never both succeed.

**Highlights:**
- 🔒 Pessimistic locking (`SELECT FOR UPDATE`) for concurrency-safe redemption
- 🚨 Fraud detection & audit logging
- 🖨️ Batch QR PDF export (QuestPDF)
- 📱 Live Android app on Google Play

**Stack:** `ASP.NET Core` `Clean Architecture` `CQRS` `MySQL` `IMemoryCache`

</td>
<td width="50%">

### 🥊 Pro-Fighter
![Status](https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge)

**Gym Management Platform — Rekaz SaaS Integration**

Gym management backend integrating the Rekaz platform, built around a resilient webhook-driven subscription sync that stays correct even when webhooks retry or arrive out of order.

**Highlights:**
- 🔄 Webhook-driven subscription sync (thin-webhook / fetch-full-state pattern)
- 🧾 Idempotent Inbox pattern for safe webhook retries
- 🤖 AI-powered fitness & nutrition plan generator (OpenAI)
- 🔔 Firebase push notifications, Flutter mobile client

**Stack:** `ASP.NET Core` `CQRS/MediatR` `Hangfire` `Rekaz API` `Firebase` `Flutter`

</td>
</tr>
<tr>
<td width="50%">

### 🛍️ R&S Fashion E-Commerce API
[![Live](https://img.shields.io/badge/Live_Site-4CAF50?style=for-the-badge&logoColor=white)](https://r-and-s-one.vercel.app/)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/E-Commerce-API-V1)

**Production Freelance Project — .NET 9**

Fully deployed e-commerce backend serving real users with live transactions.

**Highlights:**
- ⚡ Redis caching — 60% reduction in DB load
- 🔐 JWT authentication & role-based authorization
- 🧪 xUnit tests across auth & role management flows
- 🏗️ Manual CQRS across 8 domains

**Stack:** `.NET 9` `ASP.NET Core` `EF Core` `MySQL` `Redis` `Hangfire` `Paymob`

</td>
<td width="50%">

### 🛒 Bags-Shop API (Ziko Store)
[![Live Store](https://img.shields.io/badge/Live_Store-4CAF50?style=for-the-badge&logoColor=white)](https://ziko-store.vercel.app/)
[![API Docs](https://img.shields.io/badge/API_Docs-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](http://bags-shop.runasp.net/swagger)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/Bags-Shop-ApI)

**Production Freelance Project — .NET 10**

Powers a live online store: 131 products, 37 confirmed orders, 12,000+ EGP processed via Paymob with zero critical payment failures.

**Highlights:**
- 🏗️ CQRS with MediatR for clean separation
- 💳 Paymob gateway + idempotent webhook handling
- 🔄 Hangfire discount scheduler & order jobs

**Stack:** `.NET 10` `ASP.NET Core` `EF Core` `SQL Server` `MediatR` `Paymob`

</td>
</tr>
<tr>
<td colspan="2">

### 🦷 DentalHub
[![Live Demo](https://img.shields.io/badge/Live_Demo-4CAF50?style=for-the-badge&logoColor=white)](https://unident-care.vercel.app/)
[![API Docs](https://img.shields.io/badge/API_Docs-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://dental-hup1.runasp.net/swagger/index.html)
[![GitHub](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/omargamal1121/Dental-Hub)

**Backend Lead — Cross-Institutional Dental Collaboration Platform (.NET 9)**

Led backend development for a platform serving doctors, students, patients, and administrators — patient case management, consultation scheduling, and 20+ documented REST endpoints, containerized and deployed via GitHub Actions.

**Stack:** `.NET 9` `ASP.NET Core` `EF Core` `Redis` `Docker` `GitHub Actions`

</td>
</tr>
</table>

---

## 🏆 Experience

<table>
<tr>
<td width="50%" align="center">

### 💼 Freelance Backend Developer
*Jul 2025 — Present*

Built production-grade backends for **three real clients**
- R&S Fashion, Ziko Bags Store, Al-Ameen Cables
- Scalable REST APIs, Clean Architecture, CQRS
- Payment gateway integrations (Paymob)
- Redis caching (60% DB load reduction, 503ms → 246ms)
- QR-based loyalty system with fraud detection

</td>
<td width="50%" align="center">

### 🧑‍🏫 Programming Instructor
*May 2025 — Present*

Teaching at **3C School Egypt**
- HTML, CSS & Python fundamentals
- Hands-on project-based curriculum
- 20+ students across 10+ cohorts
- Practical, real-world exercises

</td>
</tr>
</table>

---

## 🛠️ Technology Stack

<div align="center">

**Backend:** ![.NET](https://img.shields.io/badge/.NET_9%2F10-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Data:** ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Architecture:** ![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-00ADD8?style=flat-square&logoColor=white) ![CQRS](https://img.shields.io/badge/CQRS_MediatR-FF4081?style=flat-square&logoColor=white)

**Integrations:** ![Paymob](https://img.shields.io/badge/Paymob-1E90FF?style=flat-square&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase_FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

**DevOps:** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Hangfire](https://img.shields.io/badge/Hangfire-00ADD8?style=flat-square&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Currently learning:** ![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

</div>

---

<details>
<summary><b>👨‍💻 About Me — how I approach backend work</b></summary>
<br>

```csharp
public class OmarGamal : BackendDeveloper
{
    public string CurrentRole    { get; set; } = "Freelance .NET Backend Developer";
    public string SecondRole     { get; set; } = "Programming Instructor @ 3C School";

    public List<string> CoreExpertise { get; set; } = new()
    {
        "ASP.NET Core & .NET 9/10",
        "Entity Framework Core",
        "Clean Architecture & CQRS",
        "RESTful API Development",
        "Webhook-Driven SaaS Integrations",
        "E-Commerce System Design"
    };

    public string Mission { get; set; } = "Build production-grade systems for real clients";
}
```

I believe in:
- 🏗️ **Clean Architecture** — systems that scale and evolve gracefully
- 🔐 **Security-first design** — proper authentication, authorization, and data protection
- ⚡ **Performance optimization** — smart caching and background job processing
- 🔄 **Resilient integrations** — idempotent webhook handling and concurrency-safe operations
- 📝 **Code quality** — maintainable, tested, and well-documented code

</details>

<details>
<summary><b>📊 GitHub Statistics</b></summary>
<br>

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=omargamal1121&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omargamal1121&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=omargamal1121&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

</details>

<details>
<summary><b>🎯 2026 Goals</b></summary>
<br>

| Now | Mid-Year | End of Year |
|-----|----------|-------------|
| 🐳 Docker on all projects | ☁️ Azure AZ-900 certification | 🔄 RabbitMQ in production |
| 🔄 GitHub Actions CI/CD everywhere | 📈 Expand freelance portfolio | 🏗️ Microservices fundamentals |
| 🔐 OAuth2 & ASP.NET Identity | 🌐 Open-source contributions | 🎓 Master's application (Germany) |

</details>

---

## 📫 Let's Connect

<div align="center">

Actively seeking **remote backend roles** — e-commerce or fintech, on a team that cares about correctness under real load.

[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Omargamal1132004@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-gamal-backend)
[![GitHub](https://img.shields.io/badge/Follow_on_GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/omargamal1121)

![Profile Views](https://komarev.com/ghpvc/?username=omargamal1121&color=00ADD8&style=for-the-badge)

*"Every project is a product, not just practice."*

</div>
