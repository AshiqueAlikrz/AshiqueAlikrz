<h2 align="left">Hi 👋, I'm Ashique Ali</h2>

**Full-stack developer · TypeScript · React · React Native · Node.js**

I build business software that people use every day: billing, VAT, reports, and the mobile apps that go with them. I take a product from idea to production myself: the API, the web app, the mobile app, the queues behind them, and the Docker setup they ship in.

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AshiqueAlikrz&show_icons=true&include_all_commits=true&count_private=true&theme=dracula" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=AshiqueAlikrz&layout=compact&card_width=320&langs_count=6&theme=dracula" height="150" alt="Top languages" />
</div>
<div align="center">
  <img src="https://streak-stats.demolab.com?user=AshiqueAlikrz&theme=dark&border_radius=5" height="170" alt="GitHub streak" />
</div>

---

### 🚀 What I'm building: Al Wahda ERP

A multi-company ERP for a UAE typing and business-services centre, used daily by front-desk staff on web and Android tablets. *(Client project; the code is private.)*

**Web app** (React · TypeScript · Redux Toolkit · Vite)
- Tax invoices, proformas and quotations with UAE VAT: per-line VAT that either the company or the customer pays, discounts, and profit per invoice
- Daily and monthly reports, dashboard, petty cash, customers, service catalogue
- Tenancy contract generator: fill in the form, preview the PDF, share it, and edit it again later

**Mobile app** (React Native · Expo · Expo Router · TanStack Query)
- Every web feature on phones and tablets, with tablet layouts designed for Samsung Galaxy Tab
- **Works offline:** lists are cached on the device, and invoices created without internet wait in an outbox and are sent automatically when the connection returns, with safeguards against duplicates
- Logins kept in the Android Keystore / iOS Keychain, automatic sign-out when the session expires
- Invoices as PDF, shared to WhatsApp or email, or printed from the tablet
- Release builds and per-environment config with EAS

**Backend** (Node.js · Express · TypeScript · MongoDB)
- Multi-company data: every query is limited to the signed-in user's company
- JWT auth, Redis rate limiting, input validation, Jest test suite
- **Large exports through a queue:** BullMQ + Redis workers build exports of a million rows in the background, upload them to object storage, and send the user a download link
- A separate AI service (Node.js + Gemini) for the in-app Copilot

**Infrastructure**
- Docker and Nginx for local and production setups, deployed on Vercel
- Planned move to AWS: ECS, ElastiCache / MemoryDB, and MongoDB Atlas over PrivateLink

---

### 🛠️ Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,react,redux,vite,tailwind,html,css&theme=dark" alt="Front-end" /><br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,redis,jest&theme=dark" alt="Back-end" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,nginx,aws,vercel,git,github,postman,vscode&theme=dark" alt="Tools" />
</p>

| Area | What I use |
|---|---|
| **Front-end** | React, TypeScript, Redux Toolkit, Vite, Tailwind CSS, Vitest |
| **Mobile** | React Native, Expo, Expo Router, TanStack Query, EAS Build |
| **Back-end** | Node.js, Express, MongoDB / Mongoose, Redis, BullMQ, JWT, Jest |
| **DevOps** | Docker, Nginx, Vercel, AWS (in progress) |
| **AI** | Gemini API, LLM-powered assistants inside business apps |

---

### 💡 What I care about

- **Correct numbers:** invoice and VAT maths is shared, unit tested, and gives the same result on web and mobile
- **Apps that cope with real conditions:** weak shop Wi-Fi, shared tablets, sessions that expire
- **Security by default:** data scoped to each company, secrets stored in the device's secure storage, no demo passwords left in release builds
- **Scaling only when it's needed:** caching, queues and load balancing, added when the load calls for them

---

### 📫 Contact

<p align="left">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="32" alt="LinkedIn" /></a>
  <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="32" alt="Email" /></a>
  <a href="https://wa.me/YOUR-NUMBER"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" height="32" alt="WhatsApp" /></a>
  <a href="https://www.instagram.com/YOUR-HANDLE"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" height="32" alt="Instagram" /></a>
  <a href="https://www.youtube.com/@YOUR-CHANNEL"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" height="32" alt="YouTube" /></a>
</p>

Open to full-stack and React / React Native roles. Feel free to reach out.
