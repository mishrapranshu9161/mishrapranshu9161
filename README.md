<!-- Profile README for github.com/mishrapranshu9161/mishrapranshu9161
     Anything inside <!-- ... --> comments is hidden on GitHub. Uncomment lines marked TODO once you have the link. -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:00f7ff&height=140&section=header" alt="header" width="100%"/>

<a href="https://github.com/mishrapranshu9161">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=00F7FF&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Pranshu+Mishra;AI-integrated+Full-Stack+Developer;Flask+%C2%B7+LLMs+%C2%B7+MERN+%C2%B7+Computer+Vision;Building+systems+that+think" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranshu-mishra-386873322)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mishrapranshu9161@gmail.com)
<!-- TODO: uncomment after you add your live portfolio link
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR-PORTFOLIO-URL)
-->
![Profile Views](https://komarev.com/ghpvc/?username=mishrapranshu9161&color=00f7ff&style=for-the-badge&label=PROFILE+VIEWS)

**[Projects](#-featured-projects) · [Tech Stack](#-tech-stack) · [Experience](#-experience) · [GitHub Activity](#-github-activity) · [Contact](#-lets-connect)**

</div>

---

## 👋 About Me

```python
class PranshuMishra:
    role      = "AI-integrated Full-Stack Developer"
    education = "B.Tech CSE · SRMU Lucknow · Class of 2027"
    location  = "Lucknow, India"
    focus     = ["LLM apps", "Flask / REST APIs", "MERN stack", "Computer Vision"]
    building  = "UniversityNova — AI-powered University ERP"
    learning  = ["Deep Learning", "NLP", "Computer Networks"]
    status    = "Open to internships & entry-level roles"
```

---

## 🚀 Featured Projects

| Project | What it does | Stack | Links |
|---|---|---|---|
| 🎓 **UniversityNova** | AI-powered University ERP with face-recognition attendance, a syllabus-aware study bot and fee management | Flask · SQLite · OpenCV · Groq LLM | [Repo](https://github.com/mishrapranshu9161/UniversityNOVAA) <!-- TODO: add · [Live Demo](URL) --> |
| 🛡️ **FakeShield** | Misinformation detector: credibility score, editorial bias detection, fact-check lookup | Python · Groq LLM · Google Fact Check API · Vite | [Live Demo](https://fakeshield-nine.vercel.app) · [Repo](https://github.com/mishrapranshu9161/fakeshield) |
| 🏥 **MediPredict** | Hospital management system with role-based portals, appointments, prescriptions and symptom risk assessment | MongoDB · Express · React · Node.js | [Repo](https://github.com/mishrapranshu9161/Medipredict) |

<details>
<summary><b>🎓 UniversityNova — click for details</b></summary>

<br/>

**Problem:** colleges juggle attendance sheets, fee counters and scattered study material across different tools.
**Solution:** one Flask-based platform with separate Admin, Teacher and Student roles.

- 📍 **Smart Attendance** — GPS + face recognition
- 🤖 **AI Study Bot** — syllabus-aware answers via Groq LLM
- 💳 **Fee Management** — PDF + UPI + NetBanking
- 📊 **Analytics** — Chart.js dashboard
- 🔐 **Role system** — Admin · Teacher · Student

```mermaid
flowchart LR
    U["Admin / Teacher / Student"] --> A["Flask app"]
    A --> R["routes"]
    R --> M["models (SQLAlchemy)"]
    M --> DB[("SQLite")]
    R --> T["utils"]
    T --> F["OpenCV face recognition"]
    T --> L["Groq LLM study bot"]
```

[📂 View repository](https://github.com/mishrapranshu9161/UniversityNOVAA)

</details>

<details>
<summary><b>🛡️ FakeShield — click for details</b></summary>

<br/>

**Key insight:** a news article can be *real but biased*. FakeShield scores credibility **and** labels editorial slant.

- 🧠 **Bias detection** — Neutral · Left-Leaning · Right-Leaning · Sensationalist · Pro-Government · Anti-Government
- ✅ **AI credibility score** with suspicious-keyword highlights
- 🔎 **Google Fact Check API** results alongside the AI verdict
- 📸 **Share as image** and ⬇️ **Export history as CSV**

[🚀 Try it live](https://fakeshield-nine.vercel.app) · [📂 View repository](https://github.com/mishrapranshu9161/fakeshield)

</details>

<details>
<summary><b>🏥 MediPredict — click for details</b></summary>

<br/>

- 👥 **3 role-based portals** — Patient, Doctor, Admin (JWT + bcrypt, Helmet, rate limiting)
- 🗓️ **Double-booking prevention** — server-side validation + compound index on doctor/date/slot
- 🖨️ **Printable digital prescriptions** and lab report tracking
- 📈 **Admin analytics** with Recharts
- 🧠 **Symptom risk engine** — rule-based weighted scoring, built as a swappable service so a Python ML model can replace it later

[📂 View repository](https://github.com/mishrapranshu9161/Medipredict)

</details>

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Backend & Databases**

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**AI / ML**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_LLM-F55036?style=for-the-badge)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 💼 Experience

- **Intern — Netcamp.in**
  <!-- TODO: add role, duration and 2 bullets: what you built + a measurable result (e.g. "Built X using Y, reduced Z by N%") -->

---

## 📈 GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mishrapranshu9161/mishrapranshu9161/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mishrapranshu9161/mishrapranshu9161/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/mishrapranshu9161/mishrapranshu9161/output/github-contribution-grid-snake.svg">
</picture>

<img src="https://streak-stats.demolab.com?user=mishrapranshu9161&theme=radical&hide_border=true&border_radius=10" alt="Streak Stats" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mishrapranshu9161&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" width="100%" />

</div>

---

## 🎯 Let's Connect

I'm looking for **internships and entry-level roles** in AI / full-stack development. If you're hiring or want to collaborate, reach out:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranshu-mishra-386873322)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mishrapranshu9161@gmail.com)

<div align="center">

*"Building systems that think."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f7ff,100:0f2027&height=100&section=footer" alt="footer" width="100%"/>

</div>
