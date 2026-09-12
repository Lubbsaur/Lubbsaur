### Anders Nyvoll Bergh
**Fullstack Developer and tinkerer**

I build full products end-to-end — frontend, backend, infrastructure, and the occasional 3D visualization because it's fun. Based in Norway.

- 🔭 Currently building **[Berghweb](https://berghweb.no)** — a personal platform combining a portfolio, a data-driven Fantasy Premier League analysis tool, and a couple of side experiments, all running on a self-built Cloudflare Workers backend.
- 🐑 Also building **Lamb**, a location-based audio guide app (React Native + Appwrite) — in active development.
- 🌍 I like projects that mix real data with visualization — climate data, sports stats, maps.
- 📫 Reach me at berghjunior@gmail.com

---

### Featured project — Berghweb

A production site I designed and built solo, live at **[berghweb.no](https://berghweb.no)**.

- **Frontend:** React + Vite, Three.js/GSAP for 3D scenes, Sanity as a headless CMS for content
- **Backend:** Cloudflare Workers (single edge worker as API + router), D1 (SQLite at the edge) for storage, cron-triggered scheduled jobs
- **Features:** cookie-based auth with rate limiting, Stripe checkout + webhook-verified payments, transactional email, a fantasy football transfer-optimizer that projects points across a scoring horizon and respects squad/budget/club-limit constraints, a climate-data explorer

The full source is private (it's a real product, not a demo), but the core backend patterns — session auth, rate limiting, the Worker router, password reset flow — are extracted and documented in **[pantropos-backend-showcase](https://github.com/Lubbsaur/pantropos-backend-showcase)**.

---

### In progress — Lamb

A location-based audio guide app (React Native/Expo + Appwrite): guide entries trigger as you walk near them, with a collectible-badge and leaderboard layer on top of a custom avatar builder. Aiming to take this from side project to a real product.

Still private while it's early, but the auth flow, profile system, and avatar builder are extracted in **[lamb-showcase](https://github.com/Lubbsaur/lamb-showcase)** — the proximity-trigger logic, scoring engine, and content model stay private since that's the actual product design.

---

### Tech I work with

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

### Other repos

- **[fpl-proxy](https://github.com/Lubbsaur/fpl-proxy)** — a small proxy for Fantasy Premier League data
- **[WeatherApp](https://github.com/Lubbsaur/WeatherApp)** — first project learning Java
- **[SpillutviklingX-showcase](https://github.com/Lubbsaur/SpillutviklingX-showcase)** — gameplay scripts (NavMesh enemy AI, quest/dialogue system, combat) from a Unity dungeon-crawler RPG; the full project stays private since it also bundles licensed asset packs I can't redistribute
