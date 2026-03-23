<h1 align="center">Hi, I'm Maharshi Patel</h1>

<p align="center">
  Full-Stack Developer &nbsp;·&nbsp; Hamilton, ON &nbsp;·&nbsp; Open to Work
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/maharshi-patel-software-developer">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://rookiebulls.com">rookiebulls.com</a>
  &nbsp;·&nbsp;
  patel.maharshi.1996@gmail.com
</p>

---

### About Me

I'm a software developer based in Hamilton, Ontario. I completed a Software
Development diploma at Mohawk College (GPA: 87, Dean's Honor) after spending
three years as a lab technologist in chemical engineering — a background that
trained me to care about precision, process, and getting things right the first
time.

I did a co-op at Pollard Windows where I worked on ERP automation, SVG tooling
in Python, and full-stack web features using Django. Since then I have been
building RookieBulls — a production-deployed, full-stack stock trading
simulator — learning DevOps, backend architecture, and system design by doing,
not just studying.

I learn by building real things and deploying them. Every decision I make has
a reason, and I can explain it.

---

### What I'm Building

**[RookieBulls](https://github.com/maharshidpatel/RookieBulls)** — a
production-deployed stock trading simulator for North American equities.
Users receive $100,000 in virtual credits and simulate buying and selling
using delayed real market data.

What is interesting about it architecturally:

- Redis cache-aside layer that reduced external API calls by 97%
  (from ~39,000 to ~400 per day)
- Wallet built as an immutable transaction ledger — balance is always
  derived, never directly mutated
- JWT auth with full token lifecycle — access tokens, refresh rotation,
  HTTP-only cookies, server-side invalidation
- Email verification pipeline with crypto tokens, 24h expiry, and
  rate-limited resend (3/hr per IP)
- Deployed on a DigitalOcean VPS — Docker Compose, Nginx reverse proxy,
  Let's Encrypt SSL, firewall, non-root deploy user
- CI/CD via GitHub Actions — push to main deploys both backend and
  frontend automatically

**Live:** https://rookiebulls.com

---

### Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)

**Databases & Cache**

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white)

**DevOps & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat&logo=digitalocean&logoColor=white)

---

### Projects

| Project | Description | Stack |
|---|---|---|
| [RookieBulls](https://github.com/maharshidpatel/RookieBulls) | Production-deployed stock trading simulator | Node.js, React, MongoDB, Redis, Docker |
| [Python FAQ Chatbot](https://github.com/maharshidpatel/Python-FAQ_chat_bot) | Regex-driven FAQ bot with ChatGPT API integration | Python |
| [DSA — Java Assignments](https://github.com/maharshidpatel/DSA-JAVA_Assignments) | Data structures and algorithm problems in Java | Java |
| [Web Dev & Java Assignments](https://github.com/maharshidpatel/Beginner-WebDev-and-Java-Assignments) | Foundational web and Java coursework | HTML, CSS, Java |

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=maharshidpatel&show_icons=true&theme=default&hide_border=true&count_private=true" height="150"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=maharshidpatel&layout=compact&hide_border=true&theme=default" height="150"/>
</p>

---

### Certifications

| Certification | Issuer | Date |
|---|---|---|
| SQL Fundamentals (26 hrs) | DataCamp | Jan 2026 |
| SQL Intermediate | HackerRank | Nov 2025 |
| SQL Basic | HackerRank | Nov 2025 |
| Intermediate SQL | DataCamp | Nov 2025 |
| Foundations: Data, Data, Everywhere | Google | Jul 2025 |
| Azure Fundamentals (AZ-900) | Microsoft | Nov 2024 |

---

### Background

Before software, I spent three years running ICP-OES instrumentation and
validating chemical datasets at a certified laboratory. The discipline of
working in an ISO-compliant environment — where precision and documentation
are non-negotiable — transferred directly into how I write code and
structure systems.

Career transition was deliberate. I went back to school, earned a Software
Development diploma, landed a co-op, and have been building in public
since.

---

<p align="center">
  <a href="https://www.linkedin.com/in/maharshi-patel-software-developer">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:patel.maharshi.1996@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://rookiebulls.com">
    <img src="https://img.shields.io/badge/RookieBulls-Live-brightgreen?style=flat"/>
  </a>
</p>
