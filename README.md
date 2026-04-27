<img align="right" src="images/meprogrammer.png" width="360" style="margin-left: 40px; margin-bottom: 20px;"/>

## Hi, I'm Kuba 👋

I'm a **24-year-old full-stack developer** from **Warsaw, Poland** 🇵🇱 with **6 years of commercial experience**.

I build production-ready web applications end-to-end — from database schema to deployed frontend. My current focus is **Go backends** paired with **Next.js**, real-time systems, and clean API design.

Outside of web dev, I'm passionate about **automation and robotics** — I enjoy bringing software into the physical world.

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
</p>

---

## 🚀 Featured Project

### [🍕 Pizza Ordering App](https://github.com/bombel1337/pizza-project) — [Live Demo](https://pizza.kubap.pl)

Full-stack pizza ordering platform with real-time order tracking and admin chat.

- **Backend** — Go, Gin, PostgreSQL, Redis, WebSocket hub (goroutine-based broadcaster)
- **Frontend** — Next.js, TypeScript, Tailwind CSS, SSR, i18n (PL/EN)
- **Auth** — JWT in HttpOnly cookies, refresh token rotation, session invalidation, separate customer/admin sessions
- **Real-time** — WebSocket hub (goroutine broadcaster), live order status push, customer↔admin live chat with online presence indicators
- **Security** — per-IP rate limiting (Redis + in-memory fallback), SQL injection & XSS detection, CORS, security headers (CSP, X-Frame-Options)
- **Images** — self-hosted, on-the-fly resizing via `?w=`/`?h=` query params using bilinear scaling, served as JPEG regardless of source format
- **i18n** — Polish (no URL prefix) + English (`/en/`), locale auto-detection from cookie → Accept-Language, all API errors translated
- **Admin** — activity logs with IP geolocation (GeoIP), order state machine, hot-reload menu from JSON without server restart
- **UX** — add-to-cart fly animation, draggable floating chat widget, skeleton loading states, optimistic UI
- **Deployed** on a Windows VPS behind Caddy reverse proxy with Cloudflare

---

## 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bombel1337&layout=compact&theme=tokyonight" />
</p>

---

## 📫 Get in Touch

![Profile Views](https://komarev.com/ghpvc/?username=bombel1337&color=brightgreen&style=flat-square)

- 💼 [LinkedIn](https://www.linkedin.com/in/przygodajacob/)
- 📧 [realprogrammer@bombelix.com](mailto:realprogrammer@kubap.pl)
