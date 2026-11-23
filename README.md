<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:0ea5e9&height=200&section=header&text=Ashique%20Ali&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Full-stack%20Developer%20%E2%80%A2%20Web%20%E2%80%A2%20Mobile%20%E2%80%A2%20Backend&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Ashique Ali" />
</p>

<p align="center">
  <a href="https://github.com/AshiqueAlikrz">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=620&lines=I+build+business+software+people+use+daily;React+%E2%80%A2+React+Native+%E2%80%A2+Node.js+%E2%80%A2+TypeScript;Offline-first+mobile+apps+for+real+shops;Queues%2C+caching+and+Docker+in+production" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/YOUR-NUMBER"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <img src="https://komarev.com/ghpvc/?username=AshiqueAlikrz&style=for-the-badge&color=0ea5e9&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 👨‍💻 About me

```ts
const ashique = {
  role: "Full-stack developer",
  location: "UAE",
  buildsWith: ["TypeScript", "React", "React Native", "Node.js", "MongoDB"],
  currentlyBuilding: "Al Wahda ERP: web + Android tablet app + API",
  focus: ["offline-first mobile", "correct VAT maths", "secure multi-company data"],
  openTo: "Full-stack and React / React Native roles",
};
```

I take products from idea to production on my own: the API, the web app, the mobile app, the background workers, and the Docker setup they ship in.

---

## 🚀 Featured project

<table>
<tr>
<td>

### 🧾 Al Wahda ERP
**A multi-company ERP for a UAE business-services centre, used daily by front-desk staff on web and Android tablets.**
<sub>Client project · private code</sub>

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/React_Native-0B1220?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-E0234E?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

| | Highlights |
|---|---|
| 🌐 **Web** | Tax invoices, proformas and quotes with UAE VAT, reports, petty cash, tenancy-contract PDF generator |
| 📱 **Mobile** | Works offline with an invoice outbox, secure login storage, PDF share and print, tablet layouts |
| ⚙️ **API** | Data scoped to each company, JWT, Redis rate limits, Jest tests |
| 📦 **Scale** | BullMQ workers export a million rows in the background and send the user a download link |
| 🤖 **AI** | In-app Copilot powered by a Node.js + Gemini service |

</td>
</tr>
</table>

<details>
<summary><b>🔍 How it's built (click to expand)</b></summary>
<br/>

```text
 Android tablet (Expo)          Web (React + Vite)
   │ cached data + outbox          │
   └──────────────┬────────────────┘
                  ▼
        Nginx ──► Express API (TypeScript, JWT, rate limits)
                  │          │                │
               MongoDB     Redis ◄── BullMQ export workers ──► object storage
                  │
            AI service (Node.js + Gemini)
```

- **Offline-first mobile:** TanStack Query cache saved on the device; invoices made offline are queued per user and sent in order, and are never re-sent automatically if they may already have reached the server
- **One set of invoice maths:** VAT, discount and profit logic is shared and unit tested, so web and mobile always agree
- **Built to grow:** Dockerised services, health checks, and a planned AWS setup (ECS, ElastiCache, Atlas PrivateLink)

</details>

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,redux,vite,tailwind,html,css&perline=8&theme=dark" alt="Front-end" />
  <br/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,redis,jest,docker,nginx,aws&perline=8&theme=dark" alt="Back-end and DevOps" />
  <br/>
  <img src="https://skillicons.dev/icons?i=git,github,vercel,postman,vscode&perline=8&theme=dark" alt="Tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/BullMQ-E0234E?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
</p>

---

## 📊 GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AshiqueAlikrz&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&border_radius=12" height="165" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=AshiqueAlikrz&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&border_radius=12" height="165" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=AshiqueAlikrz&theme=tokyonight&hide_border=true&border_radius=12" height="165" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AshiqueAlikrz&theme=tokyo-night&hide_border=true&area=true&radius=12" width="95%" alt="Contribution graph" />
</p>

---

## 💡 How I work

| | |
|---|---|
| ✅ **Correct numbers** | Money and VAT logic is unit tested and shared between apps |
| 📶 **Real-world ready** | Built for weak Wi-Fi, shared tablets and sessions that expire |
| 🔐 **Secure by default** | Data scoped to each company, device secure storage, no demo passwords in release builds |
| 📈 **Scale when needed** | Caching, queues and load balancing added when the load calls for them |

---

<p align="center">
  <b>Open to full-stack and React / React Native roles. Let's build something useful. 🤝</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" alt="" />
</p>
